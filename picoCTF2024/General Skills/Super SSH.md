# Super SSH
Author: JEFFERY JOHN

Description: Using a Secure Shell (SSH) is going to be pretty important.
Can you `ssh` as `ctf-player` to `titan.picoctf.net` at port `61453` to get the flag?
You'll also need the password `xxxxxxxx`. If asked, accept the fingerprint with `yes`.
If your device doesn't have a shell, you can use: https://webshell.picoctf.org
If you're not sure what a shell is, check out our Primer: https://primer.picoctf.com/#_the_shell

Hint:
- https://linux.die.net/man/1/ssh
- You can try logging in 'as' someone with <user>@titan.picoctf.net
- How could you specify the port?
- Remember, passwords are hidden when typed into the shell
---
## POC
Dari deskripsi bisa kita lihat perintahnya. Kita diharuskan untuk masuk ssh dengan user `ctf-player`. Kita gunakan terminal dan perintah `ssh ctf-player@titan.picoctf.net -p 61453` untuk masuk. Masukkan password yang telah diberikan dan ketik yes saat muncul pesan fingerprint. Dan flag sudah kita dapatkan.

Flag: `picoCTF{s3cur3_c0nn3ct10n_xxxxxxxx}`

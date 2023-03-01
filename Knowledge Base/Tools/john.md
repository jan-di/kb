Crack PGP key
```shell
gpg2john jnelson.pgp >hash
john hash
john hash --wordlist=SecLists/Passwords/Leaked-Databases/rockyou-10.txt
```

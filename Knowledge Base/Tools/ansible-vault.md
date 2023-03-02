
Decrypt vaulted string
```shell
echo '$ANSIBLE_VAULT;1.1;AES256  
encrypted-string-here' | ansible-vault decrypt --vault-id vaultid
```
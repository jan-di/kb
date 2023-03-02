Show certificates froma file:
```shell
openssl x509 -in $FILE -noout -text
```

Show certificates from a TLS encrypted endpoint:
```shell
openssl s_client -connect my.domain.example:443 </dev/null 2>/dev/null | openssl x509 -noout -text
```
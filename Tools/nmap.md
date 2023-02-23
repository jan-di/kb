scan all ports
```shell
nmap -p- -T5 1.2.3.4
```

detect application/version on specific port

```shell
nmap -p80 -sC -sV 1.2.3.4
```

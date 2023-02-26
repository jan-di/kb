

## API

Add ssh key via API
```shell
curl --data-urlencode "key=$(cat sshkey.pub)" --data-urlencode "title=somenicetitle" -X POST -H "PRIVATE-TOKEN: xxx“ [https://git.cgm.ag/api/v4/user/keys](https://git.cgm.ag/api/v4/user/keys)
```
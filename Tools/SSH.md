curl --data-urlencode "key=$(cat mha_pipeline_2023-12-22.pub)" --data-urlencode "title=mha_pipeline_2023-12-22" -X POST -H "PRIVATE-TOKEN: xxx“ [https://git.cgm.ag/api/v4/user/keys](https://git.cgm.ag/api/v4/user/keys)

  

SSH mit bestimmtem Key, ignoriere Keys vom Agent

```shell
ssh -i path/to/key -o "IdentitiesOnly=yes" git@server.example
```
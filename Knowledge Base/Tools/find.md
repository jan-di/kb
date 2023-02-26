
use `-exec` to execute other binaries in context of find
```shell
sudo find /root -name "*.txt" -exec cat {} \;
```

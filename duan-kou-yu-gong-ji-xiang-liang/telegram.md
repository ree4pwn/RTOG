---
description: 针对Telegram各平台的取证方法
---

# Telegram

## Windows Desktop

tdata目录中保存了已登陆的当前session，对于telegram来说，拥有了session等于拥有当前账户的登陆权限。tdata所在路径为 \*%userprofile%/AppData/Roaming/Telegram Desktop/tdata\*，将tdata目录拷出即可，可能会遇到部分文件锁定的情况，并不影响。

```text
xcopy tdata tdata_bak /E /H /C /I
```


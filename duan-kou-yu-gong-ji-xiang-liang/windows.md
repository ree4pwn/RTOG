# Windows

## WiFi

获取曾连接wifi

```text
netsh wlan show profiles
```

获取曾连接wifi的密码

```text
netsh wlan show profile name="wifi名称" key=clear
```

获取周边wifi

```text
netsh wlan show networks
```

获取所有Wlan信息

```text
netsh wlan show all
```




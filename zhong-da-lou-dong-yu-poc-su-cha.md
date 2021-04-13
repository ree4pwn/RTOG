---
description: 重大漏洞与PoC速查
---

# 重大漏洞与PoC速查

## 2020

* **CVE-2021-21972** 
  * 受影响产品
    * VMware vCenter RCE
  * 漏洞简介
    * vSphere Client（HTML5）在 vCenter Server 插件中存在一个远程执行代码漏洞。未授权的攻击者可以通过开放 443 端口的服务器向 vCenter Server 发送精心构造的请求，从而在服务器上写入 webshell，最终造成远程任意代码执行。
  * 受影响版本
    * `vmware:vcenter_server`7.0 U1c 之前的 7.0 版本
    * `vmware:vcenter_server`6.7 U3l 之前的 6.7 版本
    * `vmware:vcenter_server`6.5 U3n 之前的 6.5 版本
  * PoC
    * [https://github.com/NS-Sp4ce/CVE-2021-21972](https://github.com/NS-Sp4ce/CVE-2021-21972)
  * 参考链接
    * [http://noahblog.360.cn/vcenter-6-5-7-0-rce-lou-dong-fen-xi/](http://noahblog.360.cn/vcenter-6-5-7-0-rce-lou-dong-fen-xi/)
* CVE-2021-3156
  * 受影响的产品
    * Sudo 1.9.0 到 1.9.5p1 所有稳定版（默认配置）
    * Sudo 1.8.2 到 1.8.31p2 所有旧版本（默认配置）
  * 漏洞简介
    * 任何本地用户（包括普通用户和系统用户，sudoer和非sudoers）若成功利用该漏洞，可在无需密码的情况下获得root权限。
  * PoC
    * [https://github.com/worawit/CVE-2021-3156](https://github.com/worawit/CVE-2021-3156)
  * 参考链接
    * [https://blog.qualys.com/vulnerabilities-research/2021/01/26/cve-2021-3156-heap-based-buffer-overflow-in-sudo-baron-samedit](https://blog.qualys.com/vulnerabilities-research/2021/01/26/cve-2021-3156-heap-based-buffer-overflow-in-sudo-baron-samedit)


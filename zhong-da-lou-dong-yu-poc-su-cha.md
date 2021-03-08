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
* CVE-2021




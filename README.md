# S2-045
CVE-2017-5638 Exploit

![exploit](https://raw.githubusercontent.com/BearcatMao/S2-045/master/exploit.png)

# 修复方案

检测方式查看web目录下/WEB-INF/lib/目录下的struts-core.x.x.jar ，如果这个版本在Struts2.3.5 到 Struts2.3.31 以及 Struts2.5 到 Struts2.5.10之间则存在漏洞，

更新至Strusts2.3.32或者Strusts2.5.10.1，或使用第三方的防护设备进行防护。

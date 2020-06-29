---
name: Bug report
about: 反馈软件错误及异常
title: 无法显示Dashboard界面
labels: ''
assignees: ''

---

[//]: # (如不按模版填写，则issue将被直接关闭)

**信息**

[//]: # (如果符合，请将``[ ]``改为``[x]``)

- [x] 已经尝试更新到最新版本，问题依旧存在
- [ ] 软件从本仓库下载
- [ ] 软件下载后未修改任何安装目录中的文件

**系统**

[//]: # (平台及版本号)
操作系统名称:          Microsoft Windows 10 专业版
操作系统版本:          18362.900
   版本号  :           1903
   
**描述**

[//]: # (请具体并清楚地描述遇到的问题)
更新到最新版本后无法显示Dashboard界面

**复现**

[//]: # (请描述复现问题的步骤)
1. 更新版本后，进入'桌面'
2. 点击'clash for windows'快捷方式打开软件
3. 打开'状态栏'，右击'clash图标'
4. 点击'Dashboard'
5. 触发问题

**预期行为**

[//]: # (清晰地描述期望看到的行为)
打开Dashboard界面

**日志**

[//]: # (上传触发问题对应的日志文件)
time="2020-06-29T15:03:05+08:00" level=info msg="Start initial compatible provider Proxy"
time="2020-06-29T15:03:05+08:00" level=info msg="RESTful API listening at: 127.0.0.1:9090"
time="2020-06-29T15:03:05+08:00" level=info msg="Redir proxy listening at: :7892"
time="2020-06-29T15:03:05+08:00" level=warning msg="Failed to start Redir UDP Listener: UDP redir not supported on current platform"
time="2020-06-29T15:03:05+08:00" level=info msg="Mixed(http+socks5) proxy listening at: :7890"
time="2020-06-29T15:03:05+08:00" level=info msg="Start initial compatible provider πΉπΌ TW"
time="2020-06-29T15:03:05+08:00" level=info msg="Start initial compatible provider πΊπΈ US"
time="2020-06-29T15:03:05+08:00" level=info msg="Start initial compatible provider θ΄¦ε·δΏʽζ―"
time="2020-06-29T15:03:05+08:00" level=info msg="Start initial compatible provider δΈ­θ½¬"
time="2020-06-29T15:03:05+08:00" level=info msg="Start initial compatible provider Advertising"
time="2020-06-29T15:03:05+08:00" level=info msg="Start initial compatible provider Spotify"
time="2020-06-29T15:03:05+08:00" level=info msg="Start initial compatible provider πΉπ· TR"
time="2020-06-29T15:03:05+08:00" level=info msg="Start initial compatible provider πΈπ¬ SG"
time="2020-06-29T15:03:05+08:00" level=info msg="Start initial compatible provider π―π΅ JP"
time="2020-06-29T15:03:05+08:00" level=info msg="Start initial compatible provider Local"
time="2020-06-29T15:03:05+08:00" level=info msg="Start initial compatible provider Final"
time="2020-06-29T15:03:05+08:00" level=info msg="Start initial compatible provider πΉπ­ TH"
time="2020-06-29T15:03:05+08:00" level=info msg="Start initial compatible provider Low Latency"
time="2020-06-29T15:03:05+08:00" level=info msg="Start initial compatible provider ForeignMedia"
time="2020-06-29T15:03:05+08:00" level=info msg="Start initial compatible provider Hijacking"
time="2020-06-29T15:03:05+08:00" level=info msg="Start initial compatible provider Apple"
time="2020-06-29T15:03:05+08:00" level=info msg="Start initial compatible provider DomesticMedia"
time="2020-06-29T15:03:05+08:00" level=info msg="Start initial compatible provider Netflix"
time="2020-06-29T15:03:05+08:00" level=info msg="Start initial compatible provider Proxy"
time="2020-06-29T15:03:05+08:00" level=info msg="Start initial compatible provider π­π° HK"
time="2020-06-29T15:03:05+08:00" level=info msg="Start initial compatible provider π©π DE"
time="2020-06-29T15:03:05+08:00" level=info msg="Start initial compatible provider Download"
time="2020-06-29T15:03:05+08:00" level=info msg="Start initial compatible provider China"
time="2020-06-29T15:03:05+08:00" level=info msg="Start initial compatible provider BBC"
time="2020-06-29T15:03:06+08:00" level=info msg="Start initial compatible provider Low Latency"
time="2020-06-29T15:03:06+08:00" level=info msg="Start initial compatible provider Spotify"
time="2020-06-29T15:03:06+08:00" level=info msg="Start initial compatible provider Apple"
time="2020-06-29T15:03:06+08:00" level=info msg="Start initial compatible provider Netflix"
time="2020-06-29T15:03:06+08:00" level=info msg="Start initial compatible provider Final"
time="2020-06-29T15:03:06+08:00" level=info msg="Start initial compatible provider πΊπΈ US"
time="2020-06-29T15:03:06+08:00" level=info msg="Start initial compatible provider πΉπΌ TW"
time="2020-06-29T15:03:06+08:00" level=info msg="Start initial compatible provider π­π° HK"
time="2020-06-29T15:03:06+08:00" level=info msg="Start initial compatible provider Download"
time="2020-06-29T15:03:06+08:00" level=info msg="Start initial compatible provider ForeignMedia"
time="2020-06-29T15:03:06+08:00" level=info msg="Start initial compatible provider Proxy"
time="2020-06-29T15:03:06+08:00" level=info msg="Start initial compatible provider Local"
time="2020-06-29T15:03:06+08:00" level=info msg="Start initial compatible provider China"
time="2020-06-29T15:03:06+08:00" level=info msg="Start initial compatible provider πΉπ­ TH"
time="2020-06-29T15:03:06+08:00" level=info msg="Start initial compatible provider DomesticMedia"
time="2020-06-29T15:03:06+08:00" level=info msg="Start initial compatible provider BBC"
time="2020-06-29T15:03:06+08:00" level=info msg="Start initial compatible provider θ΄¦ε·δΏʽζ―"
time="2020-06-29T15:03:06+08:00" level=info msg="Start initial compatible provider πΉπ· TR"
time="2020-06-29T15:03:06+08:00" level=info msg="Start initial compatible provider π―π΅ JP"
time="2020-06-29T15:03:06+08:00" level=info msg="Start initial compatible provider π©π DE"
time="2020-06-29T15:03:06+08:00" level=info msg="Start initial compatible provider δΈ­θ½¬"
time="2020-06-29T15:03:06+08:00" level=info msg="Start initial compatible provider Hijacking"
time="2020-06-29T15:03:06+08:00" level=info msg="Start initial compatible provider Advertising"
time="2020-06-29T15:03:06+08:00" level=info msg="Start initial compatible provider πΈπ¬ SG"
time="2020-06-29T15:03:06+08:00" level=warning msg="dial DIRECT error: lookup raw.githubusercontent.com: getaddrinfow: The requested name is valid, but no data of the requested type was found."
time="2020-06-29T15:03:06+08:00" level=warning msg="dial DIRECT error: lookup raw.githubusercontent.com: getaddrinfow: The requested name is valid, but no data of the requested type was found."
time="2020-06-29T15:03:06+08:00" level=info msg="[TCP] 127.0.0.1:13787 --> api.github.com using DIRECT"

**截图**

[//]: # (如果可以，请提供对应问题的截图)

**其他说明**

[//]: # (其他补充内容)

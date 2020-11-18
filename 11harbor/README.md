# Harbor 简介

Harbor 是一个开源制品（artifact）仓库，可通过策略和基于角色的访问控制来保护制品（如容器镜像、Helm Chart等），扫描镜像并避免受安全漏洞的危害，并对镜像签名成为受信内容，帮助用户在 Kubernetes 和 Docker 等云原生平台之中持续和安全地管理制品。

Harbor 源于 2014 年 VMware中国研发中心云原生实验室的一个内部项目，旨在为容器的开发人员解决镜像管理的问题。随着 Kubernetes 和容器技术的流行，该项目于 2016 年开源，并于 [2018 年 7 月捐赠给 CNCF](http://mp.weixin.qq.com/s?__biz=MzAwNzUyNzI5Mw==&mid=2730790774&idx=2&sn=6ff9eb88b8179fe0599f0cd0c9fb0e85&chksm=bc4ce1648b3b6872ce6301e638010c0bd07dc0a50e4b5460273053301f95d8fa94655f159523&scene=21#wechat_redirect)，在同年 11 月被正式接受为孵化项目。

2020年5月， [Harbor 2.0](http://mp.weixin.qq.com/s?__biz=MzAwNzUyNzI5Mw==&mid=2730791329&idx=2&sn=215e5d7ea817bd662a6fc91c5c0fd99f&chksm=bc4cffb38b3b76a5effcd89b04453fb041ddcd3ca7f560671049795450a35f91a03f48b7f20a&scene=21#wechat_redirect) 正式发布，增加了对 OCI 制品的支持，能够存储大量云原生制品，例如容器镜像、Helm Chart、CNAB、OPA 和 Singularity 等等。开发人员可依照 OCI 规范，通过 OCI 索引和 OCI 制品功能开拓更广泛的应用场景，包括策略、远程复制和基于角色的访问控制等。**2020 年 6 月 23 日** ，Harbor 成为第 11 个毕业的项目。这是首个中国原创项目自CNCF毕业。

## 特性

- **云原生镜像库**(Cloud native registry)
- **基于角色的访问控制**(Role Based Access Control)
- **基于策略的镜像复制**(Policy based image replication)
- **漏洞扫描**(Vulnerability Scanning)
- **LDAP/AD集成**(LDAP/AD support)
- **OIDC 支持**
- **镜像删除和垃圾清理**(Image deletion & garbage collection)
- **签名功能**
- **友好管理界面**(Graphical user portal)
- **审计**(Auditing)
- **RESTful API**
- **部署简单**(Easy deployment)


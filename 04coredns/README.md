# CoreDNS 简介

2016 年 3 月，Google 工程师 Miek Gieben 启动 CoreDNS 项目，它的开发初衷是作为 Caddy（一个用 Golang 写的高效 Web Server）的服务器插件。2017 年，CoreDNS 加入 CNCF Sandbox，并于 2018 年 2 月成为孵化项目。2019年1月末，云原生计算基金会（CNCF）宣布域名系统（DNS）服务器——CoreDNS 毕业了，这也是 2019 年第一个成功毕业的孵化项目。

CoreDNS是一个快速、灵活且现代的DNS服务器，可在云原生部署中提供服务发现。由于它提供了与Kubernetes向后兼容但可扩展的集成，从Kubernetes 1.13版本开始，正式推荐CoreDNS作为所有部署的默认DNS。该服务器还可用于AWS的混合云环境，使用AWS Route53和etcd集成，亦计划尽快添加Google Cloud DNS支持。

“CoreDNS的灵活、基于插件的架构，已被证明是DNS服务器的强大设计。易于集成和扩展，使得CoreDNS在实施各种DNS服务和用例变得至关重，从Kubernetes服务发，到基于政策的DNS和广告拦截，”Google云计算高级软件工程师和CoreDNS高级维护者，John Belamaric表示。“CNCF对该项目的支持对CoreDNS的成功至关重要，我们很高兴能够毕业，并继续发展我们多元化的社区。”


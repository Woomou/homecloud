# homecloud
Home Integration of Lots of Service.
## 项目初衷
将很多有意思的东西集成到一块，实现多种服务的私有化：
- 同步盘 TODO
- 内外网穿透的服务
    - 域名配置
        - Cloudflare
        - BIND
    - 域名解析
        - DDNS-go
    - IP获取
        - Zerotier 虚拟IPv6网卡
    - 端口转发
        - Nginx-Proxy-Manager
    - 典型实践
- 开发及部署服务
    - 镜像注册
        - Harbor
    - 一键部署
        - Actions
    - 自动测试
- 微服务集成
<p align="center">
  <img src="./portone.png" width="128" alt="Port One">
</p>

<h1 align="center">Port One</h1>

<p align="center">单域名、单端口，统一管理多个 Web 服务</p>

<p align="center">
  <a href="https://github.com/IMGZCQ/Port-One/releases">下载</a>
  ·
  <a href="./使用手册.md">使用手册</a>
  ·
  <a href="https://github.com/IMGZCQ/Port-One/issues">问题反馈</a>
</p>

Port One 是一个面向个人、家庭服务器和小型团队的单端口 Web 管理面板。它可以把多个后端服务集中到同一个域名和端口下，并集成反向代理、终端、文件、分享、静态站点和组网穿透等常用运维功能。

## 功能

- **反向代理** · 单域名单端口反代多个后端，各后端原生跑在根路径 `/`。
- **本地终端** · 浏览器里的多会话终端，后台保活、随时重连。
- **文件管理** · 在线浏览、编辑、上传下载与文件操作。
- **外链分享** · 为文件或目录生成带密码/有效期的分享链接。
- **静态站点** · 把任意目录一键发布为静态网站。
- **组网穿透** · 简易配置 FRPC 和 EasyTier 快速组网，支持参数随启。

## 快速开始

### fnOS

1. 从 [Releases](https://github.com/IMGZCQ/Port-One/releases) 下载最新的 `port_one_<版本>.fpk`。
2. 在 fnOS 应用中心手动安装。
3. 默认端口为 `9788`，安装过程中可以修改。
4. 打开 `http://<服务器地址>:9788/@admin`。
5. 首次访问时设置管理密码。

后端服务、组网穿透、文件管理、外链分享和静态站点的详细操作，请查看[使用手册](./使用手册.md)。

管理入口和本地终端拥有较高权限，组网穿透配置也可能包含 Token、密码和服务器信息。请勿公开分享相关配置，并建议通过 HTTPS 或访问控制保护管理入口。

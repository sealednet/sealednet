<p align="center">
  <a href="https://sealednet.com">
    <picture>
      <source media="(prefers-color-scheme: dark)" srcset=".github/assets/lockup-dark.svg">
      <img alt="SealedNet" src=".github/assets/lockup.svg" height="64">
    </picture>
  </a>
</p>

<p align="center">
  <a href="https://sealednet.com">官网</a> ·
  <a href="https://sealednet.com/docs/quickstart">快速开始</a> ·
  <a href="https://sealednet.com/docs/capabilities">产品能力</a> ·
  <a href="https://sealednet.com/site/pricing">定价</a> ·
  <a href="README.en.md">English</a>
</p>

# SealedNet

给每个团队和客户一个独立的上网环境：浏览器、桌面、终端或应用。每个环境绑定一条你自己的线路，时区和语言跟着线路的出口走；线路断了，环境就断网，不会回落到机器自己的网络。

## 怎么工作

- **面板由 SealedNet 托管**：在 [sealednet.com](https://sealednet.com) 注册即用，管理机器、线路、环境和团队。
- **环境跑在你自己的机器上**：Windows 电脑运行一行命令就能装好，Linux 服务器（x86_64 / arm64）也可以。不需要公网 IP，不用开端口。
- **流量不经过 SealedNet**：环境的上网流量从你的机器直接进你的线路。

## 主要能力

- **环境**：云浏览器、Linux 桌面、终端、安卓开发环境等模板；应用目录里的 Docker 应用；也可以装你自己的镜像。每个环境有独立的数据卷，更新只换镜像、数据不动。
- **打开方式**：在浏览器里打开桌面（优先 WebRTC 直连，不通时走中继，手机也能用）、网页终端、应用自带的网页端口、TCP 端口映射。不用装远程软件。
- **断网保护**：环境在专属网络里，所有联网流量（包括 UDP）只能走绑定的线路；线路不通时环境没有网络。
- **出口检测**：出口 IP、国家、DNS、UDP 与 WebRTC、IPv6 等定时体检；线路质量等级、检测历史和告警。
- **团队**：所有者、管理员、成员、只读成员四种角色。

## 不是什么

- **不卖线路**：线路是你自己的 SOCKS5 或 HTTP 代理。
- **不是 VPN 或加速器**：只管理你机器上的环境，不改电脑本身的网络。
- **不提供服务器**：环境跑在你的 Windows 电脑或你自己的 Linux 机器上。

## 上手

1. 在 [sealednet.com](https://sealednet.com) 注册并验证邮箱。
2. 在面板里添加机器，复制安装命令到你的 Windows 电脑或 Linux 服务器上运行。
3. 添加线路并检测。
4. 安装环境，在浏览器里打开。

完整步骤见 [快速开始](https://sealednet.com/docs/quickstart)，所有文档见 [文档中心](https://sealednet.com/docs/)。

## 关于这个仓库

这是 SealedNet 在 GitHub 上的官方主页，不包含产品源码。问题和建议欢迎提 [Issue](https://github.com/sealednet/sealednet/issues)，也可以通过 [联系我们](https://sealednet.com/docs/support) 找到客服。

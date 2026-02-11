---
# 官方文档相关配置：https://vitepress.dev/reference/default-theme-layout
layout: home
home: true

# 官方文档相关配置：https://vitepress.dev/reference/default-theme-home-page
lang: zh-CN
title: KnopiaPE
titleTemplate: 官方帮助文档
editLink: true
lastUpdated: true

# 指定要为当前页面注入的额外头标签。将附加在站点级配置注入的头标签之后
head:
  - - meta
    - name: description
      content: KnopiaPE、WinPE
  - - meta
    - name: keywords
      content: KnopiaPE、WinPE

hero:
  name: "KnopiaPE"
  text: "一个纯净、强大、优雅的PE工具箱"
  image: # text 和 tagline 区域旁的图片
    src: /logo.svg
    alt: "FirPE"
  # 按钮相关
  actions:
    - theme: brand
      text: "🏠首页"
      link: "/"
    - theme: alt
      text: "🚀快速开始"
      link: "/guide/quickstart/"

# 按钮下方的描述
features:
  - icon: ⚙️
    title: "双内核适配"
    details: "集成 Win11PE 与 Win03PE 双内核，全面覆盖新旧硬件平台，支持 UEFI/Legacy 双启动模式。"
  - icon: 🧰
    title: "系统安装与维护"
    details: "支持系统安装、备份、恢复和维护等功能，能够显著提高系统安装效率。"
  - icon: 💾
    title: "全能启动盘制作"
    details: "支持双分区/三分区模式制作，智能识别U盘状态，失败不自动还原空间，兼容新旧主板启动。"
  - icon: 🌐
    title: "全场景网络支持"
    details: "支持有线/无线网络，集成大量网卡驱动，支持 SMB 共享连接、IP 固定配置等高级功能。"
  - icon: 🛡️
    title: "安全纯净保障"
    details: "零广告零捆绑，通过 MPL 2.0 协议开源验证，工具链规避主流杀软误报。"
---

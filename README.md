<!-- AUTO_UPDATE_TIME -->
# v2ray节点订阅 每日更新 更新时间：2025-10-15 11:31:01
所有v2ray免费节点都爬取自网络，请勿用于非法用途 。

|  客户端  | Android  | Windows  | iOS  |
|  ----  | ----   | ----  |----  |
| v2ray  | [v2rayNG](https://github.com/v2fly/v2ray-core/releases/download/v5.32.0/v2ray-android-arm64-v8a.zip) | [v2rayN](https://github.com/2dust/v2rayN/releases/download/7.12.3/v2rayN-windows-64-desktop.zip) | [OneClick]() |
## v2rayN使用教程：[点击查看]()

## 节点导入方法
- 1. 在订阅配置页面，增加订阅下方免费节点订阅地址，更新订阅获取节点
- 2. 在下方节点分享 → 右边点击复制 → 打开V2Ray软件 → 点击左上角服务器 → 从剪贴板导入分享链接，即可一键导入所有v2ray节点
     
# v2ray免费节点订阅
### [订阅地址：]()
`https://raw.githubusercontent.com/WLget/V2Ray_configs_64/refs/heads/master/ConfigSub_list.txt`

# 自己搭建节点教程
### 节点搭建使用CF的方式部署
- CF网站：https://dash.cloudflare.com/
- 部署项目地址：https://github.com/WLget/wk-Auto-update

## 部署步骤

- 创建项目：在cloudflare 后台- 左侧点击【pages】—【创建项目】
- 登录 Cloudflare 后台 → 左侧点击【Pages】→ 【创建项目】 选择 连接到 GitHub： 选择你的 Fork 仓库 允许 Cloudflare Pages 读取你的 GitHub 仓库权限 项目基本配置： 项目名字自己取，比如 cf-auto-update 分支选择 main

### 配置环境变量（Varidbles）
- 在 Pages 项目设置里：
- 打开 【设置 Settings】→ 【环境变量 Environment Variables】 -添加这些变量：
  
|  变量名称（注意： 变量名字全大写！）  | 释义 |
|  ----  | ----   |
|  UUID  | 自己需要生成一个UUID，可以去这个网站生成https://1024tools.com/uuid  |
|  TR_PASS  | 自己设一个密码  |
|  FALLBACK  | 设置成example.com  |
### 配置KV 存储绑定
- Pages Functions 也可以使用 KV， -需要绑定 KV 存储桶。
- 步骤：
- 1. Cloudflare 后台左侧【Workers & KV】→ 【KV 存储】
  2. 创建一个新的命名空间（比如叫 test）
  3. 回到 Pages 项目的【Settings → KV Bindings】
  4. 添加绑定： -Binding Name Namespace -kv 你刚才创建的 test ✅ Binding Name 必须是 kv 小写，保持和代码对应！

### 访问面板
- 部署完成后：
- 访问你的 Pages 地址，比如： https://your-project-name.pages.dev/panel 第一次访问，会让你设置后台管理密码 进入后台后，可以自由开关协议（Trojan、VLess 等），生成订阅链接

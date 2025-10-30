<!-- AUTO_UPDATE_TIME -->
# v2ray节点订阅 每日更新 更新时间：2025-10-30 17:11:59
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

# Clash免费节点订阅
### [订阅地址：]() 下列订阅地址已测试Clash/Clash Verge/NekoBox软件均可使用，其他暂未测试！
- `https://subconverters.com/sub?target=clash&url=http%3A%2F%2F103.143.238.196%3A20211%2F&insert=false&config=https%3A%2F%2Fraw.githubusercontent.com%2FACL4SSR%2FACL4SSR%2Fmaster%2FClash%2Fconfig%2FACL4SSR_Online_Full_NoAuto.ini&emoji=true&list=false&xudp=false&udp=false&tfo=false&expand=true&scv=false&fdn=false&new_name=true`
- `http://103.143.238.196:20211/`

- ### 客户端下载
  
|  客户端  | Clash for Windows  | Clash Verge rev  | NekoBox for Android  |
|  ----  | ----   | ----  |----  |
| more  | [Clash](https://github.com/Z-Siqi/Clash-for-Windows_Chinese/releases/tag/0.20.39.3) |[Verge](https://github.com/clash-verge-rev/clash-verge-rev/releases/tag/v2.4.2) | [NekoBox](https://github.com/MatsuriDayo/NekoBoxForAndroid/releases/tag/1.4.0) |

# 自己搭建节点教程
### 节点搭建使用CF的方式部署
- CF网站：https://dash.cloudflare.com/
- 部署项目地址：https://github.com/bia-pain-bache/BPB-Worker-Panel/tree/v3.4.3

## 部署步骤

- 创建项目：在cloudflare 后台- 左侧点击【pages】—【创建项目】
- 登录 Cloudflare 后台 → 左侧点击【Pages】→ 【创建项目】 选择 从 Hello World! 开始 创建应用 --> 编辑代码 --> 这里需要上面项目中右侧“Releases” 点开 --> 下载“worker.js
  到本地，打开（需要编程软件才能打开）--> 复制里面的代码保存

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
  5. 一切都完成之后，必须要绑定域名，没有域名的话注册一个域名，要不然无法访问配置面板的地址！

### 访问面板
- 部署完成后：
- 访问你的 Pages 地址，比如： https://your-URL/panel 第一次访问，会让你设置后台管理密码 进入后台后，可以自由开关协议（Trojan、VLess 等），生成订阅链接
















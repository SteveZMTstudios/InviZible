# InviZible Pro

![GitHub release (latest by date)](https://img.shields.io/github/v/release/gedsh/invizible?style=plastic)
![GitHub Releases](https://img.shields.io/github/downloads/gedsh/invizible/latest/total?color=blue&style=plastic)
[![翻译状态](https://hosted.weblate.org/widgets/invizible/-/invizible/svg-badge.svg)](https://hosted.weblate.org/engage/invizible/?utm_source=widget)

### [Google Play 上的稳定版](https://play.google.com/store/apps/details?id=pan.alexander.tordnscrypt.gp)

### [在 Github 上下载](https://github.com/Gedsh/InviZible/releases/latest)

### [IzzyOnDroid F-Droid beta 版本](https://apt.izzysoft.de/fdroid/index/apk/pan.alexander.tordnscrypt)

### [F-Droid 稳定版](https://f-droid.org/packages/pan.alexander.tordnscrypt.stable/)

## 用于在线隐私和安全的 Android 应用程序

*保护隐私，防止跟踪，并提供对受限和隐藏的在线内容的访问*
**InviZible Pro** 结合了**Tor**、**DNSCrypt**和**Purple I2P**的优势，为在线隐私、安全和匿名性提供了全面的解决方案。
(译者注：尽管本程序被叫做**InviZible Pro**,但程序本体无需支付任何费用。)

### Tor
* 隐藏用户IP和位置
* 抵御流量分析和审查
* 保护在线活动免受监视
* 通过多台服务器路由流量
* 提供对“.onion”网站的访问
* 开源

### DNSCrypt
* 使用加密保护 DNS 流量
* 使用加密密钥验证 DNS 服务器合法性
* 抵御基于 DNS 的攻击（如欺骗）
* 防范窃听和 DNS 查询记录
* 可以屏蔽广告 *
* 可以防范危险和恶意网站 *
* 可以屏蔽“成人”网站 *
* 开源

**取决于所选的 dnscrypt 服务器*
**（Google Play 版本中不可用）**

### Purple I2P
* 提供匿名通信网络
* 隐藏用户身份和活动
* 防止监视
* 确保安全数据传输
* 分布式自组织网络
* 提供对“i2p”网站 (eepsites) 的访问
* 开源

要开始使用 **InviZible Pro**，您只需要一部 Android 手机。
只需运行所有三个模块，即可享受安全舒适的互联网冲浪。但是，
如果您想完全控制应用程序和互联网连接 - 没问题！
可以访问大量简单和专业的设置。
您可以灵活配置 **InviZible Pro** 本身及其模块 - **DNSCrypt**、
**Tor** 和 **Purple I2P**，以满足大多数非标准要求。

**InviZible Pro** 是一款一体化应用程序。安装后，您可以删除所有 VPN 应用程序和广告拦截器。
在大多数情况下，**InviZible Pro** 比免费 VPN 运行得更好、更稳定、速度更快。
它不包含任何广告、过度软件，也不会监视用户。

### 为什么 InviZible Pro 比其他类似应用程序更好：
* 隐私保护：保护您的在线活动。
* 匿名浏览：隐藏您的身份。
* 安全 DNS 加密：保护您的 DNS 查询。
* 匿名网络集成：利用 Tor、DNSCrypt 和 Purple I2P。
* 防火墙：防止未经授权的访问。
* 访问受限内容：解除对被阻止网站的阻止。
* 反跟踪措施：防止跟踪您的在线行为。
* 隐藏网络访问：连接到“洋葱”和“i2p”网站。
* 开源：透明且由社区驱动。
* 用户友好设计：简单直观的界面。

## 兼容性

**InviZible Pro** 既可用于 root 设备，也可用于非 root 设备。

请访问 [wiki](https://github.com/Gedsh/InviZible/wiki) 了解如何使用它。

根据 root 方法和设备具体情况，应用程序可能与某些 Android 手机不兼容。

## 支持

对于问题、功能请求和错误报告，您可以使用 GitHub。

**官方网站：[invizible.net](https://invizible.net)**

### 国际：

Telegram 频道：[InviZiblePro](https://t.me/InviZiblePro)

Telegram 群组: [InviZiblePro_Group](https://t.me/InviZiblePro_Group)

Matrix 群组: [Matrix](https://matrix.to/#/#invizible-pro-en:matrix.org)

### For Russian-speaking users:

Telegram channel: [InviZiblePro](https://t.me/InviZibleProRus)

Telegram group: [InviZiblePro_Group](https://t.me/InviZibleProRus_Group)

Matrix group: [Matrix](https://matrix.to/#/#invizible-pro-ru:matrix.org)

仅最新版本的 **InviZible Pro** 受支持。

与 **InviZible Pro** 无直接关系的内容不受支持。

自行构建和开发内容不受支持。

## 贡献

#### 构建
要克隆项目，请使用以下命令：
```bash
git clone --recursive https://github.com/Gedsh/InviZible
```

要构建 **InviZible Pro**，请使用 **Android Studio**。

如果您看到类似以下内容：
_Illegal character in opaque part at index 2: C:\KStore\keystore.properties_
请注释项目根目录中的 settings.gradle 文件的行，如下所示：

```bash
include ':tordnscrypt', ':filepicker'
project(':filepicker').projectDir = new File('android-filepicker/filepicker')
//Please comment line below if you are not the project owner
//project(':tordnscrypt').buildFileName = 'owner.gradle'
```

我们希望您能够自己解决构建问题，因此不支持构建。
如果您无法自行构建，[此处](https://github.com/Gedsh/InviZible/releases/latest) 提供了 **InviZible Pro** 的预构建版本。

#### 翻译

[在 POEditor 上翻译 InviZible](https://poeditor.com/join/project/h6ulNL9gEd)。

[在 Hosted Weblate 上翻译 InviZible](https://hosted.weblate.org/engage/invizible/)。

[![翻译状态](https://hosted.weblate.org/widgets/invizible/-/multi-auto.svg)](https://hosted.weblate.org/engage/invizible/?utm_source=widget)

## 署名

InviZible Pro 使用：

* [DNSCrypt](https://github.com/jedisct1/dnscrypt-proxy)
* [Tor](https://www.torproject.org/)
* [Purple I2P](https://github.com/PurpleI2P/i2pd)
* [Chainfire/libsuperuser](https://github.com/Chainfire/libsuperuser)
* [jaredrummler/AndroidShell](https://github.com/jaredrummler/AndroidShell)
* [NetGuard](https://github.com/M66B/NetGuard)
* [Angads25/android-filepicker](https://github.com/Angads25/android-filepicker)
* [meefik/busybox](https://github.com/meefik/busybox)

本产品独立于 **Tor®**、**DNSCrypt**、  **Purple I2P** 软件 
并且不对这些项目的质量、适用性或其他任何方面提供任何保证。

 ## 捐款 
 **Patreon**：https://www.patreon.com/inviziblepro 
 
 **BTC**：1GfJwiHG6xKCQCpHeW6fELzFfgsvcSxVUR 
 
 **LTC**：MUSAXkcAvnN1Ytauzeo9bwjVjarUdDHGgk 
 
 **BCH**：qzl4w4ahh7na2z23056qawwdyuclkgty5gc4q8 tw88 
 
 **USDT**：0xdA1Dd53FE6501140E3Dcd5134323dfccF20aD536 
 
 **XLM**：GBID6I3VYR4NIFLZWI3MEQH3M2H72COC3HQDI5WMYYQGAC3TE55TSKAX 
 
 **XMR**  82WFzofvGUdY52w9zCfrZWaHVqEDcJH7y1FujzvXdGPeU9UpuFNeCvtCKhtpC6pZmMYuCNgFjcw5mHAgEJQ4RTwV9XRhobX

请注意，XMR 地址已更改。旧地址不再有效。

## 许可证

[GNU 通用公共许可证版本 3](https://www.gnu.org/licenses/gpl-3.0.txt)

版权所有 (c) 2019-2024 Garmatin Oleksandr invizible.soft@gmail.com

保留所有权利

此文件是 **InviZible Pro** 的一部分。

 **InviZible Pro** 是免费软件：您可以根据自由软件基金会发布的 GNU 通用公共许可证条款重新分发和/或修改它，无论是许可证第 3 版还是（由您自行决定）任何后续版本。

**InviZible Pro** 的分发旨在希望它有用，但不提供任何担保；甚至没有适销性或特定用途适用性的默示担保。有关更多详细信息，请参阅 GNU 通用公共许可证。

您应该已收到一份 GNU 通用公共许可证以及 **InviZible Pro**。如果没有，请参阅 [http://www.gnu.org/licenses/](https://www.gnu.org/licenses/)

由 [@SteveZMTstudios](https://github.com/stevezmtstudios) 翻译

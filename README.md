![Artboard][NuggetLogo]

# GoldenNugget (Mobile)
释放你设备的全部潜力，现已支持 iOS 27！

用动态壁纸自定义你的设备、禁用烦人的守护进程，还有更多功能！

如果你使用的是 Windows 或 Linux，请确保已安装[所需环境](#requirements)。

> [!NOTE]
> 使用本项目之前请先备份你的数据！GoldenNugget 可能会引发不可预见的问题，安全第一总没错。对于你的设备遭受的任何损坏，我们概不负责。

> [!WARNING]
>  **对于任何数据丢失或陷入重启循环，我概不负责；出了问题就是你自己的责任**
## Discord 服务器
需要支持？加入我们的 [Discord 服务器][server]。

## 功能
<details>
<summary>iOS 26.2 - 27.0+</summary>

- PosterBoard：动态壁纸与描述文件。
  - 社区壁纸可以在[这里][WallpapersWebsite]或[这里][caplayground]找到
  - 通过 batter 文件自定义社区制作的壁纸
  - 可以安装 MercuryPoster 中针对特定设备的壁纸
  - tendies 和 batter 文件的结构文档见 [documentation.md](documentation.md)
- 模板：自定义操作与文件编辑
  - batter 文件的结构文档见 [documentation.md](documentation.md)
- Springboard 选项
  - 设置锁屏脚注
  - 设置锁屏闲置自动锁定时间
  - 禁用注销后锁定
  - 充电时禁用屏幕变暗
  - 禁用低电量提醒
  - 在锁屏上隐藏交流电源提示
  - 在锁屏上显示监管文字
  - 在截图中显示灵动岛
  - 为台前调度启用 AirPlay 支持
  - 在锁屏上显示红/绿认证线（效果见[这个 issue](https://github.com/leminlimez/Nugget/issues/656)）
  - 在 iPad 上禁用浮动标签栏
- 内部选项
  - 在状态栏显示构建版本
  - 强制从右到左布局
  - 在主屏幕显示隐藏图标
  - 强制 Metal HUD 调试
  - iMessage 诊断
  - IDS 诊断
  - VC 诊断
  - App Store 调试手势
  - 备忘录 App 调试模式
  - 显示带调试信息的触摸点
  - 隐藏注销图标
  - 粘贴时播放声音
  - 系统粘贴时显示通知
- 禁用液态玻璃 (iOS 26.0+)：
  - 忽略液态玻璃 App 构建检查 (iOS 26.0+)
  - 强制 Solarium 回退 (iOS 26.0+，在 iOS 27 上已失效)
- 禁用守护进程：
  - OTAd
  - UsageTrackingAgent
  - Game Center
  - 屏幕使用时间 Agent
  - 日志、转储和崩溃报告
  - ATWAKEUP
  - Tipsd
  - VPN
  - 中国无线局域网服务
  - HealthKit
  - AirPrint
  - 辅助触控
  - iCloud
  - 互联网共享（即个人热点）
  - PassBook
  - Spotlight
</details>

## 贡献者 

<div align="center">

**感谢每一位为项目做出贡献的人！** 🎉

<a href="https://github.com/goldennugget-team/goldennugget-mobile/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=goldennugget-team/goldennugget-mobile" />
</a>

想让你的名字出现在这里？来提交 [Pull Request](https://github.com/GoldenNugget-Team/GoldenNugget-mobile/pulls)！

</div>

## Star 历史

<a href="https://www.star-history.com/?type=date&repos=GoldenNugget-mobile%2FGoldenNugget-mobile">
 <picture>
   <source media="(prefers-color-scheme: dark)" srcset="https://api.star-history.com/chart?repos=GoldenNugget-Team/GoldenNugget-mobile&type=date&theme=dark&legend=top-left&sealed_token=3Suw7Y0hFqwuBPijtmeM2A7pzK2ZCvEPoousYMJzOVFnPza-Aq5SzgNnEcgveIpQsBLEOL2QRtxwZbmaxn_S_3Lf9l0jINrMfRWkjFWGo3dVYCrFRpN6dA" />
   <source media="(prefers-color-scheme: light)" srcset="https://api.star-history.com/chart?repos=GoldenNugget-Team/GoldenNugget-mobile&type=date&legend=top-left&sealed_token=3Suw7Y0hFqwuBPijtmeM2A7pzK2ZCvEPoousYMJzOVFnPza-Aq5SzgNnEcgveIpQsBLEOL2QRtxwZbmaxn_S_3Lf9l0jINrMfRWkjFWGo3dVYCrFRpN6dA" />
   <img alt="Star History Chart" src="https://api.star-history.com/chart?repos=GoldenNugget-Team/GoldenNugget-mobile&type=date&legend=top-left&sealed_token=3Suw7Y0hFqwuBPijtmeM2A7pzK2ZCvEPoousYMJzOVFnPza-Aq5SzgNnEcgveIpQsBLEOL2QRtxwZbmaxn_S_3Lf9l0jINrMfRWkjFWGo3dVYCrFRpN6dA" />
 </picture>
</a>

<div align="center">
<br>如果你觉得这是个不错的项目，可以给这个仓库点个 star。</br>
</div>

> [!NOTE]
> ## Mobilegestalt
> 连问都不要问我。它永远不会再被实现了。 

## 构建所需环境：
Xcode 26+，或带有 iOS 26+ SDK 的 xtool\
Rust (minimuxer, idevice, NeoSpring and airlift)\
Swift 6+（更旧版本未测试，也许能用）
macOS 15.6 Sequoia+ 或 Ubuntu 22.04+

# 贡献与 fork。
见 [CONTRIBUTING.md](https://github.com/GoldenNugget-Team/GoldenNugget-mobile/blob/main/CONTRIBUTING.md)，想 fork 的话？见 [FORKING.md](https://github.com/GoldenNugget-Team/GoldenNugget-mobile/blob/main/FORKING.md)

## HotLoad 与更新

HotLoad 会缓存移动端安全规则以供离线使用。设置中包含它的总开关、
手动刷新规则和检查更新。可用的移动端版本会显示在主页和
设置中，附带发行说明和 IPA 链接；用你的侧载工具安装 IPA 即可。
见[规则格式与行为](docs/hotload-and-updates.md)。

## 致谢
- [awesomenull] 主开发者
- [Wind0ws11Aero] 在开发上帮了很多忙。
- [kik4311](https://github.com/kik4311) 共同开发者。
- [@mak5er](https://github.com/mak5er)：AirCard 开发者。
- [NeoSpring](https://github.com/rooootdev/neospring)：Swift 实现由 **[@skadz108](https://github.com/skadz108)** 和 **[@rooootdev](https://github.com/rooootdev)** 完成，**[@neonmodder123](https://github.com/neonmodder123)** 提供 WebKit GPU 进程注销技术。
- [LeminLimez] Nugget 的创作者。
- [0xjonhnnydev] [AirLift] 的作者
- [iTechExpert][iTechExpertTwitter] 提供多项 Springboard/内部选项
- [Mikasa-san][Mikasa-sanGitHub] [Quiet Daemon][QuietDaemonGitHub] 的作者
- [MiniVoidyy](https://github.com/MiniVoidyy) 提供额外的系统与分析守护进程列表。
- [Snoolie](https://github.com/0xilis) 提供 AAR 处理。
- [mattisklein](https://github.com/mattisklein) 提供来自 Project Linwood 的 Siri AI 资格归档。
- [Prognosticate-X](https://github.com/Prognosticate-X/) 提供 [iOS 27 状态栏研究](https://github.com/Prognosticate-X/ios27-carrier-lockscreen-research)。

[caplayground]: https://caplayground.vercel.app/wallpapers
[i18n]: https://github.com/awesomenull-dev/gNugget-i18n
[NuggetLogo]: https://github.com/GoldenNugget-Team/GoldenNugget-mobile/blob/main/layout/Applications/GoldenNuggetMobile.app/Logo%401x.png
[LeminLimez]: https://github.com/leminlimez
[CowabungaLite]: https://github.com/leminlimez/CowabungaLite
[WallpapersWebsite]: https://cowabun.ga/wallpapers
[AppleDevices]: https://apps.microsoft.com/detail/9np83lwlpz9k
[iTunes]: https://support.apple.com/en-us/106372
[usbmuxdGitHub]: https://github.com/libimobiledevice/usbmuxd
[libimobiledeviceGitHub]: https://github.com/libimobiledevice/libimobiledevice
[ShortcutsApp]: https://apps.apple.com/us/app/shortcuts/id915249334
[MobilegestaltShortcut]: https://www.icloud.com/shortcuts/66bd3c822a0145b98d46cd1c9077e6e5
[ReadMoreGist]: https://gist.github.com/leminlimez/c602c067349140fe979410ef69d39c28
[Wind0ws11Aero]: https://github.com/Wind0ws11Aero
[POEditorJoin]: https://poeditor.com/join/project/UTqpVSE2UD
[JJTechGitHub]: https://github.com/JJTech0130
[TrollStoreGitHub]: https://github.com/JJTech0130/TrollRestore
[PosterRestoreDiscord]: https://discord.gg/gWtzTVhMvh
[dootskyreX]: https://x.com/dootskyre
[MiddoX]: https://x.com/MWRevamped
[dularkGitHub]: https://github.com/dularkian
[SerStarsX]: https://x.com/SerStars_lol
[disfordottieX]: https://x.com/disfordottie
[Mikasa-sanGitHub]: https://github.com/Mikasa-san
[QuietDaemonGitHub]: https://github.com/Mikasa-san/QuietDaemon
[sneakyf1shyGitHub]: https://github.com/f1shy-dev
[lrdsnowGitHub]: https://github.com/Lrdsnow
[EUEnablerGitHub]: https://github.com/Lrdsnow/EUEnabler
[pymobiledevice3GitHub]: https://github.com/doronz88/pymobiledevice3
[PySide6Doc]: https://doc.qt.io/qtforpython-6/
[python-aar-stuffGitHub]: https://github.com/0xilis/python-aar-stuff
[AIEligibilityGist]: https://gist.github.com/f1shy-dev/23b4a78dc283edd30ae2b2e6429129b5
[bl_sbxGitHub]: https://github.com/khanhduytran0/bl_sbx/tree/main
[DuyGitHub]: https://github.com/khanhduytran0
[HuyTwitter]: https://x.com/Little_34306
[iTechExpertTwitter]: https://twitter.com/iTechExpert21
[server]: https://discord.gg/Rm6r4zeE3y
[0xjonhnnydev]: https://github.com/0xjohnnydev
[awesomenull]: https://github.com/awesomenull-dev
[AirLift]: https://github.com/0xjohnnydev/airlift

## 与上游的区别（汉化说明）

本仓库是 **GoldenNugget** 的 fork（原项目：[GoldenNugget-Team/GoldenNugget-mobile](https://github.com/GoldenNugget-Team/GoldenNugget-mobile)，桌面版：[awesomenull-dev/GoldenNugget](https://github.com/awesomenull-dev/GoldenNugget)），于 2026-11-07 加入了完整的简体中文 (zh-Hans) 汉化：

- `Localizable.xcstrings` / `InfoPlist.xcstrings`：界面文案的 zh-Hans 翻译共 583 条（上游原有 527 条，另补齐上游目录遗漏的 56 条）。
- 调整与守护进程目录（`TweakCatalog.swift`、`TweakCatalogDaemons.swift`）：标题、说明、警告和分区名称均已原地翻译。
- 目录之外的用户可见文案已全量汉化：各页状态与提示、预设与模板导入导出信息、全部错误说明（含传输失败的详细解释）、配对与隧道状态等均已原地翻译；核查标准是除运行日志与诊断读数外不留英文。
- 构建配置：`knownRegions`（project.yml）和 xtool 资源列表（xtool.yml）中加入 `zh-Hans`。

功能没有任何改动。所有致谢与 GPLv3 许可证均按上游保留。

**翻译说明：本仓库的简体中文翻译（包括应用内文案与本 README）由 AI 完成，发行版的更新日志亦由 AI 翻译。如发现译文有误，欢迎提出指正。**

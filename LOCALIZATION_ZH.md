# 简体中文汉化说明

本仓库是 GoldenNugget-mobile 的简体中文（zh-Hans）全量汉化 fork，汉化于 2026-11-07。

## 汉化范围

- 界面文案目录 `Localizable.xcstrings` / `InfoPlist.xcstrings`：583 条全部译为简体中文（上游原有 527 条 + 补齐上游目录遗漏的 56 条）
- 目录之外的用户可见文案（状态、提示、错误说明等）已全量原地翻译；仅运行日志与诊断读数保留英文
- 调整页目录（`TweakCatalog.swift`）：258 条调整的标题、说明、警告原文替换为中文
- 守护进程页（`TweakCatalogDaemons.swift`）：53 组的标题与说明原文替换为中文
- 各页面状态消息 27 条原文替换为中文
- 分区标题（液态玻璃 / 内部选项 / 要禁用的守护进程等）原文替换为中文

内部标识（调整 ID、守护进程内部名、plist 键名等）未改动，功能与上游一致。

## 获取 IPA

推送到 main 会触发 GitHub Actions 的 **Build IPA** 工作流（云端 macOS + Xcode 构建，
未签名）。构建完成后在仓库 **Actions → 对应运行 → Artifacts** 下载
`GoldenNuggetMobile`，即未签名 IPA，自签后安装。应用要求 iOS 26 以上，
设备语言为中文时自动显示中文界面。

构建记录：2026-11-07 启用 Build IPA 工作流后触发首次云端构建。

翻译说明：本项目的简体中文翻译（应用内文案、README 与发行更新日志）由 AI 完成。

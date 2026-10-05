# iOS 定位模块

个人 Shadowrocket 定位配置，模块及脚本均托管于本仓库。

[模块订阅链接](https://raw.githubusercontent.com/novain1102/ios-location-spoofer/main/ios-location-spoofer.sgmodule)

## 来源与许可证

脚本 `location-spoofer.js` 与 `LICENSE` 原样同步自 [mekos2772/ios-location-spoofer](https://github.com/mekos2772/ios-location-spoofer)，上游提交为 [`06feaf2f2279ab966567f946d87ead9461564634`](https://github.com/mekos2772/ios-location-spoofer/commit/06feaf2f2279ab966567f946d87ead9461564634)。保留上游署名与版权信息，许可证为 [AGPL-3.0](LICENSE)。模块沿用上游格式，并配置个人坐标及本仓库脚本地址。

## 当前限制

此版本脚本在 `mode=response` 下仅改写响应中已有的纬度、经度和水平精度字段；海拔和垂直精度字段原样保留。因此，模块中的 `altitude=168` 与 `verticalAccuracy=20` 虽被解析，不会在该模式下实际改写对应字段。尚未进行手机端定位验证。

# 东方原曲与 8bit BGM 方案

QxBgmManager 的东方音乐替换方案仓库，原名 `qxbgm-schemes-touhou8bit`，现为 `qxbgm-schemes-touhou`。

## 原曲全替换方案

| 方案 | 替换条目 | 下载与说明 |
|---|---:|---|
| TH01 灵异传·原版全曲替换（修复版） | 15 | [下载](https://github.com/crt106/qxbgm-schemes-touhou/releases/tag/th01-original-v2.0.0) · [说明](docs/th01-original-full-v2.md) |
| TH08 永夜抄·原曲全替换（一轮版） | 20 | [下载](https://github.com/crt106/qxbgm-schemes-touhou/releases/tag/th08-original-v1.0.0) · [说明](docs/th08-original-full-v1.md) · [对应表](docs/th08-track-map.csv) |

使用 [QxBgmManager 0.1.2 或更新版本](https://github.com/crt106/QxBgmManager)，在方案市场刷新后安装；也可下载 `.qxbgmzip`，到“方案管理”打开并安装。

替换前退出游戏。TH01 与 TH08 共用编号 10009 和 10020，切换时先卸载前一个方案。更新或修复游戏前恢复音乐。

TH08 一轮版保持原速立体声和完整一轮旋律；当前地图有四个槽位时长偏短。[时长配置候选](docs/th08-map-timing-candidate.json) 需在地图工程单独接入，app 不会修改地图。

## 仓库结构

- `index/`：app 索引，同步收录于 [中心索引](https://github.com/crt106/qxbgm-registry)。
- `schemes/`：带音频下载地址及 SHA256 的方案清单。
- Releases：完整安装包、音频、校验值和测试报告。
- `docs/`：说明、对应表及尚未应用的地图时长配置。
- `audio/`：保留旧版 8bit 方案使用的音频。

## 原有单曲方案

- [东方妖怪小町 8bit](schemes/youkai-komachi.qxbgm.json)：替换编号 10071。
- [竹取飞翔 8bit](schemes/taketori-lunatic-princess.qxbgm.json)：替换编号 10140。

原曲权利归原作者所有；仓库工具和索引的许可不包含音频再授权。

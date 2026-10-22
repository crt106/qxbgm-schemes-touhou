# 东方原曲与 8bit BGM 方案

QxBgmManager 的东方音乐替换方案仓库，原名 `qxbgm-schemes-touhou8bit`，现为 `qxbgm-schemes-touhou`。

## 原曲全替换方案

| 方案 | 条目 | 下载与说明 |
|---|---:|---|
| TH01 灵异传·原版全曲替换（修复版） | 15 | [下载](https://github.com/crt106/qxbgm-schemes-touhou/releases/tag/th01-original-v2.0.0) · [说明](docs/th01-original-full-v2.md) |

使用 [QxBgmManager 0.1.2 或更新版本](https://github.com/crt106/QxBgmManager)，在方案市场刷新后安装；也可下载 `.qxbgmzip`，到“方案管理”打开并安装。替换前退出游戏。更新或修复游戏前请恢复音乐。

`index/` 为 app 索引，同步收录于 [中心索引](https://github.com/crt106/qxbgm-registry)。完整安装包和新音频放在 Releases，`schemes/` 保存带下载地址及 SHA256 的清单。

原曲权利归原作者所有；仓库工具和索引的许可不包含音频再授权。

## 结构

- `schemes/` — qxbgm/v1 manifest（`.qxbgm.json`）
- `audio/` — 已编码 wem 资产（大文件正式发布时应放 Releases 附件，此处为 P0 本地验证）

## 方案清单

| 方案 | 目标曲目 | 说明 |
|---|---|---|
| youkai-komachi | 难逃之阵 (10071 / fileID 122217526) | 東方妖怪小町 8bit，已实机验证 |
| taketori-lunatic-princess | 无尽的挑战 (10140 / fileID 15673379) | 竹取飛翔 8bit（编码中） |

## 使用

- QxBgmManager 方案管理页直接打开 `schemes/*.qxbgm.json`（P0 本地路径）。
- 上架：向 qxbgm-registry 索引仓库 PR 一条 `index/<id>.json` 注册条目。

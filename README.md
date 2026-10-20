# 东方 8bit BGM 方案仓库（发布者仓库示例）

本仓库是 qxbgm/v1 方案的发布者仓库示例，用 git 管理方案版本。

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

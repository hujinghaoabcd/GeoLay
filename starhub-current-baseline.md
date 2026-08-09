# StarHub 当前基线

> 2026-08-10 更新。后续分类审查、Rank 计算和项目数量均以最新 StarHub 导出为准。

## 最新导出

- 导出文件：`starhub-backup-2026-08-09 (1).json`
- StarHub 版本：`4.0`
- exportDate：`2026-08-09T21:52:46.116Z`
- repos：14,631
- tags：408
- taggedRepos：14,355
- untaggedRepos：276
- highlightedRepos：104

## 与上一基线比较

上一基线 `starhub-backup-2026-08-09.json`：15,427 repos。

最新基线：14,631 repos。

- 实际减少：796 个 Star
- 无新增 Star
- 796 = 旧 505 条断点删除 + Leaflet 断点后 291 条删除

因此，后续不再将旧 505 或 Leaflet 291 作为待执行项目。

## Python 生态修正

分类：`编程语言与通用库｜Python 生态`

- 上一基线：136 项，旧 Rank 3
- 最新基线：63 项
- 最新 Rank：81
- 用户锁定保留的 28 `arrow-py/arrow`、44 `sindresorhus/awesome-nodejs`、89 `antvis/component`、129 `wangchen415/UCAS-MAP` 均仍存在于最新导出。

此前记录中的 Python 生态“删除 73”不能再作为 73 个新增待执行项累计。最新导出显示，这 73 个删除项目已经包含在本次实际减少的 796 个仓库集合之中，存在跨分类/跨批次重叠。

## 后续规则

1. 从本基线开始重新计算所有分类 Rank；旧备份中的 Rank 不再沿用。
2. 分类项目数以最新导出的 tag.repos 为准。
3. 后续取消 Star 命令只针对最新基线之后新确认且仍存在于当前 repos 列表中的项目。
4. 生成命令前必须与当前基线和历史删除记录做仓库级去重。

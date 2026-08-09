# StarHub 清理断点

- 断点 ID：`2026-08-10-leaflet-framework-vue-angular-svelte`
- 创建日期：2026-08-10
- 主记录冻结提交：`be4b3d30f52181a742ed7327fda0d23873ce016d`
- 主记录范围：650 项（删除 333，保留 317）
- 本断点追加范围：223 项（删除 172，保留 51）
- 本断点累计：873 项（删除 505，保留 368）
- 本次取消 Star 命令数：505
- 最后完成分类：`前端与 WebGIS｜Leaflet｜框架集成｜Vue、Angular 与 Svelte`
- **下次起点：仅处理该分类之后新确认的项目；不得再次生成本断点中的 505 个取消 Star 命令。**
- 执行脚本：`starhub-unstar-checkpoint-2026-08-10.ps1`
- 脚本修正：Windows PowerShell 下不再直接解析 `gh api` 的 UTF-8 中文输出；改为读取 GitHub Contents API 的 Base64 内容后显式 UTF-8 解码，避免 `删除` 被错误解码导致 0 条匹配。
- 建议首次运行：`./starhub-unstar-checkpoint-2026-08-10.ps1 -GenerateOnly`，确认输出 `Commands: 505` 后再正式执行。

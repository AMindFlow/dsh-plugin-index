# AMindFlow 插件索引（DSH format 1）

AMindFlow 出品插件的 DeepSeek Harness 市场索引。在 DSH 插件页「自定义插件索引」源中粘贴：

    https://raw.githubusercontent.com/AMindFlow/dsh-plugin-index/main/market-index.json

条目 schema 为宿主 `@deepseek-ai/dsh-plugin-market-index` 的 format 1；每次上游插件发版后由其 `scripts/make-market-index.mjs` 取回本文件 upsert 再推送。安装始终钉各版本 tag 解引用后的 40 位 commit。

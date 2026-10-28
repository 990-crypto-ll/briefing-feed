# briefing-feed

每日金融 + AI 快报的数据文件，供安卓桌面小组件（联动版）读取。

- 数据文件：`feed.json`，每天早上约 8:00（Asia/Shanghai）更新当天一期
- 固定读取地址：https://raw.githubusercontent.com/990-crypto-ll/briefing-feed/main/feed.json
- 内容：金融消息与 AI 用法/应用各数条，英文在前、中文翻译在后；含当天行情
- 结构：`{"date", "fetchedAt", "quotes": [...], "items": [{"section", "title", "titleZh", "detail", "detailZh", "sourceName", "sourceUrl"}]}`

Daily finance + AI briefing feed (JSON) for the Android briefing widget. Updated daily around 08:00 Asia/Shanghai.

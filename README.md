# 讀小說學英文：書籍資源包

[讀小說學英文](https://epub-english.vercel.app) App 內建 20 本書，其他書做成資源包放在這裡，使用者在 App 的「書城」選擇下載。

- `index.json`：可下載的書目（書名、章數、難度、大小、版本）。
- `packs/<id>.json`：一本書的資源包，內含每章生字、片語、文法、全文和長句拆解。

資源包由主專案的 `pipeline/build_pack.py` 產生，不要手改。只收公版書。

書的原文來自 Project Gutenberg（公版書）；分級、字典、例句等資料來源與授權見主專案 README。

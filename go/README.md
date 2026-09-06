# go/ 短連結對照表

由 `12-tools/make-go-pages.mjs` 產生，對照 `11-tracking/utm-rules.md` 嘅渠道表。
改域名／落地頁路徑：改 `12-tools/make-go-pages.mjs` 頂部嘅 `BASE_URL` 常數，然後重新執行腳本（會覆蓋呢 12 個 .html）。

| 短連結 | 渠道 | utm_source | utm_medium | utm_campaign | 目標網址 |
|---|---|---|---|---|---|
| go/ig.html | IG bio | instagram | bio | q4_2026 | https://qosmio77.github.io/bookingyou-landing/?utm_source=instagram&utm_medium=bio&utm_campaign=q4_2026 |
| go/ig-post.html | IG 貼文／Reels | instagram | post | q4_2026 | https://qosmio77.github.io/bookingyou-landing/?utm_source=instagram&utm_medium=post&utm_campaign=q4_2026 |
| go/threads.html | Threads | threads | post | q4_2026 | https://qosmio77.github.io/bookingyou-landing/?utm_source=threads&utm_medium=post&utm_campaign=q4_2026 |
| go/xhs.html | 小紅書 | xiaohongshu | post | q4_2026 | https://qosmio77.github.io/bookingyou-landing/?utm_source=xiaohongshu&utm_medium=post&utm_campaign=q4_2026 |
| go/fb.html | FB 群組 | facebook | group | q4_2026 | https://qosmio77.github.io/bookingyou-landing/?utm_source=facebook&utm_medium=group&utm_campaign=q4_2026 |
| go/li.html | LinkedIn | linkedin | post | q4_2026 | https://qosmio77.github.io/bookingyou-landing/?utm_source=linkedin&utm_medium=post&utm_campaign=q4_2026 |
| go/x.html | X | x | post | q4_2026 | https://qosmio77.github.io/bookingyou-landing/?utm_source=x&utm_medium=post&utm_campaign=q4_2026 |
| go/wa.html | WhatsApp outreach | whatsapp | dm | q4_2026 | https://qosmio77.github.io/bookingyou-landing/?utm_source=whatsapp&utm_medium=dm&utm_campaign=q4_2026 |
| go/print.html | QR 名片／單張 | print | qr | q4_2026 | https://qosmio77.github.io/bookingyou-landing/?utm_source=print&utm_medium=qr&utm_campaign=q4_2026 |
| go/pr.html | 新聞稿／媒體 | pr | article | q4_2026 | https://qosmio77.github.io/bookingyou-landing/?utm_source=pr&utm_medium=article&utm_campaign=q4_2026 |
| go/ref.html | 商戶推薦 | referral | merchant | q4_2026 | https://qosmio77.github.io/bookingyou-landing/?utm_source=referral&utm_medium=merchant&utm_campaign=q4_2026 |
| go/ws.html | 工作坊 | event | workshop | q4_2026 | https://qosmio77.github.io/bookingyou-landing/?utm_source=event&utm_medium=workshop&utm_campaign=q4_2026 |

## 備註

- **ig-post.html**：來源表列「post / reel」，預設用 post；Reels 專用可另外複製一份改 utm_medium=reel。
- **ref.html**：實際使用時將 <商戶代號> 換成該商戶代號，呢頁 UTM 唔帶商戶代號（保持通用短連結）。
- **ws.html**：實際使用時將 <日期> 換成活動日期，呢頁 UTM 唔帶日期（保持通用短連結）。
- App Store Connect Campaign Link 嘅 `ct=` 值（同呢啲短連結分開、用喺 App Store 直連追蹤）已列喺下表最後一欄，方便對照 `11-tracking/utm-rules.md`。

| 短連結 | App Store ct= |
|---|---|
| go/ig.html | ig_bio |
| go/ig-post.html | ig_post |
| go/threads.html | threads |
| go/xhs.html | xhs |
| go/fb.html | fb_group |
| go/li.html | linkedin |
| go/x.html | x |
| go/wa.html | wa_dm |
| go/print.html | print_qr |
| go/pr.html | pr |
| go/ref.html | ref_<商戶代號> |
| go/ws.html | ws_<日期> |


# 關於我入侵 HITCON 的一檔事

先說，我沒有入侵 HITCON，我只是想要取個感覺很酷的標題，順便完成我申請學生票的 300 字心得。

總之，這是一個我偉大的計劃，終極目標就是在 HITCON 閉幕式提到今日流量排名的時候，能夠拿下排名第一。非常可惜的是，今年沒有公布網路用量的相關數據 🤬

![HITCON 2023 的網路流量排名](/posts/2026-HITCON/HITCON2023_rank.webp)

> 附上 HITCON 2023 的網路流量排名，啊為什麼第一名有 2.5 TB 啦，太多了吧（截圖取自 HITCON YouTube）

雖然今年沒有公布流量排名，但我還是成功拿下 283.72 GB 的上傳流量。

| Day 1 | Day 2|
| --- | --- |
| ![Day 1 流量](/posts/2026-HITCON/Day1-traffic.webp) | ![Day 2 流量](/posts/2026-HITCON/Day2-traffic.webp) |

# 具體要如何做到呢？

1. 首先，買一個 ipwnedhitcon.top 的 Domain
2. 接著，租一台 VPS，並讓其能夠接收並丟棄資料（回傳 200）
3. 最後，拿一台樹莓派放在會場瘋狂連續 POST 一大堆沒意義的資料

同時，確保以下原則，避免影響其他會眾：

1. 選擇上傳（Upload）而非下載（Download），因為上傳需求較少，對會眾影響更小
2. 設定速度上限，確保不會佔用過多頻寬影響其他人使用
3. 流量打向自己架設的伺服器，上傳資料由伺服器直接丟棄，不儲存任何內容
4. 若此行為對現場網路造成影響，將立即停止或降速

附上 http://ipwnedhitcon.top/ 的截圖，確保活動方能夠在受到影響的時候，取得聯繫方式：

![ipwnedhitcon.top 截圖](/posts/2026-HITCON/ipwnedhitcon.webp)

# 來點認真的

* 在「Out of LINE：一張 QR Code 盜走全球手機」的議程結束後，我突然發現我是那種覺得點連結或掃 QR Code 只要不要亂點操作或登入帳密就不會有問題的人，還是不要小看 ZeroDay 的力量好了，同時我也很敬佩 Flydragon 的好駭客精神，寧願被 Line ~~如此不負責任~~的回應，也沒賣給對岸。
* Orange Tsai 的「↖乂古法挖洞乂↘ ~~ 純邏輯 Microsoft Edge 零點擊沙箱逃逸鏈 ~~」大概是我最喜歡的議程之一吧！不論是 CVE-2024-4577、Apache 或這次的議程，都是那種把多個看起來沒什麼問題的程式片段，串出一個邏輯漏洞。議程最後他本人也提到在 AI 的時代，這種邏輯漏洞受限於 Content Window 的限制，反而是 AI 無法取代的工作。
* Steven Meow 在 HITCON 前就瘋狂的宣傳他的「The "Never Gave It Up" Harness: How AI Hacked a Payment Terminal and Turned It Into an Arcade」議程，所以我也非常這場的內容，全部由 AI 操作打下一台讀卡機聽起來超級無底有趣。同時他也用 Gemini Flash 作為 OpenClaw 的模型，負責督促 Claude Code 做事，避免了 Claude 總是愛放棄的心態。話說，我在 U 某服飾店也有看到同款讀卡機 XD
    ![](/posts/2026-HITCON/Uxx.webp)
* spitline 的純台語「原初之穢：先莫管供應鍊夆毒，阮直接共官方發布源頭駭掉矣」議程則是走本來沒打算搞笑的搞笑風格，用純台語講議程的理由竟然是擔心自己會不小心講支語！今年 DEVCORE Conference 的時候他就有講相關的議程，這場繼續延伸當時的研究，串起一系列的研究超屌。總結，台語穿插英文整個變得很滑稽。

# 結語

首先，感謝陪我鬧這齣把戲的夥伴們，以及不具名的某某某社群攤位提供插座，讓我能夠 24 小時不間斷的為樹莓派供電。以及這個偉大計劃的罪魁禍首，tusoar（對，這個我就是要具名）在某一年 HITCON 還是 SITCON 的提議。

最後，希望 HITCON 不要 DQ 我，明年繼續施捨我學生票，啾咪喲～
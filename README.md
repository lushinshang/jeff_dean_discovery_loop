# 別問AI能不能回答問題，問它能不能加速一次科學發現

本專案是一篇根據Jeff Dean（前Google Chief Scientist）與Dawn Song（UC Berkeley教授）於2026 Frontier & Pioneer Symposium爐邊對談內容整理、改寫而成的深度導讀，並補充查證了文中提及的具體數字與事件。

## 目錄內容

| 檔案 | 說明 |
|------|------|
| `index.html` | 發布用網頁版本，含全覽圖、Mermaid迴圈流程圖、關鍵數字資料卡、響應式排版 |
| `jeff_dean_discovery_loop.md` | 深度導讀 Markdown 原稿 |
| `research_notes.md` | 逐字稿結構化摘要與事實查證筆記 |
| `images/` | 全覽圖（含手機直式變體） |
| `qa_desktop.png` / `qa_mobile.png` | HTML 排版驗證截圖 |

## 200字介紹

Jeff Dean在Google待了二十七年，做出MapReduce、BigTable、TensorFlow、Gemini，這場對談發生在他離開Google、加入自己新公司Discovery Loop的第十二個半小時。他沒有花時間緬懷過去，反而解釋AI下一步該解決的問題：不是「答得更好」，而是能不能讓一整套科學發現流程自動跑起來。本文從Mixture-of-Experts的省能源直覺、TensorFlow開源時犯下的具體設計錯誤、Gemini如何靠一張備忘錄合併三個團隊，拆解出Dean判斷「值得投入五年的問題」的方法論——先找數量級的落差，把問題拆到大部分可控、少部分未知，然後試很多可能不會成功的事。文章也談到AI系統攻防兩端同時變強的資安風險（Hugging Face事件），以及Discovery Loop如何把這套方法論用在自動化科學方法本身：把每次實驗迭代從幾天壓縮到幾分鐘，並解釋為什麼在雲端運算普及的年代，聚焦的小團隊反而能贏過資源龐大的大公司。

## 原始素材

- 影片：https://youtube.com/watch?v=0kC3xOZChdA
- 逐字稿：`../transcription/Jeff_Dean__2026_Frontier_&_Pioneer_Symposium_0kC3xOZChdA.srt`

## 相關報導與延伸閱讀

- [Jeff Dean and other top AI researchers are leaving Google to launch their own startup（TechCrunch）](https://techcrunch.com/2026/08/05/jeff-dean-and-other-top-ai-researchers-are-leaving-google-to-launch-their-own-startup/) — 獨立佐證文中提及的離職時間點、共同創辦人名單、Google作為創始投資人的細節
- [The startup idea that convinced a UW computer science legend to leave Google after 27 years（GeekWire）](https://www.geekwire.com/2026/the-startup-idea-that-convinced-a-uw-computer-science-legend-to-leave-google-after-27-years/)
- [Our Investment in Discovery Loop（Radical Ventures）](https://radical.vc/our-investment-in-discovery-loop/)
- [當AI開始自己做實驗：Jeff Dean出走之後，科學發現還剩下什麼是人類的？](https://lushinshang.github.io/deepmind_caoyuan_ai4science/) — 同系列文章，前DeepMind研究科學家曹原對同一起離職事件的深度解讀

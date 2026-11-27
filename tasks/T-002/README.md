# [T-002] 閱讀論文
負責：Bongo ｜ 關聯：無 ｜ 期限：2026.10.11 (Sun)

## 狀態：完成

討論串：
- [dc 討論串](https://discord.com/channels/1397794408061206628/1557408138016325652)

任務執行情況：
- 閱讀 SD-MAE 與 AnomalyRuler 相關論文，整理影片異常偵測的基本方法與模型用途。
- 針對 SD-MAE 記錄異常判斷的概念，包括重建誤差、模型對異常的判斷，以及 Teacher／Student 結果的差異。
- 查閱 LaGoVAD 與影片異常偵測（VAD）的 Survey，整理不同方法在異常定義、輸出形式、監督方式、可解釋性及訓練需求上的差異。
- 初步整理三種模型在系統中的可能分工：SD-MAE／AED-MAE 提供異常影格與位置資訊；LaGoVAD 提供異常類別資訊；AnomalyRuler 提供規則與判斷理由。

結果與結論：
- 已整理候選模型的基本原理與功能差異，供後續架構討論及 MVP 驗證參考。
- 此任務以論文閱讀和技術比較為主；模型能否成功執行、實測效果與是否適合目標場景，仍需後續實驗確認。

參與對象：
- 主要負責：Bongo

相關文件：
- [T-002 任務說明](T-002.md)
- [SD-MAE 論文](https://arxiv.org/abs/2306.12041)
- [AnomalyRuler 論文](https://arxiv.org/abs/2407.10299)
- [LaGoVAD 論文](https://arxiv.org/abs/2503.13160)
- [影片異常偵測 Survey](https://arxiv.org/pdf/2409.05383)
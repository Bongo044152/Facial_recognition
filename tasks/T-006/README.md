# [T-006] 專題代碼與架構方面的 MVP 驗證

負責：洋溢 ｜ 關聯：無 ｜ 期限：2026.10.12 (Mon)

## 狀態：完成

> 本任務已依組內進度紀錄結案，但原訂完成條件並未全部達成。以下區分已進行的測試與尚未解決的問題。

## 任務執行情況

- **AnomalyRuler**：未能成功完成。因 CogVLM 權重下載耗時、Colab GPU 額度用盡，以及同時執行 LLM、VLM 造成記憶體不足（OOM）。
- **SD-MAE**：建立 Colab 測試程式並表示有產生結果，部分測試使用虛擬輸入資料，主要是確認模型能載入及輸入張量形狀，不能直接視為完整的模型重現。
- **額外驗證**：另行執行 SD-MAE 的推論與評分程式，回報約 88% 與 86% 的結果(與論文數值接近)。


## 結果與結論

- SD-MAE 已有初步程式測試及推論評分紀錄，但需要使用實際影格與資料載入流程進一步確認結果。
- AnomalyRuler 尚未成功重現，運算資源需求是當時的主要障礙之一。
- 後續因更換題目所以任務無繼續進行

## 討論串

- [dc 討論串](https://discord.com/channels/1397794408061206628/1557408566275612673)

## 參與對象

- 主要負責：洋溢
- 協助討論與驗證：夜貓、Bongo

## 相關文件

- [T-006 任務說明](T-006.md)
- [SD-MAE 測試 Colab](https://colab.research.google.com/drive/1wzdszsIam3lvtMMLRUMXmU7PCDF-womt?usp=sharing)
- [AnomalyRuler 測試 Colab](https://colab.research.google.com/drive/1Q_btqk_KpJUEc5xWtYfIxeNYcC7zYOMa?usp=sharing)
- [專案狀態](/STATUS.md)

> 註：上述 Colab 為討論串中提供的測試連結，並非已驗證可重現的正式版本；部分資料需另取得存取權限。
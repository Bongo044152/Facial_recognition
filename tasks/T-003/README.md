# [T-003] 專題題目前調查

負責：明哲 ｜ 關聯：無 ｜ 期限：2026.10.12 (Mon)

## 狀態：完成

## 任務執行情況

- **其他作品調查**：蒐集 Sentinel、VigilAI、icetana AI 等開源與商業系統，了解現有產品的異常偵測、事件告警、規則判斷等功能。
- **Survey 論文調查**：參考兩篇 VAD Survey，整理目前領域的主要方向：異常偵測、異常定位及異常理解，包含重建式方法、視覺語言模型與 LLM 的應用。
- **相關研究比較**：參考 Holmes-VAD，發現「先篩選可疑影格，再交由大型模型進行分析」已有相關研究。
- **可能改善方向**：提出跨場景適應、語意判斷可靠性、運算成本及資料集標註不足等問題，作為後續研究方向的參考。

## 結果與結論

- 現有開源及商業系統已有類似功能，單純串接模型難以作為主要研究貢獻。
- VAD 領域仍有跨場景適應、異常解釋可靠性及運算效率等問題值得研究。
- 本次完成初步調查，但尚未確定具體的研究貢獻；後續因更換專題方向，未繼續深入。

## 討論串

- [dc 討論串](https://discord.com/channels/1397794408061206628/1557408306031628379)

## 參與對象

- 主要負責：明哲
- 協助討論：Bongo

## 相關文件

- [T-003 任務說明](T-003.md)
- [VAD Survey（綜合）](https://arxiv.org/abs/2507.21649)
- [VAD Survey（LLM 方向）](https://www.merl.com/publications/TR2026-143)
- [Holmes-VAD](https://arxiv.org/abs/2406.12235)
- [Sentinel](https://github.com/khalequzzamanlikhon/sentinel-video-anomaly-detection)
- [VigilAI](https://github.com/hassanimtiaz158/VigilAI)
- [icetana AI](https://www.icetana.ai/video-anomaly)
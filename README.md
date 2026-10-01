## 從哪裡開始

| 想知道 | 去哪 |
|---|---|
| 現在的任務與進度 | [`STATUS.md`](/STATUS.md) |
| 需求是什麼 | [`docs/requirements/`](/docs/requirements/) |
| 為什麼這樣決定 | [`docs/adr/`](/docs/adr/) |
| 實驗做了什麼、結果如何 | [`tasks/`](/tasks/) |
| 階段彙整 | [`docs/reports/`](/docs/reports/) |
| 跟助教開會的會議紀錄 | [`docs/metting/`](/docs/metting/README.md) |

## 目錄結構

```
├── README.md
├── STATUS.md                # 任務表、待議
├── docs/
│   ├── requirements/        # 需求文件
│   ├── adr/                 # 決策紀錄
│   ├── metting/             # 跟助教開會的會議紀錄
│   └── reports/             # 階段彙整
├── tasks/
│   └── T-xxx/               # 一任務一資料夾
└── src/                     # 可能的原始碼
```

## 協作規則

1. Discord 負責討論，一議題一個 Thread。
2. 沒有寫進 `docs/adr/` 或 `STATUS.md` 的決定，視為還沒決定。
3. 每個任務先寫完成條件再開工。
4. 產出要進 repo 或 Hugging Face，任務才算完成。
5. 每項資訊只有一個家，其他地方放連結。

## 執行方式

TODO：待 `src/` 的技術選型與目錄定案後補上。

## 連結

- Hugging Face（權重與資料集）：TODO
<!-- - 需求文件：[`docs/requirements/`](/docs/requirements/) -->

權重與資料集放在 Hugging Face，不放在本 repo。
含真人人臉的資料不公開。

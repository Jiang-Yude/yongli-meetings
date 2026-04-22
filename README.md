# 永力扶輪社會議記錄

台北永續影響力扶輪社（永力社）與江昱德合作專案的會議記錄與分析歸檔。

官網入口：`index.html`（Vercel 部署網址見下方）

---

## 專案目的

1. 完整歸檔永力社與江昱德合作的會議記錄、會議報告網頁、分析文件
2. 提供統一入口網站，讓合作雙方隨時查閱歷次會議紀錄
3. 版本管控：每次修改有 commit 記錄，可回溯
4. 補充資料專區，收納會議中提到的延伸主題（如 AI 永續性觀點日記）

---

## 資料夾結構

```
yongli-meetings/
├── README.md                          專案說明（本檔）
├── index.html                         官網入口導覽頁
├── robots.txt                         禁止搜尋引擎收錄
├── .gitignore
├── meetings/
│   ├── 2026-03-31-kickoff/            第一次會議：AI 導入與永續報告書規劃
│   │   ├── record.md                  會議記錄（主版）
│   │   ├── record-gemini.md           會議記錄（Gemini 版本）
│   │   └── report.html                會議報告頁
│   ├── 2026-04-16-consensus/          第二次會議：共識決策與工作分配
│   │   ├── transcript.md              原始逐字稿
│   │   ├── record.md                  會議記錄（主版）
│   │   ├── summary.md                 對外精簡版＋後續代辦
│   │   ├── structure.md               網頁內容結構表
│   │   └── report.html                會議報告書網頁
│   └── 2026-04-17-analysis/           兩次會議人員態度軌跡分析
│       ├── analysis.md                分析文件
│       └── trajectory.html            軌跡視覺化圖表
├── docs/                              補充資料（會議中提到的延伸主題）
│   └── ai-sustainability-perspective.md
└── invitations/                       前置邀請往來
    └── aibi-response.md
```

---

## 檔名對照表（repo 短名 ↔ Obsidian 源檔名）

repo 內檔名是英文短名（for URL 友善），Obsidian 主知識庫保留原始中文完整檔名。兩邊內容同步但檔名不同。

| Repo 路徑 | Obsidian 源檔名 |
|---|---|
| `meetings/2026-03-31-kickoff/record.md` | `2026-03-31-2324 合作·永力扶輪社：永力扶輪社 AI導入與永續報告書規劃 會議記錄｜AI導入 永續報告書 會議記錄.md` |
| `meetings/2026-03-31-kickoff/record-gemini.md` | `2026-03-31-2319 合作·永力扶輪社：永利社AI知識庫與永續報告書會議記錄（Gemini製作）｜AI知識庫 永續報告書 會議記錄.md` |
| `meetings/2026-03-31-kickoff/report.html` | `2026-04-01-1410 永力扶輪社 AI導入與永續報告書規劃 會議報告頁.html` |
| `meetings/2026-04-16-consensus/transcript.md` | `2026-04-16-2340 永力社 永續報告書 共識與工作分配會議 原始逐字稿.md` |
| `meetings/2026-04-16-consensus/record.md` | `2026-04-16-2350 合作·永力扶輪社：永續報告書共識與工作分配會議記錄｜永續報告書 AI知識庫 工作分配.md` |
| `meetings/2026-04-16-consensus/summary.md` | `2026-04-16-2351 合作·永力扶輪社：永續報告書對外精簡版與後續代辦｜永續報告書 對外簡版 代辦.md` |
| `meetings/2026-04-16-consensus/structure.md` | `2026-04-16-2352 永力會議網頁內容結構表｜共識決策 代辦 細節.md` |
| `meetings/2026-04-16-consensus/report.html` | `2026-04-16-2353 永力扶輪社會議報告書：共識決策與工作分配網頁｜永續報告書 AI知識庫.html` |
| `meetings/2026-04-17-analysis/analysis.md` | `2026-04-17-2120 合作·永力扶輪社：兩次會議人員態度軌跡分析｜會議分析 態度轉變 推動者觀察.md` |
| `meetings/2026-04-17-analysis/trajectory.html` | `2026-04-17-2120 合作·永力扶輪社：兩次會議人員態度軌跡圖｜會議分析 態度軌跡 視覺化.html` |
| `docs/ai-sustainability-perspective.md` | `2026-04-18-1016 觀點日記：AI 這麼浪費算力，到底永不永續？｜AI永續 算力 食物浪費.md` |
| `invitations/aibi-response.md` | `2026-03-21-0935 合作·艾筆：艾筆回覆 永力社工作坊與共識營邀請｜永續報告書 工作坊 共識營.md` |

---

## 搜尋引擎策略

本 repo 為合作夥伴分享用途。雖然 repo 公開，但部署的網站禁止搜尋引擎收錄（`robots.txt` 已設定 `Disallow: /`）。知道分享連結的人才會進來看。

---

## 更新流程

Obsidian 主知識庫是真實源頭（source of truth）。repo 是對外版本的鏡像。

每次永力社會議有新檔案或更新：
1. 先在 Obsidian `06 合作專案統整/永力扶輪社/` 底下更新
2. 複製對應檔案到 repo 對應路徑（依上方對照表）
3. git commit + push
4. Vercel 自動部署

---

## 相關連結

- Obsidian 主知識庫：本地端
- GitHub repo：https://github.com/Jiang-Yude/yongli-meetings
- 部署網址：待首次部署後填入

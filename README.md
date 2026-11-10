## 使用情況調查（2026-11-09）

> 本節為 hanlin-edu-tech repo 清理作業的調查紀錄，待負責人確認後決定封存或刪除。

- 調查結論：仍在使用
- 建議處置：保留，理由：`profile/README.md` 是 hanlin-edu-tech 組織首頁顯示的介紹內容，刪除或封存 repo 會使組織首頁失去此內容。
- 最後更新：pushedAt 2022-08-15；最後 commit `b1756f4` 2022-08-15 hotdog929 Update README.md
- 用途：GitHub 組織層級的特殊 repo。目前只有 `profile/README.md`（組織首頁顯示的 eHanlin logo 圖片）與內容為空行的根目錄 `README.md`；沒有預設社群檔案（`CODE_OF_CONDUCT`、`CONTRIBUTING`、`ISSUE_TEMPLATE`、`PULL_REQUEST_TEMPLATE`、`LICENSE`）、沒有 `workflow-templates/`，其他 repo 沒有可繼承的檔案。本節寫在根目錄 `README.md`，不影響組織首頁的 `profile/README.md`。

### 檢查結果

| 檢查項目 | 結果 | 依據 |
|---|---|---|
| GitHub 活動 | 2022-08-15 後無 commit；組織首頁持續顯示 `profile/README.md` | 非 fork；僅 `main` 一個分支、6 個 commit（2022-08-03～2022-08-15，JerryLin、hotdog929）；PR 0、issue 0；Actions workflow 0、執行紀錄 0；release 0、tag 0；webhook 0；repo 檔案只有 `README.md`、`profile/README.md`；2026-11-09 開啟 `https://github.com/hanlin-edu-tech` 頁面含 `profile/README.md` 的 logo 圖片；community profile API 的社群檔案欄位全部為 null；PUBLIC repo，近 14 天 views 1 次（2026-10-26），clone 為 2026-10-28 2 次、2026-10-29 1 次（org 全面批次 clone）、2026-11-08 1 次，來源無法歸因 |
| org 內程式碼引用 | 查無其他 repo 引用 | `hanlin-edu-tech/.github` 0 筆；repo 內沒有可被 `uses:` 引用的 workflow 或 workflow 範本 |
| GCP 部署 | 不適用 | repo 只有 Markdown 檔，無部署設定 |
| AWS 部署 | 不適用 | repo 只有 Markdown 檔，無部署設定 |

### 待確認事項
- 無



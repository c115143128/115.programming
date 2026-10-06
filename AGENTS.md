# 專案指引

- 所有回應都使用繁體中文。
- 專案使用的程式語言為 Python。
- 使用 conda 管理 Python 套件，環境名稱為 `iem_python`；執行程式或管理套件前，先執行 `conda activate iem_python`。
- Git 提交身分使用 `user.name=Yu-Jun Liu`、`user.email=115143128@nkust.edu.tw`；需要設定時，使用儲存庫層級的 `git config --local`，不要修改全域設定。
- `week5.ipynb` 是唯一的程式來源；直接修改 Notebook，不要假設存在 Python 套件或腳本入口。
- Notebook 記錄 Python 3.12.13，核心名稱為 `python3`、顯示名稱為 `iem_python`；這些中繼資料不代表環境已安裝。儲存庫沒有依賴清單或環境建立設定。
- 修改 Notebook JSON 時保留儲存格 ID 與中繼資料；既有輸出和執行次數不是修改後程式的驗證結果。
- 沒有設定建置、lint、型別檢查或自動測試命令；驗證行為時，在 `iem_python` 環境對應的核心執行相關儲存格，無法執行時明確說明。

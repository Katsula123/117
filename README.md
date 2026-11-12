# LLM 研究知識庫（LLM Wiki）

本儲存庫採用 Karpathy 提出的 **LLM Wiki** 模式建立，並採**單層大資料夾結構**（不細分子資料夾），透過檔名前綴區分原始資料（`raw-*`）、Wiki 頁面（`paper-*`、`article-*`、`concept-*`、`model-*`、`comparison-*`）、研究筆記（`note-*`）與簡報（`outline-*`、`slides-*`）。

## 如何在 GitHub Pages 上打開網頁版知識庫

1. 將本資料夾內的所有檔案（包含 `index.html` 與 `.nojekyll`）上傳至 GitHub 儲存庫根目錄。
2. 前往儲存庫的 **Settings → Pages**。
3. 在 **Build and deployment → Branch** 選擇 `main` 與 `/ (root)`，點擊 **Save**。
4. 等待約 1 分鐘後，開啟 `https://<你的帳號>.github.io/<儲存庫名稱>/`，即可在清幽日系風的網頁中瀏覽所有筆記、點擊 `[[雙向連結]]` 並渲染 LaTeX 公式。

## 其他使用方式

- **用 Obsidian 開啟**：將本資料夾設為 Obsidian Vault，即可透過 Graph View、雙向連結與 Dataview 外掛瀏覽。
- **攝取資料（Ingest）**：將論文或文章貼給 Agent，Agent 會自動以 `raw-` 前綴保存原文，並建立或更新對應的 Wiki 頁面、`index.md` 與 `log.md`。
- **深度研究與簡報**：提出研究問題後，Agent 會依序產出 `note-*.md`、`outline-*.md` 與清幽日系編輯風的 `slides-*.html`。

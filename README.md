# `Ssdc-Glossary-V5-Final-Unfrozen_去敏公版-CYC.html` 說明

## 這份檔案是什麼

一份**通用軟體工程術語表**，去敏自原始檔 [`Ssdc-Glossary-V5-Final-Unfrozen-CYC.html`](./Ssdc-Glossary-V5-Final-Unfrozen-CYC.html)（原名 `Ssdc-Glossary-V5-Final-Unfrozen.html`，一個曾經公開存取的 GitHub Pages 網站）。內容涵蓋 Git、CI、部署、程式碼品質等 50 個詞條，不含任何公司內部資料，可以安心分享、當教材、或直接部署成公開頁面。

## 怎麼做的

原始檔案是 React 單檔渲染，86 個詞條的資料直接內嵌在壓縮過的 JavaScript 裡，不是能直接文字取代的格式。處理方式：

1. 用正規表示式把 86 個詞條的完整資料結構化解析出來。
2. 逐條人工判斷是否涉及公司資料或資安細節。
3. 對判定安全的詞條，重寫說明文字，拿掉所有指回原始內部文件的措辭（例如「文中…」「本案例…」）。
4. 用乾淨的靜態 HTML 重新產出，套用大字體排版（內文 23px），不再依賴原本的 React 執行環境。

## 怎麼用

直接用瀏覽器開啟即可，不需要伺服器或建置流程。這份檔案也複製了一份到教學工作區的 [`reference/軟體工程術語表.html`](./如何用Claude分工開發_從小任務到大專案/reference/軟體工程術語表.html)，供課程內容引用查閱。



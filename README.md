# 泰文影子跟讀

## 新增來源
把 `.txt` 放進 `data/` 資料夾並 push，GitHub Actions 會自動更新 `data/index.json`，
檔名（不含 .txt）就是下拉選單的名稱。

## txt 格式
```
1. 泰文單字：詞性 中文意思
泰文例句： ...
中文翻譯： ...
```
`一、…` 這類標題行會被忽略。

## 部署（GitHub Pages）
1. 建立 repo，推上所有檔案。
2. Settings › Pages › Source 選 `Deploy from branch`，Branch 選 `main` / `(root)`。
3. 網址：`https://<帳號>.github.io/<repo>/`

## 本機預覽
瀏覽器不能用 file:// 讀取 txt，請在此資料夾執行 `python3 -m http.server`，開 http://localhost:8000

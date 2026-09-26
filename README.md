# 張侑傑 Yu-Chieh Chang｜個人履歷網站

以繁體中文為主、附英文摘要的個人網站，整理我的 AI 研究、軟體開發與程式教育經歷。

[個人網站](https://ujayjoandao.github.io/) · [GitHub](https://github.com/UJayJoAnDao) · [LinkedIn](https://www.linkedin.com/in/%E4%BE%91%E5%82%91-%E5%BC%B5-165311305/)

## 關於我

目前就讀國立臺北科技大學人工智慧科技碩士學位學程，預計於 2027 年 7 月畢業，並於築景都更擔任實習工程師，負責 AI 導入。

主要關注：

- **交通事故偵測**：以公開 ACCIDENT 資料集，研究結合物件偵測與時序資訊的事件偵測方法。
- **文件 AI 與本地部署**：運用 LLM 擷取謄本內容、整理結構化資料並整合資料庫，以 Ollama 部署本地模型。
- **軟體開發與教育**：曾於叡揚資訊參與金融系統開發，並在橘子蘋果程式學院擔任程式設計講師。

## 網站架構

採明亮、簡潔的單頁履歷版面，以暖白底色搭配綠色與橘色點綴，支援桌面、手機與列印。

| 區塊 | 內容 |
| --- | --- |
| 個人介紹 | 姓名、照片、目前身分、簡介與聯絡方式 |
| 工作經歷 | 築景都更、叡揚資訊、橘子蘋果程式學院 |
| 研究與競賽 | 路口交通事故偵測、2026 鐵客松「鐵道全面電子化平台」 |
| 早期公開作品 | 判決書分類、AutoDrive、RaiseYourHand |
| 學歷與技能 | 北科大 AI 碩士學程、技術與實務、英文摘要 |

## 技術與檔案

使用原生 HTML 與 CSS，不需安裝前端套件或執行建置程序。

```text
.
├── index.html                       # 頁面內容、響應式樣式與列印樣式
├── portrait.jpg                     # 個人照片
├── accident-detection-example.jpg   # 研究示例圖片
└── README.md                        # 網站說明
```

頁面包含語意化區塊、圖片替代文字、鍵盤焦點樣式、跳至主要內容連結，以及減少動態效果的偏好設定支援。

## 本機預覽

下載或 clone 儲存庫後，直接以瀏覽器開啟 `index.html` 即可。請保持兩張圖片與 HTML 位於同一層目錄。

若已安裝 Python，也可在儲存庫根目錄執行：

```sh
python -m http.server 8000
```

接著開啟 [本機預覽](http://localhost:8000)。結束時按 `Ctrl+C`。

## GitHub Pages

此儲存庫對應的網站網址為 [ujayjoandao.github.io](https://ujayjoandao.github.io/)。

使用分支部署時，在儲存庫的 **Settings → Pages** 設定：

- Source：`Deploy from a branch`
- Branch：`main`
- Folder：`/ (root)`

將網站修改合併至 `main` 後，可在 GitHub 的 Pages 設定或 Actions 查看部署狀態。部署完成後，公開網址才會顯示更新內容。

## 維護方式

- **更新履歷**：直接編輯 `index.html` 中的個人介紹與各區塊內容；英文摘要與頁面描述也應一併更新。
- **調整配色**：修改 `<style>` 內 `:root` 定義的 CSS 色彩變數。
- **替換照片或研究圖片**：替換對應圖片檔案；若更換尺寸或內容，同時更新 HTML 的 `width`、`height`、`alt` 與圖說。
- **新增研究成果**：目前圖片為單一影格的物件偵測示例；待成果可公開時，再補上事件偵測結果、論文或展示連結。
- **更新競賽狀態**：2026 鐵客松目前為決賽入圍，預計於 2026 年 12 月底公布結果。
- **發布前檢查**：確認手機與桌面排版、圖片、聯絡連結及頁內導覽正常，並更新頁尾日期。

## 聯絡方式

- Email：[plmoknijb1234510@gmail.com](mailto:plmoknijb1234510@gmail.com)
- GitHub：[UJayJoAnDao](https://github.com/UJayJoAnDao)
- LinkedIn：[張侑傑](https://www.linkedin.com/in/%E4%BE%91%E5%82%91-%E5%BC%B5-165311305/)

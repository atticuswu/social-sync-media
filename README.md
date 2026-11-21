# social-sync-media

social-sync 專案的影片代管。Threads 與 Instagram 的發佈 API 只收公開網址，不能直接上傳檔案，所以發佈前把轉好格式的影片推到這裡，用 GitHub Pages 的網址給它們抓。

- 檔案放在 `v/`，網址是 `https://atticuswu.github.io/social-sync-media/v/<檔名>.mp4`。
- 這裡的影片都已經公開發在 Facebook 上；只放公開貼文的影片。
- 由程式自動推送，超過保留天數的舊檔會自動從工作目錄刪掉（git 歷史仍保留）。

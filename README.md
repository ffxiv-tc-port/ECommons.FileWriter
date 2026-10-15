<!-- ffxiv-tc-port 繁體中文說明開始 -->
# ECommons.FileWriter(台服 fork)

ECommons 的獨立檔案寫入小程式（上游 [Limiana/ECommons.FileWriter](https://github.com/Limiana/ECommons.FileWriter)）。ECommons 的 `ExternalWriter` 透過匿名管道把檔名與內容（附 SHA1 校驗）交給它，由這個獨立行程寫入磁碟。

## 台服 fork 的目的

- 讓 AutoRetainer 的子模組網址指向本 org，建置不依賴上游 repo 是否還在、有沒有被改寫。

## 與上游的差異

- 沒有我方的 commit，分支內容與上游相同。

## 誰在用它

- [AutoRetainer](https://github.com/ffxiv-tc-port/AutoRetainer)：子模組 `ECommons.FileWriter`；專案參照把它的建置輸出當成內容檔，隨插件一起出貨。

<!-- ffxiv-tc-port 繁體中文說明結束 -->

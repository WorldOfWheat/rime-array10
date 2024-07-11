# 這個專案是什麼？
行列是一種輸入法，並且根據其原理分為行列 10 和 30。行列 10 只需要 0~9 這十個按鈕即可輸入，因為行列 10 目只僅有 gcin 和萊姆輸入法可用，但萊姆輸入法已停止開發，因此我做了這個基於 Rime 引擎的行列 10 方案。

# 我可以用在哪裡？
這個方案是設計用來給手機使用的，目前只有為 Android 的 ![Trime](https://github.com/osfans/trime) 設計。

但我也非常歡迎其它人幫忙移植到其它平台，幫這個輸入法移植到更多平台

# 如何使用該輸入法
首先你要先有上述提到的 ![Trime](https://github.com/osfans/trime)，並且你需要找到一個名為 `rime` 的資料夾，之後把這裡所有名為 array10 東西都複製進去。

如果你的 Trime 跟我一樣沒有辦法在 `Schemata` 找到行列 10，那麼請你連同 `build` 資料夾一起複製進 `rime` 資料夾。

`Schemata` 和 `Theme & Color/Themes` 皆需要啟用。

# 如何更改鍵盤配置
我建議僅更改 `array10.trime.yaml` 這個檔案，並且可以參考 Trime 官方文件。

# 特別感謝
行列輸入法發明人 - 廖明德

行列 10 碼表 ![GitHub](https://github.com/gontera/array10)

# 參考資料
![rime-array](https://github.com/rime/rime-array)

![Rime 官方文件](https://github.com/rime/home/wiki/)

![Trime 官方文件](https://github.com/osfans/trime/wiki)

![Android 上的 RIME 输入法 trime 同文输入法使用](https://einverne.github.io/post/2021/04/use-trime-input-method-rime-on-android.html)

![关于以数字键小键盘为输入方式的纵横码配置 #718](https://github.com/rime/home/discussions/718)

![預設鍵盤檔 trime 3.2.14 只剩注音](https://github.com/oniondelta/Onion_Trime_Files/issues/1)

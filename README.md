# 常用地點簡訊報案

https://chiuchiubro.github.io/sms-report/

選常用地點、違規事實、車牌，打開手機簡訊 App 傳給當地警察局的簡訊報案專線。
地點只存在你的瀏覽器（localStorage），這個網站沒有後端。

這個 repo 只放建置結果，請不要直接改；原始碼與說明在私人 repo 的 `modules/sms-report/`，
改完跑 `python modules/sms-report/build.py` 再把 `dist/` 複製過來。

警察局號碼與違規選項取自 [Willseed/report-via-mobile](https://github.com/Willseed/report-via-mobile)（MIT）。

# md5-xscript
https://app.hackthebox.com/challenges/67
Emdee five for life
用python寫一個快速解網站MD5的植並且輸入取得FLAG，
用手動絕對不行，如果用手動的方式解，
時間會來不及，網站會告訴你太慢。

寫的程式主要有下列幾個要點
1.請求模組：透過 GET 或 POST 請求與 Web 應用程式進行通信
2.Re模組：從網頁中抓取字串
3.Hashlib 模組：計算字串的 md5 雜湊值
4.Sys模組：允許我們退出腳本
5.Cmd模組：用於插入Python腳本將使用的URL

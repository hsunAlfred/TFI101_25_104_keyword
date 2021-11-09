# TFI101_25_陳正勳_104人力銀行_關鍵字搜尋爬蟲

### 使用方式
在命令列使用
```
python 104.py arg1(關鍵字) arg2(前n頁)
```
eg. 
```
python 104.py 軟體 3
```
代表到104爬取關鍵字為軟體的前3頁

### 資料儲存
資料夾：104_關鍵字_first 最大頁數 pages_建立時間
eg.
```
104_軟體_first 1 pages_2021-11-09 23-39-03
```

### 資料儲存1
用途：索引
格式：Excel
欄位：更新日期、職缺連結、職缺名稱、公司名稱、公司連結、所屬產業、所在區域、工作經歷、學歷要求、職缺描述
檔名：104_關鍵字_索引_first 最大頁數 pages_建立時間.xlsx
eg.
```
104_軟體_索引_first 1 pages_2021-11-09 23-39-03.xlsx
```

### 資料儲存2
用途：個職缺詳細內容
格式：Json
欄位：更新日期、職缺連結、職缺名稱、公司名稱、公司連結、所屬產業、所在區域、工作經歷、學歷要求、職缺描述
檔名：更新日期_職缺名稱_公司名稱.json
eg.
```
1022_軟體工程師Software Engineer_薩摩亞商耀爵有限公司台灣分公司.json
```

### 程式執行資訊
執行完成後，會顯示Done
主程式執行過程錯誤可參見err.log

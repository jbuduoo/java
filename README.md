# java11安裝環境變數 

一、使用者變數和系統變數的差別?
使用者變數只對當前使用者有效，系統變數對所有使用者有效

## 安裝流程：
### 一、下載 JDK
https://jdk.java.net/archive/
11.0.1 (build 11.0.1+13)
Windows 64-bit zip (sha256) 179 MB
解壓縮
### 二、設定系統環境變數
本機按右鍵/內容/進階系統設定/環境變數/系統變數
加入到path中:
D:\Java\jdk-11.0.2，請填寫自已的路徑
D:\Java\jdk-11.0.2\bin，請填寫自已的路徑
### 三、測試是否安裝成功
開啟cmd.exe
執行java -version，看JDK版本
執行javac -version，看JRE版本

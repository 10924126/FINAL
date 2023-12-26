# 第一章問題定義
## 1.1業務調查
隨著社會的發展和人民生活水平的提高，買車成為了人們奮鬥目標之一，當然已經有很多人買了車。可是隨著車輛的增加，車輛的停泊問題也隨之出現。人們的生活方式發生看深刻的變化。城市的交通用即便是這種變化所引起的現象之一。城市由於交通設施的增加造成的交通擁擠甚至混亂給人們的生活帶來了極大的不便，這種不便迫使人們尋求高技術的有效手段去解決這種不便，這就使得各個停車場需要更加先進，更加完善的車輛管理系統，為車主帶來方便，使停車場的管理系統化，因此開發了停車場管理系統。
## 1.2需求陳述
1)車主進入停車場：當車主在停車場外時，停車場外的顯示屏將顯示空餘停車位的數量。若有空餘車位，車主來到擋車器前，系統自動識別車牌號，記錄車輛進入停車場的時間與車牌號，擋車器放行，車主進入停車場。若因某些原因系統無法識別，例如車輛尚未上牌或使用臨時車牌，此時由管理員負責手動輸入車輛信息（車牌號、進入時間、特殊情況備註：未上牌或臨時牌），若無特殊情況則不需要備註。

2)車主離開停車場：車主再次來到擋車器前，系統自動識別車牌號，記錄車輛離開停車場的時間，並計算停車費用。車主完成支付後，擋車器放行，車主離開停車場。若出現以上特殊情況，則由管理員手動處理輸入信息，費用則由系統完成計算。

3)管理員查看車輛信息：管理員登入系統後，能夠對車輛信息（車牌號、進出時間、停車費用、特殊情況備註）進行管理，可查詢車輛信息、添加車輛信息、刪除車輛信息。
## 1.3 業務模型
### 1.3.1業務模型
![image](https://github.com/10924126/FINAL/blob/main/drawio%20png/%E6%A5%AD%E5%8B%99%E6%A8%A1%E5%9E%8B.drawio.png)
### 1.3.2車主業務活動圖
![image](https://github.com/10924126/FINAL/blob/main/drawio%20png/%E8%BB%8A%E4%B8%BB%E6%A5%AD%E5%8B%99%E6%B4%BB%E5%8B%95%E5%9C%96.drawio.png)
### 1.3.3管理員業務活動圖
![image](https://github.com/10924126/FINAL/blob/main/drawio%20png/%E7%AE%A1%E7%90%86%E5%93%A1%E6%A5%AD%E5%8B%99%E6%B4%BB%E5%8B%95%E5%9C%96.drawio.png)
# 第二章 需求分析
## 2.1 系統用例建模（根據對1.2的分析進行系統用例建模）
### 2.1.1 參與者概述
1)車主—— 停車服務

2)管理員—— 管理車輛進出的相關信息
### 2.1.2 用例概述
1)車主來到有空餘車位的停車場，進入停車場停車，支付停車費用後離開停車場

2)管理員輸入正確的帳號和密碼登入系統，管理車輛進出的信息，包括車牌號、進出時間、停車費用。
### 2.1.3 用例關係
正在上傳...重新上傳取消
![image](https://github.com/10924126/FINAL/blob/main/drawio%20png/%E7%94%A8%E4%BE%8B%E9%97%9C%E4%BF%82.drawio.png)
## 2.2用例規約說明
表2-1 "進入停車場"用例規約
![image](https://github.com/10924126/FINAL/blob/main/%E5%85%B6%E4%BB%96%E5%9C%96%E7%89%87/%E8%A1%A82-1.png)

表2-2 "進入停車場"用例規約

![image](https://github.com/10924126/FINAL/blob/main/%E5%85%B6%E4%BB%96%E5%9C%96%E7%89%87/%E8%A1%A82-2.png)

表2-3 "支付費用"用例規約

![image](https://github.com/10924126/FINAL/blob/main/%E5%85%B6%E4%BB%96%E5%9C%96%E7%89%87/%E8%A1%A82-3.png)

表2-4 "離開停車場"用例規約
![image](https://github.com/10924126/FINAL/blob/main/%E5%85%B6%E4%BB%96%E5%9C%96%E7%89%87/%E8%A1%A82-4.png)

表2-5 "登陸"用例規約
![image](https://github.com/10924126/FINAL/blob/main/%E5%85%B6%E4%BB%96%E5%9C%96%E7%89%87/%E8%A1%A82-5.png)

表2-7 "查詢車輛信息"用例規約
![image](https://github.com/10924126/FINAL/blob/main/%E5%85%B6%E4%BB%96%E5%9C%96%E7%89%87/%E8%A1%A82-7.png)

表2-8 "導入車輛信息"用例規約
![image](https://github.com/10924126/FINAL/blob/main/%E5%85%B6%E4%BB%96%E5%9C%96%E7%89%87/%E8%A1%A82-8.png)

表2-9 "刪除車輛信息"用例規約
![image](https://github.com/10924126/FINAL/blob/main/%E5%85%B6%E4%BB%96%E5%9C%96%E7%89%87/%E8%A1%A82-9.png)
### 第三章 面向對象分析
## 3.1用例實現
使用順序圖，按B-C-E架構實現每一個用例


![image](https://github.com/10924126/FINAL/blob/main/drawio%20png/%E7%99%BB%E5%85%A5%E6%99%82%E5%BA%8F%E5%9C%96.drawio.png)

圖3-1登陸時序圖


![image](https://github.com/10924126/FINAL/blob/main/drawio%20png/%E5%88%AA%E9%99%A4%E8%BB%8A%E8%BC%9B%E8%A8%8A%E6%81%AF%E6%99%82%E5%BA%8F%E5%9C%96.drawio.png)

圖3-2刪除車輛信息時序圖


![image](https://github.com/10924126/FINAL/blob/main/drawio%20png/%E6%B7%BB%E5%8A%A0%E8%BB%8A%E8%BC%9B%E8%A8%8A%E6%81%AF%E6%99%82%E5%BA%8F%E5%9C%96.drawio.png)

圖3-3添加車輛信息時序圖


![image](https://github.com/10924126/FINAL/blob/main/drawio%20png/%E6%9F%A5%E6%89%BE%E8%BB%8A%E8%BC%9B%E8%A8%8A%E6%81%AF%E6%99%82%E5%BA%8F%E5%9C%96.drawio.png)

圖3-5查找車輛信息時序圖


![image](https://github.com/10924126/FINAL/blob/main/drawio%20png/%E6%9F%A5%E7%9C%8B%E8%BB%8A%E8%BC%9B%E8%A8%8A%E6%81%AF%E6%99%82%E5%BA%8F%E5%9C%96.drawio.png)

圖3-6查看車輛信息時序圖
## 3.2分析類模型
建立系統的分析類圖，為每個類分配職責、屬性，及對類之間的關西建模

![image](https://github.com/10924126/FINAL/blob/main/drawio%20png/%E5%88%86%E6%9E%90%E9%A1%9E%E5%9C%96.drawio.png)
# 第四章 面相對象設計
## 4.1數據庫設計
數據庫結構
1.車輛信息表
![image](https://github.com/10924126/FINAL/blob/main/%E5%85%B6%E4%BB%96%E5%9C%96%E7%89%87/%E8%BB%8A%E8%BC%9B%E4%BF%A1%E6%81%AF%E8%A1%A8.png)
表3.5車輛信息表
2.管理員信息表
![image](https://github.com/10924126/FINAL/blob/main/%E5%85%B6%E4%BB%96%E5%9C%96%E7%89%87/%E7%AE%A1%E7%90%86%E5%93%A1%E4%BF%A1%E6%81%AF%E8%A1%A8.png)
表4.1管理員信息表
## 4.2設計類
實體類

在ODA階段得到的類圖中有兩個實體，分別是車輛和管理員。

邊界類

1.管理員登錄邊界類 - LogOn.java
2.車輛信息管理 - MainWindows.java
3.輸入車輛信息界面 - AddCar.java
4.查詢車輛信息界面 - FindCar.java
5.刪除車輛信息界面 - DelCar.java
控制類

1.登錄控制類 - 接收登錄請求，控制登錄過程的狀態，調用模型，將請求轉發到管理員登錄邊界類 LogOn.java。
2.車輛信息管理 - 接收請求，控制車輛信息管理的執行狀態，調用模型，獲得處理結果，將請求轉發到車輛信息管理 MainWindows.java。
3.輸入車輛信息 - 接收輸入請求，控制車輛信息輸入的執行狀態，調用模型，處理結果，將請求轉發到輸入車輛信息 AddCar.java。
4.查詢車輛信息 - 接收查詢請求，控制查詢車輛信息的執行狀態，調用模型，得到處理結果，將請求轉發到查詢車輛信息 FindCar.java。
5.刪除車輛信息 - 接收刪除請求，控制刪除車輛信息的執行狀態，調用模型，得到處理結果，將請求轉發到刪除車輛信息 DelCar.java。
## 4.3 軟體體系結構
本系統採用MVC設計模式搭建程序結構，模型用來完成對業務邏輯的封裝，控制器控制各個程序流程，也就是前述設計的控制類的實現；視圖用來顯示頁面，也就是前述設計的邊界類的實現。
模型部分除了封裝上述實體類的屬性外，還需要實現對應的各個方法，對全部的業務功能進行分類，設計各個業務的Bean如下。
carService實現車輛信息管理相關的業務，包含以下方法：
add_in() - 在車輛信息表中添加一條車輛入庫信息。
Add_out() - 在車輛信息表中添加一條車輛出庫信息。
FindCar() - 查詢車輛信息。
delCar() - 刪除車輛信息。
lookCar() - 查看車輛信息。
## 4.4 交互介面設計
1.登陸logOn.java

![image](https://github.com/10924126/FINAL/blob/main/%E5%85%B6%E4%BB%96%E5%9C%96%E7%89%87/%E7%99%BB%E9%99%B8%E4%BB%8B%E9%9D%A2%E8%A8%AD%E8%A8%88.png)

圖4-1登陸介面設計


2.車輛信息管理mainWindows.java

![image](https://github.com/10924126/FINAL/blob/main/%E5%85%B6%E4%BB%96%E5%9C%96%E7%89%87/%E8%BB%8A%E8%BC%9B%E4%BF%A1%E6%81%AF%E7%AE%A1%E7%90%86%E4%BB%8B%E9%9D%A2%E8%A8%AD%E8%A8%88.png)


圖4-2車輛信息管理介面設計

![image](https://github.com/10924126/FINAL/blob/main/%E5%85%B6%E4%BB%96%E5%9C%96%E7%89%87/%E7%80%8F%E8%A6%BD%E8%BB%8A%E8%BC%9B%E4%BF%A1%E6%81%AF.png)


圖4-3瀏覽車輛信息

![image](https://github.com/10924126/FINAL/blob/main/%E5%85%B6%E4%BB%96%E5%9C%96%E7%89%87/%E6%B7%BB%E5%8A%A0%E8%BB%8A%E8%BC%9B%E4%BF%A1%E6%81%AF.png)


圖4-4添加車輛信息

![image](https://github.com/10924126/FINAL/blob/main/%E5%85%B6%E4%BB%96%E5%9C%96%E7%89%87/%E6%B7%BB%E5%8A%A0%E5%87%BA%E5%BA%AB%E8%BB%8A%E8%BC%9B%E4%BF%A1%E6%81%AF.png)

圖4-5添加出庫車輛信息


6.刪除車輛信息DelCar.java

![image](https://github.com/10924126/FINAL/blob/main/%E5%85%B6%E4%BB%96%E5%9C%96%E7%89%87/%E5%88%AA%E9%99%A4%E8%BB%8A%E8%BC%9B%E4%BF%A1%E6%81%AF.png)

圖4-6刪除車輛信息


7.查詢車輛信息findCar.java

![image](https://github.com/10924126/FINAL/blob/main/%E5%85%B6%E4%BB%96%E5%9C%96%E7%89%87/%E6%9F%A5%E8%A9%A2%E8%BB%8A%E8%BC%9B%E4%BF%A1%E6%81%AF.png)
# 第五章 面相對象實現
## 5.1停車場信息管理系統編碼實現
本系統基於Java+MySQL+ swing

![image](https://github.com/10924126/FINAL/blob/main/%E5%85%B6%E4%BB%96%E5%9C%96%E7%89%87/java.png)
# 第六章 軟建測試與部屬
## 6.1軟建測試
本停車管理系統在設計開發過程中遵循軟體測試的V模型以規範軟體測試。V模型推行開發與測試並行的方式，在開發完一個功能模塊後就進行相應的單元測試，注重細節方面的問題，接著再進行集成測試，主要測試模塊間的接口能否互通的問題。最後，在進行功能測試來檢測整個系統運行是否正常。

在測試過程中主要採取的是功能測試，通過功能測試可以逐一檢測各個功能是否可以滿足停車場管理人員的需求。
## 6.2 功能測試
功能測試是一種黑盒測試，這是根據軟體需求的要求設計測試用例並驗證系統功能的過程，並且通過與測試系統的外部輸入與輸出的關係來驗證，功能測試在於測試功能是否正常，因此不考慮內部的實現方式，測試的前提就是系統已經處於運行狀態。

本停車管理系統在設計開發過程中多次對系統功能進行測試，確保功能的正常運作。
## 6.3 功能測試總結
主要對停車場管理系統的登錄、車輛駛入、車輛駛出、對車輛信息的增刪改查操作進行功能測試，測試過程中界面UI的顯示都符合預期，功能方面符合需求。
##　6.4 用例測試
### 6.4.1 登錄用例測試
![image](https://github.com/10924126/FINAL/blob/main/%E5%85%B6%E4%BB%96%E5%9C%96%E7%89%87/%E7%99%BB%E9%8C%84%E7%94%A8%E4%BE%8B%E6%B8%AC%E8%A9%A6.png)
### 6.4.2添加信息用例測試
![image](https://github.com/10924126/FINAL/blob/main/%E5%85%B6%E4%BB%96%E5%9C%96%E7%89%87/%E6%B7%BB%E5%8A%A0%E4%BF%A1%E6%81%AF%E7%94%A8%E4%BE%8B%E6%B8%AC%E8%A9%A6.png)
### 6.4.3查詢信息用例測試
![image](https://github.com/10924126/FINAL/blob/main/%E5%85%B6%E4%BB%96%E5%9C%96%E7%89%87/%E6%9F%A5%E8%A9%A2%E4%BF%A1%E6%81%AF%E7%94%A8%E4%BE%8B%E6%B8%AC%E8%A9%A6.png)
### 6.4.4瀏覽信息用例測試
![image](https://github.com/10924126/FINAL/blob/main/%E5%85%B6%E4%BB%96%E5%9C%96%E7%89%87/%E7%80%8F%E8%A6%BD%E4%BF%A1%E6%81%AF%E7%94%A8%E4%BE%8B%E6%B8%AC%E8%A9%A6.png)
### 6.4.5刪除信息用例測試
![image](https://github.com/10924126/FINAL/blob/main/%E5%85%B6%E4%BB%96%E5%9C%96%E7%89%87/%E5%88%AA%E9%99%A4%E4%BF%A1%E6%81%AF%E7%94%A8%E4%BE%8B%E6%B8%AC%E8%A9%A6.png)
## 6.5本章小節
本章捷主要介紹了對停車場管理系統進行功能測試的必要性和測試結果，針對當前停車管理系統設系了一系列的功能測試用例。通過系統測試使系統更能府和預期要求，並能檢測和修復一些開發過程中的bug。

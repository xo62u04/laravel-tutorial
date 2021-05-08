# 使用vscode建置laravel，並透過XAMPP啟動laravel專案
## 安裝懶人包：
1. xampp的安裝選項要改(步驟
2. 確認composer的路徑有沒有錯誤
##  下載連結整理：
### XAMPP：https://www.apachefriends.org/xampp-files/8.0.3/xampp-windows-x64-8.0.3-0-VS16-installer.exe
### compooser：https://getcomposer.org/Composer-Setup.exe
### VS code 下載網址：https://code.visualstudio.com/sha/download?build=stable&os=win32-x64-user



# 1. 安裝 php 8.0.3版本的XAMPP，XAMPP裡面內建apachee + mysql + php + phpmyadmin，一套包裝好的伺服器環境提供給我們使用
### xampp安裝步驟：
### 1.1 將所有選項勾起來
![](https://i.imgur.com/uKDHK26.png)
### 1.2 選擇自己安裝路徑
![](https://i.imgur.com/hQJGiWM.png)
### 1.3 選擇語言 (使用english)
![](https://i.imgur.com/7I5G0Hi.png)
### 1.4 直接選next
![](https://i.imgur.com/G3gMmOg.png)
### 1.5 再次直接選next，就會開始安裝囉
![](https://i.imgur.com/RcL4JdE.png)

# 2. php 套件管理工具 composer

### composer安裝步驟：
1. ### 直接選 next
![](https://i.imgur.com/NQjcp6P.png)
2. ### php路徑會自動帶入xampp的php，確認路徑沒錯後，點選next，如果沒有自動帶入，請參考xampp 預設php.exe路徑
![](https://i.imgur.com/xxNDOgK.png) 
3. ### 本機不使用預設的proxy，所以直接選 next
![](https://i.imgur.com/9Kba167.png)
4. ### 最後按下 install 就完成囉
![](https://i.imgur.com/W7sehvY.png)
5. ### 打開 power shell(類似命令提示字元的工具)(windows + R 輸入powershell)，並輸入composer，確認是否安裝成功，看到大大的composer就代表成功囉。
![](https://i.imgur.com/691cve1.png)
--------------------------------------------------------------------
# 3. 建立 laravel專案
1. 打開power shell，透過cd {進入自己想要的資料夾}，進入你想放專案的位置
![](https://i.imgur.com/J1WWFBt.png)
2. 貼上以下指令，貼上去後，就會建立一個news的laravel專案，等跑完就可以代表安裝好了。
範例：`composer create-project laravel/laravel news` 
可以在{{專案名稱}}輸入自己的專案名稱，`composer create-project laravel/laravel 專案名稱
![](https://i.imgur.com/YhGyyE2.png)
![](https://i.imgur.com/p7GKcYS.png)
## 4. 下載VScode
### vscode安裝步驟：
1. ### 安裝程式直接點下一步到最後的安裝
2. ### 安裝vscode 與laravel php 相關模組
#### 點選左邊紅框的模組清單並搜尋以下模組並安裝：
* beautify：讓js, json, css, sass, html在vs code裡面會比較好看
* DotENV
* EditorConfig for VS Code
* GitLens — Git supercharged
* Kite AutoComplete AI Code: Python, Java, Go, PHP, C/C#/C++, Javascript, HTML/CSS, Typescript, React, Ruby, Scala, Kotlin, Bash, Vue, React
* Laravel Exter
* Laravel Artisan
* Laravel Blade Snippets
* Laravel Blade Spacer
* Laravel Extra Intellisense
* Laravel goto view
* Laravel Helpers
* Laravel Snippets
* laravel-blade
* laravel-goto-controller
* php cs fixer
* PHP Debug
* PHP Intelephense
* PHP IntelliSense
![](https://i.imgur.com/UjYuwt8.png)
↑點擊上圖的紅框，並搜尋以上模組，安裝完後即可進入下一步
3. ### 開啟news專案，點擊開左上角 File->open folder
![](https://i.imgur.com/kCwXXjn.png)
![](https://i.imgur.com/EI9cVke.png)
4. 點選news後，進入資料夾內，按下選擇資料夾
![](https://i.imgur.com/K41p1yU.png)
5. 恭喜完成，接下來就可以進入[laravel的世界](https://hackmd.io/h0gBZ4fLRGCnPGXxeHclRg)囉
![](https://i.imgur.com/8jMlfef.png)


## 下一步：[PHP Laravel基礎教學認識MVC架構：Model-View-Controller](https://hackmd.io/h0gBZ4fLRGCnPGXxeHclRg)
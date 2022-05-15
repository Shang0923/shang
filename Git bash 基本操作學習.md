# Git bash 基本操作學習

> Git 是一套Source code 版本管理的工具"程式"，學習使用版本管理工具是相當方便的。而且是免費的~

### First step: downloads.

下載網址:

https://git-scm.com/downloads

![image](https://user-images.githubusercontent.com/105298432/168477640-f7360187-a184-49ab-93cd-ca1930c33f01.png)


下載完成後會有 (1)Git bash (2)Git CMD 之後要來跑一些指令跟程式碼用Git bash.

### Second : 基本指令

> 這邊介紹我學的一些基本指令的輸入

* 在Git bash 裡輸入git，可查看 Git 版本. 還有一些常用 Git 指令如下

![image](https://user-images.githubusercontent.com/105298432/168477702-2d4263c0-8160-428e-ad64-2b4d8012da48.png)

* Git bash 常用指令

(1)可以查詢自己在哪個目錄的話，可以使用pwd，會顯示/c/Users/<你的使用者名稱>

![image](https://user-images.githubusercontent.com/105298432/168477735-1ff4f172-9f9d-4e01-96dd-853ea81442a1.png)

(2)列出資料夾底下所有的檔案可以用 ls (我的檔案太多了，就放一部分就好)
![image](https://user-images.githubusercontent.com/105298432/168477782-a6709707-6166-4efd-bb1a-1a201e03bb4a.png)

(3) 輸入clear 可以清除文字，就是我上面打的一堆可以清空~

(4) 進入資料夾的指令為cd，以下操作是我先進入Desktop(桌面)然後去找test這個資料夾

，用ls顯示裡面的資料，要回到上一層目錄的話，可以輸入cd ..
![image](https://user-images.githubusercontent.com/105298432/168477847-cdf31a02-cfba-476b-b242-ee7e4853cc45.png)

(5)用 touch 建立檔案or文字檔...都可以，以下為我用touch創的檔案跟文字檔

第一個是用touch gitbash 第二個是用touch gitbash.txt  (touch 後面接的文字是檔名)
![image](https://user-images.githubusercontent.com/105298432/168477909-e5c97437-3273-4853-b15a-7c23d553fa64.png)

(6) echo 文字輸出，然後把文字輸出儲存到我剛建立的txt檔~(echo "文字輸入" >檔名.txt)然後顯示檔案裡我們剛剛輸入的文字串~ (cat gitbash.txt )
![image](https://user-images.githubusercontent.com/105298432/168477933-a83a19ff-5ce6-4d33-b4fd-c8d0ce6ea916.png)

### Third : Git bash 執行指令

(1)

1. git init，將test初始化，變成git Repo，也就是變成git的倉庫。

2. git add test.txt 將test.txt的改變加入管理版本

3. 最後 git commit -m" add test.txt" 就完成囉，可能有些人輸入這段會跑出要求使用者輸入email跟user名稱，我自己在跑這個是沒這問題。不過還是可以輸入以下的文字來完成commit
![image](https://user-images.githubusercontent.com/105298432/168477956-ae97a877-0a26-4f52-8e6b-42ab6237ba99.png)

![image](https://user-images.githubusercontent.com/105298432/168477991-ec8c1178-3a6a-48b5-b120-3bbf4771c2c7.png)

(2)修改test.txt裡的內容(我原本裡面內容是test，我把他改成1213456(可以隨便打沒差))
輸入git commit -m"first chang"  (我想查看我做的更改會有什麼變化)...
變化就是加入了第二筆紀錄~
![image](https://user-images.githubusercontent.com/105298432/168478014-edef4b95-4329-445f-ab4f-a74f32b934f3.png)

(3)顯示過去紀錄: git log
可以看到所有的紀錄，但看不出改了什麼，每條紀錄都會有一個編碼(版號)，比方說 commit 4a59036.......很長的編碼，可以用commit show 編號..看你輸入流水號幾碼，就會顯示出那條變動的紀錄)
![image](https://user-images.githubusercontent.com/105298432/168478034-abf6afbe-411e-4049-a3a9-2feb855a9c24.png)

![image](https://user-images.githubusercontent.com/105298432/168478035-bdd4118e-f807-4c53-b6c2-536f82b2601b.png)

可以看到我原先的紀錄是test，改成1213456 

### 結論

這些大概是我自己稍微run一下基本指令的內容。就是好不習慣哈哈!不過還有很多指令跟其他東西可以玩，我遇到一個問題是複製貼上吧，就是要用滑鼠操控，鍵盤copy、paste好像是沒用的?就是這點蠻不方便的。其他都可以再去多多研究~

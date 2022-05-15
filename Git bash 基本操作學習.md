# Git bash 基本操作學習

> Git 是一套Source code 版本管理的工具"程式"，學習使用版本管理工具是相當方便的。而且是免費的~

### First step: downloads.

下載網址:

https://git-scm.com/downloads

![image-20220515205927729](C:\Users\商\AppData\Roaming\Typora\typora-user-images\image-20220515205927729.png)

下載完成後會有 (1)Git bash (2)Git CMD 之後要來跑一些指令跟程式碼用Git bash.

### Second : 基本指令

> 這邊介紹我學的一些基本指令的輸入

* 在Git bash 裡輸入git，可查看 Git 版本. 還有一些常用 Git 指令如下

![image-20220515210643133](C:\Users\商\AppData\Roaming\Typora\typora-user-images\image-20220515210643133.png)

* Git bash 常用指令

(1)可以查詢自己在哪個目錄的話，可以使用pwd，會顯示/c/Users/<你的使用者名稱>

![image-20220515211111921](C:\Users\商\AppData\Roaming\Typora\typora-user-images\image-20220515211111921.png)

(2)列出資料夾底下所有的檔案可以用 ls (我的檔案太多了，就放一部分就好)![image-20220515211352597](C:\Users\商\AppData\Roaming\Typora\typora-user-images\image-20220515211352597.png)

(3) 輸入clear 可以清除文字，就是我上面打的一堆可以清空~

(4) 進入資料夾的指令為cd，以下操作是我先進入Desktop(桌面)然後去找test這個資料夾

，用ls顯示裡面的資料，要回到上一層目錄的話，可以輸入cd ..![image-20220515212741756](C:\Users\商\AppData\Roaming\Typora\typora-user-images\image-20220515212741756.png)

(5)用 touch 建立檔案or文字檔...都可以，以下為我用touch創的檔案跟文字檔

第一個是用touch gitbash 第二個是用touch gitbash.txt  (touch 後面接的文字是檔名)

![image-20220515213328417](C:\Users\商\AppData\Roaming\Typora\typora-user-images\image-20220515213328417.png)

(6) echo 文字輸出，然後把文字輸出儲存到我剛建立的txt檔~(echo "文字輸入" >檔名.txt)然後顯示檔案裡我們剛剛輸入的文字串~ (cat gitbash.txt )

![image-20220515214105021](C:\Users\商\AppData\Roaming\Typora\typora-user-images\image-20220515214105021.png)

### Third : Git bash 執行指令

(1)

1. git init，將test初始化，變成git Repo，也就是變成git的倉庫。

2. git add test.txt 將test.txt的改變加入管理版本

3. 最後 git commit -m" add test.txt" 就完成囉，可能有些人輸入這段會跑出要求使用者輸入email跟user名稱，我自己在跑這個是沒這問題。不過還是可以輸入以下的文字來完成commit.![image-20220515215549612](C:\Users\商\AppData\Roaming\Typora\typora-user-images\image-20220515215549612.png)

   ![image-20220515220635726](C:\Users\商\AppData\Roaming\Typora\typora-user-images\image-20220515220635726.png)

(2)修改test.txt裡的內容(我原本裡面內容是test，我把他改成1213456(可以隨便打沒差))
輸入git commit -m"first chang"  (我想查看我做的更改會有什麼變化)...
變化就是加入了第二筆紀錄~

![image-20220515221032028](C:\Users\商\AppData\Roaming\Typora\typora-user-images\image-20220515221032028.png)

(3)顯示過去紀錄: git log
可以看到所有的紀錄，但看不出改了什麼，每條紀錄都會有一個編碼(版號)，比方說 commit 4a59036.......很長的編碼，可以用commit show 編號..看你輸入流水號幾碼，就會顯示出那條變動的紀錄)![image-20220515221407257](C:\Users\商\AppData\Roaming\Typora\typora-user-images\image-20220515221407257.png)

![image-20220515221553320](C:\Users\商\AppData\Roaming\Typora\typora-user-images\image-20220515221553320.png)

可以看到我原先的紀錄是test，改成1213456 

### 結論

這些大概是我自己稍微run一下基本指令的內容。就是好不習慣哈哈!不過還有很多指令跟其他東西可以玩，我遇到一個問題是複製貼上吧，就是要用滑鼠操控，鍵盤copy、paste好像是沒用的?就是這點蠻不方便的。其他都可以再去多多研究~
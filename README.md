# Git

## 指令
#### 設定使用者：
* git config --list            查看git的設定
* git config --global user.name "Your Name"
* git config --global user.email "your@gmail.com"
* git remote add origin <GitHub repository URL>   

#### 新增 repository：
* mkdir my_git                 建立一個名為 my_git 的資料夾
* cd my_git                    切換至 my_git 資料夾
* git init                     初始化這個目錄，讓git對這個資料夾進行版本控制，建立git repository檔案庫
* ls                           看一下資料夾內有什麼

#### 增加檔案：
* git status                   顯示目前工作目錄的檔案狀態
* git add FILE                 把FILE加入暫存區
* git commit -m " "            留下 commit 訊息
* git log                      查看提交 commit 的歷史記錄
* git push -u origin master    將本地檔案庫上傳 
#### 上传github
1. 先建储存库  会弹出命令条件

### 如何上传

-   进入你要上传的 那个文件夹 的内部 右键 点击 git bash here
-   git init 初始化这个文件(本地仓库)) 成功的标志 有一个 .git 的隐藏文件 (仓库只需初始化一次)
-   git add . (把这个仓库里的文件 添加到 暂存区)
-   git commit -m'提交描述' (把刚才新添加到暂存区的文件 提交到 本地仓库)

-   把本地仓库 同步更新到 远程 github 仓库
-   第一次 需要 将本地仓库 和 远程仓库 建立 联系 (本地仓库只能和一个远程仓库 建立联系)

    -   git remote add origin https://github.com/metro2703/z-note.git
    -   (git remote add origin 仓库地址)

-   git push origin master (同步代码 )

#### 第二次上传

工作区===>暂存区====>提交到本地仓库===>同步到远程仓库

-   git add .
-   git commit -m'提交信息'
-   git push origin master
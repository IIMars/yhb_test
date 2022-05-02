- 先按照这个网址配置ssh，并创建一个仓库

 [Git 远程仓库(Github) | 菜鸟教程 (runoob.com)](https://www.runoob.com/git/git-remote-repo.html) 



- 创建一个文件夹，然后单击右键打开git bash here

  - 先将仓库拉下来

  - ```
    git clone https://github.com/用户名/仓库名.git
    ```

  - 进入到拉下来的仓库的文件夹中

    ```
    cd 文件夹名字
    ```

  - 将要上传的文件复制到该文件夹下，然后将文件添加到缓冲区

    ```
    git init	#初始化仓库
    git add *	#将所有文件添加到缓冲区，如何只是添加某个文件，只需要git add 文件名
    ```

  - 将缓冲区的内容提交并push到远程仓库

    ```
    git commit -m "这是提交信息随便填"
    git branch -M main		#如果命令框的最后面是（master）需要这句，如果是（main）不需要这句
    git remote add origin https://github.com/用户名/仓库名.git
    git push -u origin main		#提交到远程仓库
    ```

    


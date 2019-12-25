###Git Test
#### **github 创建项目**
1. 在github 创建一个项目 如：https://github.com/fankf/gittest.git
2. 本地拉取 idea File -> New -> Project from Version Controll -> Git
3. 填入 github 项目地址，确定  new windows 展开项目

#### **本地项目推送到github**
有时候会有在本地创建一个项目，或者复制了其他项目的代码，需要推送到 github
1. 本地创建一个项目
2. 创建同名的github项目，可以查看github 下说明，例如：

    echo "# gitt" >> README.md
    git init
    git add README.md
    git commit -m "first commit"
    git remote add origin https://github.com/fankf/gitt.git
    git push -u origin master

    在 本地项目根目录下执行，就可以了

#### **本地创建项目但是和 github下有冲突**
例如：readme 文件已经有了，这个时候需要复制其他项目的代码
1. 先拉取远程 github 项目代码
2. 把需要推送远端的代码复制到本地项目下
3. 使用idea 打开项目，会发现新的未提交的文件是红色的
    例如 复制 README.md 后的文件 README-副本.md
    此时正常提交代码，并推送到远程。
4. 有远程的代码先拉取代码即可。



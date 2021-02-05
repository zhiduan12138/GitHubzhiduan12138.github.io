1.git add  命令 git add -A(git add .)
2.git commit  命令 git commit -m"本次提交的修改的备注"
    如果只是修改文件，没有创建文件 可以使用 
     git commit -am"本次提交的修改的备注"来合并前面两个步骤
3.git push
   第一次提交到本分支 git push origin main
       oringin是远程仓库的默认名称，main是我们的分支名称（主分支） 
    第2-n次提交到本分支 git push
    提交到其他分支  git push origin b
解决代码冲突  git pull

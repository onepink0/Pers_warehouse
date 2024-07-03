# User

## 仓库关联

- 从GitHub拉取到本地仓库`git pull origin master`

- 从本地仓库发布到GitHub

  ```
  git add .
  git commit -m "此处写提交的备注"
  git pull origin master
  ```

  

## 本地和远程仓库的比较
- 更新本地的远程分支`git fetch origin`
- 本地与远程的差集 :（显示远程有而本地没有的commit信息）
`git log master..origin/master`
-  查看差异`git diff --stat master origin/master`
   **来源[git比较本地仓库和远程仓库的差异](https://blog.csdn.net/mazhongjia/article/details/106071316)**

---


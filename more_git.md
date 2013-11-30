## 分支管理方式
<img src="http://www.juvenxu.com/wp-content/uploads/2010/11/git-branch-1.png" alt="一个成功的分支模型" />

* master 
* develop
* feature_branch
* hot_fix

### 分支合并
Fast-forward

### tags
git push origin develop --tags 
将tags 同时推送到服务器

### 保护master
窝们近期会将一些项目的master分支保护起来，在推送时候需要向master做一个pull request，然后窝们帮你闷合并进去，在这个过程中做一下 code review

* 多用 issue 系统
* 使用有意义的提交日志，避免“修正了bug”这种

## 别的啥的
### rm 已经放入缓存的ignored 文件

git rm --cached . -r
git add --all

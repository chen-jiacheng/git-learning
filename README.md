# git-learning
git 学习


## 第一种流程 - 本地无代码
```bash
git clone git@github.com:chen-jiacheng/mozi.git
git fetch
git branch -a
git checkout -b <local> origin/<remote>
git add .
git commit -m 'msg'
git push
git pull
```

## 第二种流程 - 本地无代码
```git
git init
git remote add origin git@github.com:chen-jiacheng/mozi.git
git fetch
git checkout -b <local> origin/<remote>
git add .
git commit -m 'msg'
git push
git pull
```
## 第三种流程 - 本地有代码
```git
git init
git remote add origin git@github.com:chen-jiacheng/mozi.git
git fetch
git merge --allow-unrelated-histories origin/test1
git push origin test2
git branch -u origin/test2 test2
git pull
```

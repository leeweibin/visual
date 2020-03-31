# git使用手册

### 1. 常规使用

0. 设置

```
git config --global user.name xxx

git config --global user.email xxx@gmail.com
```

查看配置

> ```
> git config list
> ```

1. 初始化

第一次从本地建立工程的代码仓库，或者去github克隆代码到本地

（1）在本地建立代码仓库

```
git init
```

（2）从github克隆到本地

```
git clone https://github.com/leeweibin/visual.git 
```

2. 一般情况下，首先远程把最新代码拉到本地，建立分支

```
git checkout -b feature_x
```

3. 在分支代码的基础上进行代码编写，查看状态

```
git status
```

  将代码加到文件缓冲区

```
git add .
```

查看代码变动情况

```
git diff
```

将代码提交到缓冲区

git commit -m "this is commention"

将代码提交到远程代码仓库

```
git push
```




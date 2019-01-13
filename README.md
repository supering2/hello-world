

### 给 github 配置公钥

```
cd ~/.ssh
cat id_rsa.pub
```
然后复制命令行的内容

去 github setting 找到 SSH KEY, 加进去


### 从 github 上 clone 代码

```
git clone git@github.com:supering2/hello-world.git
```

### 查看git状态

```
git status
```

## 工作区---暂存区---本地仓库 -----远程仓库
### 工作区--->暂存区
```
git add .
```

### 暂存区--->本地仓库
```
git commit -m 'msg'
```

### 本地仓库--->远程仓库
```
git push
```

### 拉取代码
```
git pull
```
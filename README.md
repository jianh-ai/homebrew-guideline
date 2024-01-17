# homebrew-guideline
intruduction to homebrew
---
## 1.安装

国内源：
```
/bin/zsh -c "$(curl -fsSL https://gitee.com/cunkai/HomebrewCN/raw/master/Homebrew.sh)"
```
国外源：
```
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
```

启动台 -> 打开terminal
1. vim ~/.zshrc
2. 输入单字母i，表示进入输入模式insert
3. export PATH=/xxx/xxx/.../bin:$PATH
4. 按esc
5. 输入`:wq`,注意是三个字符而不是两个
6.  source ~/.zshrc

卸载
```
/bin/zsh -c "$(curl -fsSL https://gitee.com/cunkai/HomebrewCN/raw/master/HomebrewUninstall.sh)"
```
---
## 2.使用
1.使用homebrew安装程序
`brew install`

2.使用homebrew卸载程序
`brew uninstall`

3.查询homebrew可用程序
`brew search`

4.查询homebrew已安装应用
`brew list`

5.查询homebrew版本
`brew -v`

---
## 3.homebrew的存储路径
`/opt/homebrew/Cellar`

一般来说直接访达是无法直接查询的，得通过“聚焦搜索”才能搜寻到

---
### 4.使用问题
1.对于安装python存在的问题(已解决)
> zsh:command not found: python > 
原因：homebrew安装python并不会为其添加环境变量
解决：暂不清楚
参考文章(https://blog.csdn.net/baidu_30506559/article/details/127386192)


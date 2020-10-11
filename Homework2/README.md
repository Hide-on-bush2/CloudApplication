# Homework2

## 准备工作

昨晚`homework1`之后发现执行`go install github.com/Hide-on-bush2/hello`之后会产生以下错误信息：

![](./images/1.png)

因该是安装其他插件的时候将配置搞错了，之后搜到[这个网站](https://stackoverflow.com/questions/61921282/golang-cannot-find-module-providing-package-package-name-working-directory-is)，然后执行下面这条命令就可以了 

```
go env -w GO111MODULE=auto
```


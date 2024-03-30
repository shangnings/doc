
# 使用文档
https://gohugo.io/getting-started/quick-start/

# 简单使用
## 添加主题
```shell
git submodule add https://github.com/theNewDynamic/gohugo-theme-ananke.git themes/ananke
修改 hugo.toml
```

## 添加文档
```shell
hugo new content posts/my-first-post.md
```

## 本地调试
```shell
hugo server --buildDrafts
hugo server -D
```


## 打包
```shell
hugo -d docs
```

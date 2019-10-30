# 网站发布 deploy

## 发布到github pages
github pages是github提供的一个静态页面托管功能，可以帮助github的用户无须租买云服务器等网络空间，即可在互联网上构建静态站点

## 方案1：直接推送
参见 https://www.jianshu.com/p/3d03ab330df5

> 最新的github pages 似乎不再支持git-pages分支，但仍然支持 master 分支的 /docs 目录，因此请将生成后的文档放置于 /docs 目录

## 方案3：使用 gh-pages 工具包

安装 gh-pages 工具包
```
npm install g gh-pages
```

然后输入以下指令
```
gh-pages -d _book
```

该命令会将`_book` 目录下的所有html文件推送到 gh-pages 分支

## 方案3：使用 gulp 构建
参见 https://gldraphael.com/blog/publishing-gitbook-to-github-pages/
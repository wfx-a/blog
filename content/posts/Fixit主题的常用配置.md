+++
title = 'Fixit主题的常用配置'
date = 2025-10-18
categories = ['博客'] 
tags = ['hugo', 'Fixit']
+++

## 1 下载与使用

1. [Gitee 镜像仓库](https://gitee.com/lruihao/FixIt)，下载zip
2. 解压到themes文件夹
3. hugo.toml中配置theme

![20251018180152](https://blog-1300845590.cos.ap-shanghai.myqcloud.com/img/20251018180152.png)

## 2 配置

`/hugo.toml`中其他配置，参考[fixit主题文档](https://fixit.lruihao.cn/zh-cn/)

### 2.1 中文配置
  
```toml
defaultContentLanguage = "zh-cn"
languageCode = "zh-CN"
languageName = "简体中文"
```

### 2.2 目录配置

```toml
[menu]
    [[menu.main]]
        identifier = "archives"
        parent = ""
        pre = ""
        post = ""
        name = "归档"
        url = "/archives/"
        title = ""
        weight = 1

        [menu.main.params]
            icon = "fa-solid fa-archive"        # fontawesome icon
            divided = false

    [[menu.main]]
        identifier = "categories"
        parent = ""
        pre = ""
        post = ""
        name = "分类"
        url = "/categories/"
        title = ""
        weight = 2

        [menu.main.params]
            icon = "fa-solid fa-folder-tree"
```

### 2.3 github角

```toml
[params]
    [params.githubCorner]
        enable = true
        permalink = "https://github.com/wfx-a"
        title = "Go to My Git"
        position = "left"
```

### 2.4 阅读进度条
  
```toml
[params]
    [params.readingProgress]
        enable = true
        start = "left"
        position = "top"
        reversed = false
        light = "black"     # 浅色主题进度条颜色
        dark = "green"      # 深色主题进度条颜色
        height = "2px"
```

# Hugo静态博客搭建


## 1. 下载hugo，配置环境变量

`hugo version`验证安装成功

## 2. 创建xxx目录

`hugo new site xxx`

![20251018000503](https://blog-1300845590.cos.ap-shanghai.myqcloud.com/img/20251018000503.png)

## 3. 创建文章

`hugo new posts/Article01.md`

将在content/posts/下创建Article01.md

![20251018001323](https://blog-1300845590.cos.ap-shanghai.myqcloud.com/img/20251018001323.png)

Article01.md默认内容如下

![20251018001358](https://blog-1300845590.cos.ap-shanghai.myqcloud.com/img/20251018001358.png)

修改draft为false，表示不是一个草稿，否则不会在博客中显示

## 4. 下载主题

[Hugo官网主题](https://themes.gohugo.io/)

将主题下载到themes文件夹

用git clone，或下载压缩包

`git clone https://github.com/gohugoio/gohugoioTheme.git themes/gohugoioTheme`

![20251018164916](https://blog-1300845590.cos.ap-shanghai.myqcloud.com/img/20251018164916.png)

## 5. 配置主题

修改hugo的配置文件`hugo.toml`

增加theme行，内容为themes文件夹下主题的文件夹名

![20251018004649](https://blog-1300845590.cos.ap-shanghai.myqcloud.com/img/20251018004649.png)

## 6. 运行server

1. `hugo server`
2. 打开本地路径`http://localhost:1313`

## 7. 常用命令汇总

- 新建博客目录 `hugo new site xxx`
- 新建文章 `hugo new posts/xxx.md`
- 渲染并本地服务器预览 `hugo server`
- 渲染 `hugo`

## 8. 发布

本地搭建好的博客如何发布到网上，让大家用域名访问？hugo静态网页部署到服务器


---

> 作者: wfx  
> URL: http://localhost:1313/posts/hugo%E9%9D%99%E6%80%81%E5%8D%9A%E5%AE%A2%E6%90%AD%E5%BB%BA/  


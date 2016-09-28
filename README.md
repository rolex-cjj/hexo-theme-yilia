hexo-theme-yilia
================

Yilia 是Litten为 [hexo](https://github.com/tommy351/hexo) 2.4+制作的主题。我稍微做了一点点调整。
崇尚简约优雅，以及极致的性能。 你可以点击 [我的博客](https://rolex-cjj.github.io/) 查看效果。           

## 关于主题：             

###一、使用

#### 安装

``` bash
$ git clone https://github.com/rolex-cjj/hexo-theme-yilia.git themes/yilia
```

#### 配置

修改hexo根目录下的 `_config.yml` ： `theme: yilia`

#### 更新

``` bash
cd themes/yilia
git pull
```

##二、配置

主题配置文件在主目录下的`_config.yml`：

```
# Header
menu:
  首页: /
  归档: /archives
  关于: /about

# SubNav
subnav:
  github: "#"
  weibo: "#"
  rss: "#"
  zhihu: "#"
  #douban: "#"
  #mail: "#"
  #facebook: "#"
  #google: "#"
  #twitter: "#"
  #linkedin: "#"

rss: /atom.xml

# 是否需要修改 root 路径
# 如果您的网站存放在子目录中，例如 http://yoursite.com/blog，
# 请将您的 url 设为 http://yoursite.com/blog 并把 root 设为 /blog/。
root: 

# Content
excerpt_link: 阅读全文
fancybox: true
mathjax: true

# 是否开启动画效果
animate: true

# 是否在新窗口打开链接
open_in_new: true

# Miscellaneous
google_analytics: ''
favicon: /favicon.png

#你的头像url
avatar: https://xxx.jpg
#是否开启分享
share_jia: false
share_addthis: false
#是否开启多说评论，填写你在多说申请的项目名称 duoshuo: duoshuo-key
#若使用disqus，请在博客config文件中填写disqus_shortname，并关闭多说评论
duoshuo: true
#是否开启云标签
tagcloud: true

#是否开启友情链接
#不开启——
#friends: false
#开启——
friends: 
  Qi's Blog: https://nextinnovationucas.github.io/
  
#是否开启“关于我”。
#不开启——
aboutme: false
#开启——
#aboutme: 我只是一个想努力提高自己的程序渣……
```
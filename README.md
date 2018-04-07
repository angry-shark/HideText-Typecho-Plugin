# HideText-Typecho-Plugin
为文章添加肉眼不可见的额外信息，可用于追踪未授权转载行为

[关于零宽空格](https://zh.wikipedia.org/wiki/%E9%9B%B6%E5%AE%BD%E7%A9%BA%E6%A0%BC)

![Screenshot](https://img.imjad.cn/images/2018/04/07/Screenshot-20180407211223-1070x763.png)

## 安装方法
Download ZIP, 解压，将 HideText-Typecho-Plugin-master 重命名为 HideText ，之后上传到你博客中的 `/usr/plugins` 目录，在后台启用即可

可前往设置界面选择是否启用自动插入隐藏文本和自定义内容

## 使用方法
在文章里想要插入隐藏文本的地方书写`<!--ap-->`即可

### 自定义内容模板字符串
```
{siteTitle} 网站名
{title} 文章标题
{author} 文章作者
{permalink} 文章链接
{time} 文章发布日期
```

## Thanks
[zero-width-detection](https://github.com/umpox/zero-width-detection)

## LICENSE

MIT © [journey.ad](https://github.com/journey-ad/)
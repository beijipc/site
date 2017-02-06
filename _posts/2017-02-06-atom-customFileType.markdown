---
layout: post
title:  "Atom定制文件类型"
date:   2017-02-06
categories: IDE
---
微信小程序里的wxml和wxss是个奇葩的产物，在Atom里不认识这个文件类型，代码无法着色。通过以下方法可以为atom定制支持。

- 打开Atom - Config...
- 在里面添加如下代码：

{% highlight CoffeeScript %}

"*":
  core:
    customFileTypes:
      'text.html.basic': ['wxml']
      'source.css': ['wxss']

{% endhighlight %}

现在，回到你的编辑器。看到wxml和wxss是不是有着色了。

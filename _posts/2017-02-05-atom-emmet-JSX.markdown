---
layout: post
title:  "Emmet支持JSX"
date:   2017-02-05
categories: IDE
---
一直习惯使用atom，因为它有个强大的插件社区能帮助我更高效完成工作。emmet就是其中之一，直到有一天JSX的出现，让我感到困苦，还好Google总能给我带来希望。

- 打开Atom - Keymap
- 在里面添加如下代码：

{% highlight CoffeeScript %}
'atom-text-editor[data-grammar~="jsx"]:not([mini])':
  'tab': 'emmet:expand-abbreviation-with-tab'
{% endhighlight %}

现在，回到你的编辑器。在JSX中可以找回emmet带来的快感。

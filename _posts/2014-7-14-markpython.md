---
date: 2014.7.14
layout: post
title: python知识整理
categories: python
tags:  python 软件
---
不知不觉做python开发也有一年多的时间了，一直也没有时间整理基础知识，现在好好整理以下:
>* 装饰器      

范例：  

范例：  

```python      
#!/usr/bin/python
# -*- coding: utf-8 -*-

def makebold(fn):
    def wrapped():
        return "<b>" + fn() + "</b>"
    return wrapped

def makeitalic(fn):
    def wrapped():
        return "<i>" + fn() + "</i>"
    return wrapped

@makebold
@makeitalic
def hello():
    return "hello world"

print hello()
```
输出结果：
```restlt 
<b><i>hello world</i></b>

```


## import this   
作为一个pythoner必须知道的[The Zen of python]，python设计的指导原则[PEP20]
``` zen
The Zen of Python, by Tim Peters

Beautiful is better than ugly.
Explicit is better than implicit.
Simple is better than complex.
Complex is better than complicated.
Flat is better than nested.
Sparse is better than dense.
Readability counts.
Special cases aren't special enough to break the rules.
Although practicality beats purity.
Errors should never pass silently.
Unless explicitly silenced.
In the face of ambiguity, refuse the temptation to guess.
There should be one-- and preferably only one --obvious way to do it.
Although that way may not be obvious at first unless you're Dutch.
Now is better than never.
Although never is often better than *right* now.
If the implementation is hard to explain, it's a bad idea.
If the implementation is easy to explain, it may be a good idea.
Namespaces are one honking great idea -- let's do more of those!
```


##PEP8 python编码风格指南

请参考[PEP8中文翻译]以及[python code style]


##文档
推荐[sphinx]名字有点坑，刚开始跟另一个搜索功能的sphinx混了。
[深度阅读]



今天先写这些，以后不定期更新吧

[The Zen of python]:http://legacy.python.org/dev/peps/pep-0020/
[PEP8中文翻译]:https://code.google.com/p/zhong-wiki/wiki/PEP8
[python code style]:http://docs.python-guide.org/en/latest/writing/style/
[sphinx]:http://sphinx-doc.org/
[深度阅读]:http://docs.python-guide.org/en/latest/writing/documentation/


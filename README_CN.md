# 这项目是借助react框架写的
你可以通过访问这个[演示链接](http://101.132.112.146)来查看效果，点击灰色的部分可以返回
我非常喜欢GROWLANSER这款游戏，所以我尝试在web上复现这个游戏的UI菜单动画。
这是我第二次发布这个工程，因为第一次我的仓库名称拼写错了……

虽然是用了react，但是我并不太擅长使用react，因此这里绝大多数的函数都是原生语法实现的。

# 整个项目的组成
在src文件夹中：
- "style"文件夹内定义了网页中各个部分的样式；
- "ts_tool"文件夹中包括了众多的函数；
    - "data_ajax"中定义了前后端的交互；
    - "public_mod"中定义了一些公用的类和方法；
    - "ui_views"中定义了所有的界面动画； 

# 一些问题-20240628
1. 我缺少能够展示的东西，所以我只能做出一个大体的架子；
2. leftform中我似乎很难再添加三级菜单项目了，即使我已经留出来足够的位置；
3. 目前对于菜单项目数量支持比较固定，修改起来比较麻烦；
4. 异步动画我只支持8个动画的异步，如果想要实现更多的异步我要彻底重写我的命名空间GL1Box；
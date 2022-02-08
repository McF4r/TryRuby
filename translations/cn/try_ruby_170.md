---
lang:   CN
title:  元素
answer: ^(12|35|47)$
load:   ticket = [12, 47, 35]
ok:     完成
error:  差一点
---

我们已经把在变量ticket里的彩票数字排序了，那怎么再把它们拿出来呢？

我们已经知道了可以用 __max__ 来得到最大的值。
同样的，你可以
用 __first__ 或者 __last__ 来得到第一个或是第二个元素。
可如果你想要一个特定的值呢？

### [ ]
Ruby使用方括号[ ]来选择元素
方括号在Ruby中非常常见
它们就像用来瞄准目标的瞄准器
意味着“__我要去寻找__”，准备，瞄准。

让我们输出我们全部的彩票数字

    puts ticket[0]
    puts ticket[1]
    puts ticket[2]

我们为什么使用 [0], [1], [2]?

而不是 [1], [2] 和 [3]? 难道这是来自日本的神秘佛教计数法吗？不, 我们computer people就是喜欢从0开始数。不仅仅是Ruby，大多数编程语言都从0开始数。

> 一个小提示: 你可以按 __Copy__ 按钮，把示例代码复制到编辑器中。
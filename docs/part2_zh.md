
第 2部分
从基础构件开始：编程范式
任何软件架构的实现都离不开具体的代码，所以我们对软件架构的讨论应该从 
第一行被写下的代码开始。
1938年，阿兰•图灵为现代计算机编程打下了地基。尽管他并不是第一个发明 
可编程机器的人，但却是第一个提出“程序即数据”的人。到 1945年时，图灵已经 
在真实计算机上编写真实的、我们现在也能看懂的计算机程序了。这些程序中用到 
了循环、分支、赋值、子调用、栈等如今我们都很熟悉的结构。而图灵用的编程语 
言就是简单的二进制数序列。
从那时到现在，编程领域历经了数次变革，其中我们都很熟悉的就是编程语言 
的变革。首先是在20世纪40年代末期出现了汇编器(assembler), 它能自动将一 段程序转化为相应的二进制数序列，大幅解放了程序员。然后是1951年，Grace Hopper发明了 A 0 ,这是世界上第一个编译器(compiler)。事实上，编译器这个名 字就是他定义和推广使用的。再接着就到了 1953年，那一年FORTRAN面世了(就 
在我出生的第二年)。接下来就是层出不穷的新编程语言了—— COBOL、PL/1、 
SNOBOL、C、Pascal> C++、Java 等等,不胜枚举。架构整洁之道
除此之外，计算机编程领域还经历了另外一个更II大、更重要的变革,那就果 
编程范式（paradigm）的变.迁。编fV范」弋JI i fl'J ）ii卅用的编7 j 模式， 具体的编稈曽 言关系相对较小。这吐范」弋会吿诉你应该许什么时候采川什么样的代码结构 
今天,我们也一共只有三个编程范式,而且未来几乎不可能再岀现新的,接F來我 
们就看一下为什么。
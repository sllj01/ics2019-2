# PA1

I chose character x86 ISA before, though I hope to experience what is elegent ISA(RISC-V). As soon as I finished it, I will challange myself on mips32.

-----

计算机可以没有寄存器吗?

当然可以，编程模型有很多种，可以参考这一篇[文章](https://segmentfault.com/a/1190000012672028)。如果没有寄存器的话就用栈来替代咯。当然，它会和基于栈的编程模型（Stack-based programming）有一定相似之处。

-----

-----

计算机的状态模型

对于数字电路来说，它的状态可以用一个数列来表示：$a_1, a_2, ..., a_n$。我们有两种改变状态的方式：

1. 仅由内部逻辑改变，也就是[摩尔型有限状态机（Moore machine）](https://zh.wikipedia.org/wiki/%E6%91%A9%E5%B0%94%E5%9E%8B%E6%9C%89%E9%99%90%E7%8A%B6%E6%80%81%E6%9C%BA)，其输出仅由当前的状态决定。
2. 除内部逻辑外，外部输入也会影响当前状态，也就是[米利型有限状态机（Mealy machine）](https://zh.wikipedia.org/wiki/%E7%B1%B3%E5%88%A9%E5%9E%8B%E6%9C%89%E9%99%90%E7%8A%B6%E6%80%81%E6%9C%BA)

对于计算机而言，它不过是个更复杂的数字电路，和上面并没有本质区别。

-----

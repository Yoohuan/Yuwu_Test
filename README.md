首先说明一下三个项目对应的文件夹
1. yunwu_test_1 为万年历项目
2. ContactBook 为通讯录项目
3. Calculator 为计算器项目


然后是三个项目的完成情况:

万年历：
该项目主要运用的知识为循环语句和分支语句，通过运用数学逻辑计算打印月份的首日为星期几，再依次打印日期；
设计了具有开始和结束功能的菜单；
对输入数据的合法性有一定的检验能力，如菜单选择时没有正确选择，输入的月份为13、14等不合法月份或日期，均会有错误提示；
日历打印时设计了简单的界面，使界面看起来更清晰美观；

通讯录：
该项目为典型的数据管理系统，因为需要增删查改等功能，因此使用链表优于数组；
项目的增删查改功能已实现；
同时程序运行时的数据会在程序正常结束（菜单界面选择exit）时保存在文档文件中，实现数据持久化；
还未能实现排序、模糊查找、输入内容合法性检查的功能；

计算器：
该项目主要运用的知识为数组以及ASCII码表，把输入的通过ASCII码值运算判断算数符号位置，再使用四则运算法则进行数据运算；
具有一定的表达式合法性检验功能；
括号功能仅仅能使用单层的括号，括号内嵌套括号时输出值会出错；


最后总结一下近期的学习情况：
    在收到考核内容之后，首先完成了万年历的制作，该项目也是完成度最高的项目。完成之后进行的是C语言的后续学习，相继学习了
数组，结构体以及指针的内容，至此C语言的基础知识已经基本完成学习。需要说明的是，C语言的操作符部分并没有进行学习，因为我
认为操作符在日后编程过程中不断地使用，理解就会慢慢提升，因此没有刻意学习。在考虑到通讯录项目需要使用链表以及数据持久化
的知识后，又进行了C语言链表以及文件操作知识的学习，并完成了通讯录和计算器项目的制作。设计通讯录排序、模糊查找以及输入内
容合法性功能时，有想过使用ASCII码值来实现，但是考虑到时间成本，最后选择了省下时间来学习数据结构和算法。而在计算器括号功
能实现时，在完成后才发现函数的嵌套使用有一定的逻辑错误，因此只能实现单层括号的计算，同样的也是因为考虑时间成本没有进行
修改。目前的学习进度正在学习数据结构和算法的内容。
    另外，需要说明的是，考核题目中的项目编写时都有在一定程度上参考CSDN的项目、算法思维，再进行编写。因为我认为，在学习
程中遇到问题时能够检索网上的知识并正确运用也是一种学习能力的体现，并且这个过程中还可能会有些意想不到的额外收获。

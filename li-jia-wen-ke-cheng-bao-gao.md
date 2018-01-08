

**基于机器人的实践方法**

**个人课程报告**



课程名称：基于机器人的实践方法

学生：李嘉文

学院：数学与统计学院

学号：320170928361

班级：2017级数学类一班



**《基于机器人的实践方法》个人课程报告**



**内容摘要：**本课程通过对Google发布的完全可视化的编程语言Google Blockly的学习，先从理论层面深入了解运用Blockly语言，再从实践层面通过Blockly语言操控机器人小车完成迷宫。由浅及深，循序渐进；从理论到实践，多方位学习。本文即依据课程学习的方法，完成该选修课程报告。

**关键词：**Blockly编程 机器人小车 迷宫



**正文部分**

**一、关于Blockly**

**1、一种基于网页的可视化程序**

Google Blockly是基于网页的可视化编程工具库。用户可以以离线或者在线的方式在Windows、Linux、MC和Androi平台上的浏览器端进行编程操作。可以使用计算机端、手机或平板移动端进行随时随地的完成编程设计，教学编程方式多种多样。

**2、多种开发语言环境库**

Blockly基于图形化编程设计可以导出Javascript、Python、PHP、Lua、art等多种语言。通过图形化编程完成程序设计，在Blockly中有一个类似语言转换器的工具箱，可以将图形化编程语言转化成多种编程语言代码。用图形化编程方式去理解多种程序语言。

**3、开源的自定义编程环境**

Blockly是开源的编程工具，用户可以根据自己编程的特点要求，对Blockly工具箱进行自定义设计。同时，Blockly开发工具能让用户自定义块导出至工具箱，并在工作区工厂完成对代码的封装。如图所示。

![](file:///C:/Users/lijia/AppData/Local/Temp/msohtmlclip1/01/clip_image002.jpg)

**二、理论课的求实进取**

由于Blockly相对陌生，老师在此之前先进行Blockly基础知识的讲解及一些应用，如：Blockly的数据类型，Blockly的开发工具，还有众多犹如循环，条件等算法。虽然很多都与数学C语言专业课所学的类似，但唯有不同之处才是其精髓之处。犹记得一次设计是否为素数的程序，其Blockly语言如下图所示：

![](file:///C:/Users/lijia/AppData/Local/Temp/msohtmlclip1/01/clip_image004.jpg)![](/assets/P8KL5$JJ0~M7KP~3VR4OC~K.png)

**图一**



从图中可看出，这是一个典型的包括循环、条件语句等结构的一个程序，但由于在上到这节课之前，自己还不熟知程序的语句结构，所以当时做这道题也花了不少时间。

再如一节课上老师提供给我们的Blockly小游戏中，如图所示：



![](file:///C:/Users/lijia/AppData/Local/Temp/msohtmlclip1/01/clip_image006.jpg)![](/assets/%28B8QX]9B3DA_S%29COQ8`V~GN.png)

**图二**



虽然这一关看起来很简单，但是到了下一关，

![](file:///C:/Users/lijia/AppData/Local/Temp/msohtmlclip1/01/clip_image008.jpg)![](/assets/PMH@}2{}F70VNMHD@QY5{WR.png)

**图三**



就会发现该程序运用了大量的循环语句，可见Blockly里也需要程序员不断的对其进行审查，测试，才能得出最佳可行的程序。这也是我在理论课所学到的经验。



**三、实践课的不断摸索**

实践课于第16周进行，整个过程充满挑战与收获。课程分为两个阶段，第一阶段是安装小车。![](file:///C:/Users/lijia/AppData/Local/Temp/msohtmlclip1/01/clip_image002.jpg)

![](/assets/L_3CQGQ{Z~T16K]V6U65HTD.png)

**图四**

![](/assets/V8D8N_2SNACIMC%299PIXS8%W.png)

![](file:///C:/Users/lijia/AppData/Local/Temp/msohtmlclip1/01/clip_image004.jpg)

**图五**

![](file:///C:/Users/lijia/AppData/Local/Temp/msohtmlclip1/01/clip_image006.jpg)![](/assets/0O{Y%28[N}UI_91O3@3ZDWY7P.png)

**图六**

![](file:///C:/Users/lijia/AppData/Local/Temp/msohtmlclip1/01/clip_image008.jpg)![](/assets/EC5]NIN5T9~1%28TUU0SBGJZ3.png)

**图七**



正如上图中所示，整个安装小车过程中，受到了不少的阻力，比如降压器，传感器的安装，由于螺丝不足等一些客观因素，无法做到像实例中的小车那样完美，但是小组成员仍不懈努力，在组长李曦云学长的带领下，克服重重困难，终于将小车组装完毕。

而第二阶段的编程可谓是费了九牛二虎之力。刚开始的我们以为只要做到简单的离障碍物一定距离就转弯的程序就可顺利有效的完成比赛，没想到的是，因为左右两轮电机的功率问题，无法实现两轮转速一致，导致小车无法简单的达到走直线的效果。我们曾尝试利用更改左右两轮转速，但发觉这种方法并不可行，原因在于小车转弯角度无法完全达到90°，使得小车总是在的一个岔口撞墙。于是经过老师的询问，我们采用了利用与墙面距离的算法，从而达到小车一直与墙面有固定距离的效果。此效果虽理论可行，但每次实际操作中，总是会有超过距离时会持续打转的情况。在百思不得其解的情况下，经过学长和老师的辅导，我们发现，由于右轮一定程度上干扰了有传感器的信号接收，所以只需将右传感器的位置移到前方便可消除之前的问题。果不其然，虽然最后跌跌宕宕的驶向了终点，但一直被困扰我们的问题在一瞬间被解决的兴奋和小车终于跑向终点时激动的心情一直伴随着我们直到课程结束。

下图为小组成员完成任务后的照片

![](file:///C:/Users/lijia/AppData/Local/Temp/msohtmlclip1/01/clip_image010.jpg)![](/assets/J6~IB8BOEYTP3[ZR5I]DUUL.png)



这次实践课的感触很多，但要数最深的，还是懂得了理论与实践相结合的道理。不论是在数学方面的学习还是计算机方面的学习，都需要经过不断的思考，检查，审核和测试才能达到最佳效果。当然这节课上我们也收获了不少的友谊。



**四、心得与体会**

通过本次选修课的学习，我进一步理解了计算机程序的运行与机器人的运行机制，同时，从本身的专业角度来说，也认识到了数学于计算机的联系，可能有些问题不一定完全是数字类型的纯数学问题，但其中所蕴含的逻辑思维，便是数学所需要的，从自身角度来说，这次课程进一步的提升了我的逻辑思维能力，为我今后的学习产生了潜移默化的帮助。再次感谢老师与同学们！















参考文献：

1：《跟我玩Blockly》，周庆国主编，兰州大学

2：《计算机科学导论：基于机器人的实践方法》，陈以农主编，陈文智副主编，机械工业出版社，2013年

3：http://cooc-china.github.io/

4：Github Blockly地址：[http://github.com/google/blockly](http://github.com/google/blockly)

5：TAR Ball地址：[http://github.com/google/blockly/tarball/master](http://github.com/google/blockly/tarball/master)

6：ZIP File地址：[http://github.com/google/blockly/zipball/master](http://github.com/google/blockly/zipball/master)

7：http://blockly.smallbird.net/


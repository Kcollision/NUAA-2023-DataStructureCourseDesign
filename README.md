# NUAA Fall 2023 数据结构课程设计
*完成题目如下*：
## 1.必做题
*完成8题*
### 1.1 系统进程统计（必做）（链表）
[问题描述]  
　　设计一个程序，每秒统计一次当前系统的进程状况，并按照内存使用自多到少排序打印输出相关信息。对已经结束的进程，另外给出一个列表，并显示该进程的结束时间和持续时间。  
[基本要求]  
（1） 该题目要求使用两个链式线性表。一个链表存储当前活动进程，要求使用单向链表，并按照内存使用自多到少排序。另外一个链表存储已结束进程，要求使用双向链表，按照持续时间自少到多排序。  
（2） 每秒在窗口内更新一次当前系统进程情况，输出内容包括：进程名，持续时间，内存使用情况。  
（3） 每秒在窗口内更新一次已结束进程情况，输出内容包括：进程名，持续时间，结束时间。  
（4） 注意进程在这两个链表中的切换，一个进程既可被结束，也可以过一段时间后再被运行。  
### 1.2 迷宫问题（必做）（栈与队列）
[问题描述]  
利用栈操作实现迷宫问题求解。  
[基本要求]  
（1）从文件中读取数据，生成模拟迷宫地图，不少于20行20列。  
（2）给出任意入口和出口，显示输出迷宫路线。  
### 1.3 家谱管理系统（必做）（树）
[问题描述]  
实现具有下列功能的家谱管理系统。  
[基本要求]  
（1）输入文件以存放最初家谱中各成员的信息，成员的信息中均应包含以下内容：姓名、出生日期、婚否、地址、健在否、死亡日期（若其已死亡），也可附加其它信息、但不是必需的。  
（2）实现数据的文件存储和读取。  
（3）以图形方式显示家谱。  
（4）显示第n 代所有人的信息。  
（5）按照姓名查询，输出成员信息（包括其本人、父亲、孩子的信息）。  
（6）按照出生日期查询成员名单。  
（7）输入两人姓名，确定其关系。  
（8）某成员添加孩子。  
（9）删除某成员（若其还有后代，则一并删除）。  
（10）修改某成员信息。 
（11）要求建立至少40个成员的数据，以较为直观的方式显示结果，并提供文稿形式以便检查。  
（12）界面要求：有合理的提示，每个功能可以设立菜单，根据提示，可以完成相关的功能要求。  
（13）存储结构：根据系统功能要求自行设计，但是要求相关数据要存储在数据文件中。测试数据：要求使用1、全部合法数据；2、局部非法数据。进行程序测试，以保证程序的稳定。  
### 1.4 Huffman编码与解码 (必做)（Huffman编码、二叉树）
[问题描述]  
对一篇不少于5000字符的英文文章（source.txt），统计各字符出现的次数，实现Huffman编码(code.dat)，以及对编码结果的解码(recode.txt)。  
[基本要求]  
（1） 输出每个字符出现的次数和编码,并存储文件(Huffman.txt)。  
（2） 在Huffman编码后，英文文章编码结果保存到文件中(code.dat)，编码结果必须是二进制形式，即0 1的信息用比特位表示，不能用字符’0’和’1’表示。  
（3） 实现解码功能。  
### 1.5 地铁修建 (必做)（图）
[问题描述]  
　　A市有n个交通枢纽，其中1号和n号非常重要，为了加强运输能力，A市决定在1号到n号枢纽间修建一条地铁。  
　　地铁由很多段隧道组成，每段隧道连接两个交通枢纽。经过勘探，有m段隧道作为候选，两个交通枢纽之间最多只有一条候选的隧道，没有隧道两端连接着同一个交通枢纽。  
　　现在有n家隧道施工的公司，每段候选的隧道只能由一个公司施工，每家公司施工需要的天数一致。而每家公司最多只能修建一条候选隧道。所有公司同时开始施工。  
　　作为项目负责人，你获得了候选隧道的信息，现在你可以按自己的想法选择一部分隧道进行施工，请问修建整条地铁最少需要多少天。
输入格式  
　　输入的第一行包含两个整数n, m，用一个空格分隔，分别表示交通枢纽的数量和候选隧道的数量。  
第2行到第m+1行，每行包含三个整数a, b, c，表示枢纽a和枢纽b之间可以修建一条隧道，需要的时间为c天。  
### 1.6 公交线路提示  (必做)（图）  
[问题描述]  
上网下载真实南京公交线路图，建立南京主要公交线路图的存储结构。  
[基本要求]  
（1）输入任意两站点，给出转车次数最少的乘车路线。  
（2）输入任意两站点，给出经过站点最少的乘车路线。  
### 1.7 B-树应用 （必做）（查找）
[问题描述]  
设计并实现B-树的动态查找。  
[基本要求]  
（1） 从文件读取数据  
（2）实现B-树的三种基本功能：查找、插入和删除。  
（3）以可验证的方式输出结果  
### 1.8 排序算法比较 （必做）（排序）
[问题描述]   
利用随机函数产生10个样本，每个样本有50000个随机整数（并使第一个样本是正序，第二个样本是逆序），利用直接插入排序、希尔排序，冒泡排序、快速排序、选择排序、堆排序，归并排序、基数排序8种排序方法进行排序（结果为由小到大的顺序），并统计每一种排序算法对不同样本所耗费的时间。  
[基本要求]   
（1） 原始数据存在文件中，用相同样本对不同算法进行测试；  
（2） 屏幕显示每种排序算法对不同样本所花的时间；  
## 2.选做题
*完成11题*
### 2.1 数字排序（哈希、排序）
[问题描述]  
　　给定n个整数，请统计出每个整数出现的次数，按出现次数从多到少的顺序输出。  
### 2.2 社交网络图中结点的“重要性”计算（选做）（图） 
[问题描述](https://pintia.cn/problem-sets/15/exam/problems/863)
### 2.3 魔法优惠券（选做）（排序）
[问题描述](https://pintia.cn/problem-sets/15/exam/problems/866)
### 2.4 点击窗口（选做）（线性表）
[问题描述]  
　　在某图形操作系统中,有 N 个窗口,每个窗口都是一个两边与坐标轴分别平行的矩形区域。窗口的边界上的点也属于该窗口。窗口之间有层次的区别,在多于一个窗口重叠的区域里,只会显示位于顶层的窗口里的内容。  
　　当你点击屏幕上一个点的时候,你就选择了处于被点击位置的最顶层窗口,并且这个窗口就会被移到所有窗口的最顶层,而剩余的窗口的层次顺序不变。如果你点击的位置不属于任何窗口,则系统会忽略你这次点击。  
　　现在我们希望你写一个程序模拟点击窗口的过程。  
### 2.5 消除类游戏（选做）
[问题描述]  
　　消除类游戏是深受大众欢迎的一种游戏，游戏在一个包含有n行m列的游戏棋盘上进行，棋盘的每一行每一列的方格上放着一个有颜色的棋子，当一行或一列上有连续三个或更多的相同颜色的棋子时，这些棋子都被消除。当有多处可以被消除时，这些地方的棋子将同时被消除。  
　　现在给你一个n行m列的棋盘，棋盘中的每一个方格上有一个棋子，请给出经过一次消除后的棋盘。  
　　请注意：一个棋子可能在某一行和某一列同时被消除。  
### 2.6 公共钥匙盒（选做）（线性表，栈，队列）
[问题描述]  
　　有一个学校的老师共用N个教室，按照规定，所有的钥匙都必须放在公共钥匙盒里，老师不能带钥匙回家。每次老师上课前，都从公共钥匙盒里找到自己上课的教室的钥匙去开门，上完课后，再将钥匙放回到钥匙盒中。  
　　钥匙盒一共有N个挂钩，从左到右排成一排，用来挂N个教室的钥匙。一串钥匙没有固定的悬挂位置，但钥匙上有标识，所以老师们不会弄混钥匙。  
　　每次取钥匙的时候，老师们都会找到自己所需要的钥匙将其取走，而不会移动其他钥匙。每次还钥匙的时候，还钥匙的老师会找到最左边的空的挂钩，将钥匙挂在这个挂钩上。如果有多位老师还钥匙，则他们按钥匙编号从小到大的顺序还。如果同一时刻既有老师还钥匙又有老师取钥匙，则老师们会先将钥匙全还回去再取出。  
　　今天开始的时候钥匙是按编号从小到大的顺序放在钥匙盒里的。有K位老师要上课，给出每位老师所需要的钥匙、开始上课的时间和上课的时长，假设下课时间就是还钥匙时间，请问最终钥匙盒里面钥匙的顺序是怎样的？  
### 2.7 算术表达式求值 (选做) （栈）
[问题描述]
　　一个算术表达式是由操作数(operand)、运算符(operator)和界限符(delimiter)组成的。假设操作数是正实数，运算符只含加减乘除等四种运算符，界限符有左右括号和表达式起始、结束符“#”，如：#6+15*（21-8/4）#。引入表达式起始、结束符是为了方便。编程利用“运算符优先法”求算术表达式的值。  
[基本要求]
（1） 从键盘或文件读入一个合法的算术表达式，输出正确的结果。  
（2） 显示输入序列和栈的变化过程。  
（3） 考虑算法的健壮性，当表达式错误时，要给出错误原因的提示。  
（4） 实现非整数的处理（*）。  
### 2.8 Hash表应用 （选做）（查找）
[问题描述]  
设计散列表实现VIP客户发掘。对身份证号进行Hash, 通过对乘客某时间段内的乘机频率、里程数统计，发掘VIP客户。   
[基本要求]  
（1） 设每个记录有下列数据项：身份证号码（虚构，位数和编码规则与真实一致即可）、姓名、航班号、航班日期、里程。   
（2） 从文件输入各记录，以身份证号码为关键字建立散列表。   
（3） 分别采用开放定址（自行选择和设计定址方案）和链地址两种方案解决冲突；显示发生冲突的次数、每次中解决冲突进行重定位的次数。  
（4）记录条数至少在100条以上。  
（5） 从记录中实现乘客乘机频率、里程数统计，从而发掘VIP客户。  
### 2.9 树的应用 (选做)（树）
 [问题描述]  
　　JSON (JavaScript Object Notation) 是一种轻量级的数据交换格式，可以用来描述半结构化的数据。JSON 格式中的基本单元是值 (value)，出于简化的目的本题只涉及 2 种类型的值：
　　* 字符串 (string)：字符串是由双引号 " 括起来的一组字符（可以为空）。如果字符串的内容中出现双引号 "，在双引号前面加反斜杠，也就是用 \" 表示；如果出现反斜杠 \，则用两个反斜杠 \\ 表示。反斜杠后面不能出现 " 和 \ 以外的字符。例如：""、"hello"、"\"\\"。  
　　* 对象 (object)：对象是一组键值对的无序集合（可以为空）。键值对表示对象的属性，键是属性名，值是属性的内容。对象以左花括号 { 开始，右花括号 } 结束，键值对之间以逗号 , 分隔。一个键值对的键和值之间以冒号 : 分隔。键必须是字符串，同一个对象所有键值对的键必须两两都不相同；值可以是字符串，也可以是另一个对象。例如：{}、{"foo": "bar"}、{"Mon": "weekday", "Tue": "weekday", "Sun": "weekend"}。  
　　除了字符串内部的位置，其他位置都可以插入一个或多个空格使得 JSON 的呈现更加美观，也可以在一些地方换行，不会影响所表示的数据内容。例如，上面举例的最后一个 JSON 数据也可以写成如下形式。  
　　{  
　　"Mon": "weekday",  
　　"Tue": "weekday",  
　　"Sun": "weekend"  
　　}  
　　给出一个 JSON 格式描述的数据，以及若干查询，编程返回这些查询的结果。  
输入格式  
　　第一行是两个正整数 n 和 m，分别表示 JSON 数据的行数和查询的个数。  
　　接下来 n 行，描述一个 JSON 数据，保证输入是一个合法的 JSON 对象。  
　　接下来 m 行，每行描述一个查询。给出要查询的属性名，要求返回对应属性的内容。需要支持多层查询，各层的属性名之间用小数点 . 连接。保证查询的格式都是合法的。  
### 2.10 最小生成树 (选做) （图）
[问题描述]  
利用普利姆算法和克鲁斯卡尔算法实现最小生成树问题。  
[基本要求]  
（1）自行建立图的数据文件，第一行是顶点个数，然后依次是顶点名，接下来是边，用float表示边的权值；  
（2）以邻接表或者邻接矩阵表示图皆可；  
（3）分别利用Prim和Kruskal算法实现最小生成树；  
（4）输出最小生成树的权值之和，及所用的边。  
### 2.11 电子小字典（选做）（查找）
[问题描述]  
利用键树结构，建立一个微型电子字典。  
[基本要求]  
实现生词的加入，单词的查找、删除，修改等操作。  

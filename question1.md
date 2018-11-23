# algorithm

问题1
求1-1000000之间的回文数m，使得m ，m^2,m^3均为回文数。


问题2 
已知鸡和兔的总数量为n,总腿数为m。输入n和m,依次输出鸡和兔的数目，如果无解，则输出“No answer”(不要引号)。
输入
第一行输入一个数据a,代表接下来共有几组数据，在接下来的(a<10)
a行里，每行都有一个n和m.(0<m,n<100)
输出
输出鸡兔的个数，或者No answer
样例输入
2
14 32
10 16
样例输出
12 2
No answer


问题3
无穷数列1，1，2，3，5，8，13，21，34，55...称为Fibonacci数列，它可以递归地定义为
F(n)=1 ...........(n=1或n=2)
F(n)=F(n-1)+F(n-2).....(n>2)
现要你来求第n个斐波那契数。（第1个、第二个都为1)
输入
第一行是一个整数m(m<5)表示共有m组测试数据
每次测试数据只有一行，且只有一个整形数n(n<20)
输出
对每组输入n，输出第n个Fibonacci数
样例输入
3
1
3
5
样例输出
1
2
5

问题4 
给定一整型数列{a1,a2...,an}（0<n<=100000），找出单调递增最长子序列，并求出其长度。
如：1 9 10 5 11 2 13的最长单调递增子序列是1 9 10 11 13，长度为5。
输入
有多组测试数据（<=7）
每组测试数据的第一行是一个整数n表示序列中共有n个整数，随后的下一行里有n个整数，表示数列中的所有元素.每个整形数中间用空格间隔开（0<n<=100000）。
数据以EOF结束 。
输入数据保证合法（全为int型整数）！
输出
对于每组测试数据输出整形数列的最长递增子序列的长度，每个输出占一行。
样例输入
7
1 9 10 5 11 2 13
2
2 -1
样例输出
5
1
问题5 
有这样一道智力题：“中汽中心世纪酒店酒水优惠规定：三个空汽水瓶可以换一瓶汽水。小张手上有十个空汽水瓶，她最多可以换多少瓶汽水喝？”
答案是5瓶，方法如下：先用9个空瓶子换3瓶汽水，喝掉3瓶满的，喝完以后4个空瓶子，用3个再换一瓶，喝掉这瓶满的，这时候剩2个空瓶子。然后你让老板先借给你一瓶汽水，喝掉这瓶满的，喝完以后用3个空瓶子换一瓶满的还给老板。如果小张手上有n个空汽水瓶，最多可以换多少瓶汽水喝？
输入
输入文件最多包含10组测试数据，每个数据占一行，仅包含一个正整数n（1<=n<=100），表示小张手上的空汽水瓶数。n=0表示输入结束，你的程序不应当处理这一行。
输出
对于每组测试数据，输出一行，表示最多可以喝的汽水瓶数。如果一瓶也喝不到，输出0。
样例输入
3
10
81
0
样例输出
1
5
40


问题6
如何合理安排中汽中心世纪酒店的住房问题被提到了日程。酒店已接到了大量的客户住宿定单，每张定单的内容包括要住宿的房间数，开始住宿时间和要住的天数。为了便于整个酒店的管理，酒店希望对这些定单进行安排，目的是用尽可能少的房间来满足这些定单，以便空出更多的房间用于安排流动客人。
酒店请求你来完成这个任务，对这些定单进行合理安排，使得满足这些定单要求的房间数最少。
假设：某个定单上的客人一旦被安排到某房间，在他预定住宿的期间内是不换房间的。为了简化描述，定单上的开始住宿时间为距离现在的第几天。例如，定单为（10，30，5）表示游客要求使用10个房间，第30天开始连住5天。
输入
第一行：T 表示有T组测试数据
每组测试数据第一行：N 表示定单数
每组测试数据接下来有N行，每行有三个整数 A B C 表示房间数，开始住宿时间和天数
1<=T<=100
1<=N<=10000 1<=A<=10 1<=B<=180 1<=c<=10
输出
输出一个整数，为满足所有定单要求的最少房间数。
样例输入
1
3
3 10 4
4 9 3
3 12 6
样例输出
7

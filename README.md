# 912-2021回忆版
912清华计算机专业基础2021回忆版

一·数据结构

1.判断题

2.填空题

(（1!+2^3)*4-5)-(6-7!-(8+9))

大约是这种意思，就是转换为	RPN形式

底下22个空格给你填写RPN后缀表达式。

strcut BTNode{
	int key;
	struct BTNode *lc;
	struct BTNode *rc;
	int size;
	
}BTNode,*BiTree;

2.算法题

二叉搜索树结构如下，设计一个算法获取在[lo,hi]区间内结点的数目。

struct BTNode{

​	int key;

​	struct BTNode *lc;

​	struct BTNode *rc;

​	int size;

}

​	int BTNode(BTNode *p,int lo,int hi){

}

1.设计一个算法，要求时间复杂度不超过树高h，不能使用额外空间，也就是空间复杂度O（1）。描述算法的设计思路，并使用伪代码实现

2.证明算法的正确性

3.时间复杂度和空间复杂度是什么

二·操作系统

判断题若干

填空

实现同步互斥的机制有信号，信号量，管道，消息队列

1.杀死一个进程的命令

2.linux中grep|

//Linux grep命令用于查找文件里符合条件的字符串；也可以用于查找内容包含指定的范本样式的文件。它能使用正则表达式搜索，用于在文件中搜索指定的字符串模式，列出含有匹配模式子符串的文件名，并输出含有该字符串的文本行。

3.如果一个进程要向输入区输入2MB的数据，另一个进程读取这些数据接续进行下一步工作。

5题
1.

主要考了简单文件系统
三计算机组成原理

IEEE754浮点数正负数表示范围关系为（）
A.正数表示范围大于负数表示范围 B.正数表示范围小于负数表示范围
C.正数表示范围等于负数表示范围 D.视情况而言有不同
TCP报头里包含（）
A.IP和端口号     B.IP和端口号以及MAC地址
C.MAC地址和IP地址 D.MAC地址和端口号
一个连续储存的机器中存了一个8位补码整数，其高位字节为0xFF,低位字节是0x01，如果在小端机器中用十进制整数表示为（ ），如果在大端机器中表示十进制整数（）。
四、计算机网络

1判断

2选择

3.填空

网络大题

路由通路协议和链路状态协议考察

有一个表格，使用路由信息协议的网络

1.填写表格，使用路由信息协议，C刚刚接入网络，它收到其他路由器发来路由表信息

到达点 距离 下一跳路由器

。。。

。。。//这是一个表格

2.如果使用链路状态协议，C发送出的数据，不要求格式，描述信息

3.当电路稳定后，使用路由信息协议和使用链路状态协议产生的路由表是否相同，说明理由

4.49，78，29，3，13，4，划分子网号以及掩码地址。

对网络划分网络号，和前几年那些差不多

4.最后一道大题

向一个地方发送八组数据，每个包大小为L，传输速率是C，单程传播时间T，超时时间是往返传播时延的两倍，使用GBN,SR，和差错检验的方法进行通信，发送8个组到，发到第二个出现错误，其余都正确，分别计算使用每种方法花费的时间，（差错检验就是收到后，再返回一个确认帧，确认帧发送时延忽略不计）



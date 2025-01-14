# Tenda AC6 : 15.03.05.16_multi
There is a overflow vulnerability in AC6 : 15.03.05.16_multi. In the fromDhcpListClient function(target url: DhcpListClient), the parameters page by http will cause buffer overflow.


![](9_1.png)





![](9_2.png)




![](9_3.png)



POC

![](9_4.png)




Bingo

![](9_5.png)

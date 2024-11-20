## Dlink DI-8003: 16.07.16A1

There is a overflow vulnerability in DI-8003: 16.07.16A1. In the jingx_asp function, the parameter fx by http will cause buffer overflow.
affected executable: jhttpd,, affected functions: jingx_asp

jingx_asp function

![](5_1.png)

check the vuln
![](5_2.png)


![](5_3.png)


deny of service
![](5_4.png)


![](5_5.png)



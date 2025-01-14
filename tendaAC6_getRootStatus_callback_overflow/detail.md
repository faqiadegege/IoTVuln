# Tenda AC6 : 15.03.05.16_multi

There is a overflow vulnerability in AC6 : 15.03.05.16_multi. In the sub_452A4 function(target url: getRebootStatus), the parameters callback by http will cause buffer overflow.



![](7_1.png)




![](7_2.png)



![](7_3.png)


POC

![POC](7_4.png)



Bingo

![Bingo](7_5.png)

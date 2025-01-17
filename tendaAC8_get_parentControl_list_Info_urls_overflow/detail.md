# Tenda AC8 : V16.03.34.06

There is a overflow vulnerability in AC8 : V16.03.34.06. In the get_parentControl_list_Info function(target url: saveParentControlInfo), the parameters urls by http will cause buffer overflow.



![](10_1.png)





![](10_2.png)




![](10_3.png)





![](10_4.png)






![](10_5.png)



POC

![](10_6.png)




Bingo

![](10_7.png)

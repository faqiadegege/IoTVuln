# title
 RX3 V1.0br_V16.03.13.11 overflow vulnerability

firmware: 
[Firmware: RX3 V1.0br_V16.03.13.11]( https://www.tendacn.com/download/detail-3980.html)
 
# info
In the RX3 V1.0br_V16.03.13.11 device, due to the lack of restrictions on some parameters in the fromSetWifiGusetBasic function, stack overflow can be caused
# detail



In the fromSetWifiGusetBasic function, when the value of the parameter shareSpeed obtained by http is 'shareSpeed', the value of the parameter shareSpeed obtained by http is concatenated using strcpy. Similarly, stack overflow can be caused without restrictions on the iface parameter.

![parameters](001_002.png)

![parameters](001_002.png)

![parameters](001_002.png)

![parameters](001_002.png)

![parameters](001_002.png)

![parameters](001_002.png)

# title
 DI_8200-16.07.26A1 RCE vulnerability
# info
In the DI_8200-16.07.26A1 device, due to the lack of restrictions on some parameters in the msp_info_htm function, command injection can be caused
# detail

![msp_info_htm](001_001.png)
In the msp_info_htm function, when the value of the parameter flag obtained by http is 'cmd', the value of the parameter cmd obtained by http is concatenated using sprintf and executed as the parameter of system. Similarly, commands can be executed remotely without restrictions on the iface parameter.
![parameters](001_002.png)

Exploit attempt success right here:
request
![webhttp](001_003.png)
shell ls
![webhttp](001_004.png)
exploit.txt content
![webhttp](001_005.png)

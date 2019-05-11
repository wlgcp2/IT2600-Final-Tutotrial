# Things To Do


#### __[Required Software](PART1.md)__ | __[Installing Servers](PART2.md)__ | __[Things To Do](PART3.md)__

---

##### To start using your Windows server add some roles! You do this by opening the Server Manager application and clicking add roles.

![alt text](roles.png "newVM")

##### Chose Role-Based installation

![alt text](insType.png "insType")

##### Select this server

![alt text](selServer.png "selServer")

##### And install DHCP server

![alt text](dhcp.png "dhcp")

##### Then in VMware Workstation add another network adapter and put it on vmnet 2.

![alt text](addAdap.png "adapter")

##### Then configure the new adapter in windows.

![alt text](adapWin.png)

##### Then go to the DHCP server manager and create a new scope.

![alt text](newScope.png)

##### Set the range for the available addresses and create the scope.

![alt text](range.png)

##### Create another server. I chose centos

![alt text](centOS.png)

---

#### __[<-](PART2.md)__ Section __[->](PART3.md)__

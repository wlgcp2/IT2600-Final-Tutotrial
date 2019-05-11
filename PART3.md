# Things To Do


#### __[Required Software](PART1.md)__ | __[Installing Servers](PART2.md)__ | __[Things To Do](PART3.md)__

---

##### To start using your Windows server add some roles! You do this by opening the Server Manager application and clicking add roles.

![alt text](pictures/roles.png "newVM")

##### Chose Role-Based installation

![alt text](pictures/insType.png "insType")

##### Select this server

![alt text](pictures/selServer.png "selServer")

##### And install DHCP server

![alt text](pictures/dhcp.png "dhcp")

##### Then in VMware Workstation add another network adapter and put it on vmnet 2.

![alt text](pictures/addAdap.png "adapter")

##### Then configure the new adapter in windows.

![alt text](pictures/adapWin.png)

##### Then go to the DHCP server manager and create a new scope.

![alt text](pictures/newScope.png)

##### Set the range for the available addresses and create the scope.

![alt text](pictures/range.png)

##### Create another server. I chose centos

![alt text](pictures/centOS.png)

---

#### __[<-](PART2.md)__ Section __[->](PART3.md)__

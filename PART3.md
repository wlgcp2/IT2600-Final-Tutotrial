# Virtual Network and DHCP Server


#### __[Required Software](PART1.md)__ | __[Installing Servers](PART2.md)__ | __[DHCP Server](PART3.md)__

---

##### Here I will show you how to create a virtual network with a DHCP server.

##### First create a new virtual network for your servers. Go to the view -> network editor. Add a new network VMnet2 and set the settings.

![alt text](pictures/vNet.png)

##### Then in VMware Workstation add another network adapter and put it on vmnet 2.

![alt text](pictures/addAdap.png "adapter")

##### To start using your Windows server add some roles! You do this by opening the Server Manager application and clicking add roles.

![alt text](pictures/roles.png "newVM")

##### Chose Role-Based installation

![alt text](pictures/insType.png "insType")

##### Select this server

![alt text](pictures/selServer.png "selServer")

##### And install DHCP server

![alt text](pictures/dhcp.png "dhcp")

##### Then configure the new adapter in windows.

![alt text](pictures/adapWin.png)

##### Then go to the DHCP server manager and create a new scope.

![alt text](pictures/newScope.png)

##### Set the range for the available addresses and create the scope.

![alt text](pictures/range.png)

##### Create another server. I chose centos

![alt text](pictures/centOS.png)

##### Make sure to set the network adapter to VMnet2.

![alt text](pictures/centNet.png)

##### Once booted on that net work it will get an IP from the Windows Server!

![alt text](pictures/centIP.png)

##### You can also see this in the Windows Server

![alt text](pictures/leases.png)


---

#### __[<-](PART2.md)__ Section __[->](README.md)__


















 # **1. INTRODUCTION** 
Cisco Systems is the leading technology-based multinational company having its headquarters in America. Cisco is well known for its hardware and software in the networking and telecommunication industry. It was founded by two students at Sandford university in 1984 who were computer science students (Leonard Bosick & Sandy Learner) and initially, they tried to connect the university computers which developed the concept of LAN. 

` `At present, it is having a workforce of 80, 000 employees with a very revenue of 49 billion dollars. Cisco has also introduced a set of training levels for their product information and their use. It is highly specialized in Routers, Switches, Server, firewalls, Webex, Online Teleconferencing, and other technology products. Chuck Robbins is the current CEO of the company The network simulation tool packet tracer is also a product of Cisco Systems. We have created the topologies in packet tracer and the network topologies are fully configured and all desired results are being achieved. 













 # **2. INFRASTRUCTURE**
Cisco has developed a variety of products that are very famous for establishing a network. We select the product we need depending on the size of the network. For small businesses, we normally use cost-effective products like routers and switches. Though there is a variety of Cisco routers and switches that are most suitable for large enterprise networks. 

|S.No |Product |Model|Application |
| - | - | - | - |
|1|Router|ISR4331|Small Networks |
|2|Router|ISR4321|Small Networks |
|3|Router|1941|Medium Size Networks |
|4|Router|2901|Small Networks |
|5|Router|2911|Medium Size Networks |
|6|Router|1841|Medium Size Networks |
|7|Router|2811|Medium Size Networks |
|8|Router|ASR9000|Large Enterprises Networks |
|9|Router|ASR5000|Large Enterprises Networks |
|10|Switch|2960|Small and Medium Networks |
|11|Switch|2950|Small and Medium Networks |
|12|Switch|3560|Medium and Large Networks |
|13|Switch|3650|Medium and Large Networks |
|14|Switch|Cat 4500|Medium and Large Networks |

 ## **2.1. BRANCH ROUTER ANATOMY**
The Cisco routers are normally used at a branch of an enterprise network. They interface with other network routers at one of the interfaces for a WAN connection and on the other side, they are connected to a small-sized LAN. 

The ISR Series routers are small branch routers used for small networks. The ISR Series router includes 

- ISR 800
- ISR 1900
- ISR 2900
- ISR 3900 
- ISR 4000

These are popular branch routers deployed for fulfilling small network and business needs.

# **3.0 TYPES OF NETWORKS** 
While designing and deploying a network a good designer always focuses on the security, cost, and reliability of the network. The Selection of the appropriate network devices and suitable IP plans are part of the network design.

We will discuss the network features according to the below tasks in more detail.
## **3.1 TASK#1**

![Aspose Words 10f76c18-138e-4596-a737-d14c93fdc5dd 004](https://user-images.githubusercontent.com/109302402/179350336-438e884f-9cd5-4883-84b1-fc4bd8ee28e1.png)

(Figure 3.1 Task#1 Network)

The above network consists of a router of 1941 Model connected directly to a PC-A through its G0/0 interface and to a switch through the G0/1 interface. This is a very simple network designed with no redundancy but to avoid the misuse of IP addresses it is using VLSM, and IP subnets have been assigned according to the need of the network. Apart from the correct IP planning, this network is also using device hardening for the security of the devices to avoid unnecessary access to the devices.

Below are the IP subnets which are being used in the network for enabling end-to-end communication.

- Subnet-A (20 H)

172.17.16.0/27 

- Subnet-B (2540 H)

172.17.0.0/20

All lines of the router have been secured using password security and only authorized people are allowed to access the devices and alert warning has been displayed that action may be taken against the unauthorized personnel trying to access the device.


## **3.2 TASK#2**

![Aspose Words 10f76c18-138e-4596-a737-d14c93fdc5dd 005](https://user-images.githubusercontent.com/109302402/179350339-432b42ea-3be4-44dc-98bd-bdcde91967b0.png)

`				          `(Figure 3.2 Task#2 Network)

This network topology is designed for both IPV6 and IPV4 networks where the hosts on the right are based on IPV6 configuration and the left are based on IPV4 configuration. The server is located on Internet, and we access it through the end user’s PCs.
## **3.3 TASK#3**
![Aspose Words 10f76c18-138e-4596-a737-d14c93fdc5dd 006](https://user-images.githubusercontent.com/109302402/179350351-594bb5ee-bf17-413f-b76a-eaa9382a276d.png)
			          (Figure 3.3 Task#3 Network)

Task #3 is based on inter-VLAN routing where the hosts residing on different IP subnets can communicate with each other. We have configured four subnets were 

Three VLANs are representing three different networks and one subnet for the Management of the devices remotely.

- Faculty

VLAN 10

172.17.10.21/24

- Student

VLAN 20

172.17.20.22/24

- Guest

VLAN 30

172.17.30.23/24

The router on a stick inter VLAN has been configured for a cost-effective and smart approach. We use a router on a stick when we have lower traffic requirements. The interface between the switches is is configured as a Trunk which carries the data from all VLANs mentioned in the network.
## **3.4 TASK#4**

![Aspose Words 10f76c18-138e-4596-a737-d14c93fdc5dd 007](https://user-images.githubusercontent.com/109302402/179350371-68866f58-67cf-4da0-be72-9731a028df9c.png)

`					`(Figure 3.4 Task#4 Network)

This network is having two different networks connected to the router interface. The switches are connected to end-user devices. In this case, we are using a simple IP configuration. Routing protocols are not required in this network as the subnets are directly connected to the same router.

Below is the IP plan in this case.

Finance Department: 192.168.10.96/27

IT Department Switch: 192.168.10.144/28
# **4.0 DEVICE FACTORY RESETTING** 
Factory resetting of the device means, bringing the device back to its original status. We use different commands to erase the already done configuration on the routers and switches. The erase command removes both running and NVRAM Saved configuration.


![Aspose Words 10f76c18-138e-4596-a737-d14c93fdc5dd 008](https://user-images.githubusercontent.com/109302402/179350373-48b9e7d0-553e-4aa1-b78d-3ca3c948ba19.png)

`			`(Switch 4.0 Factory Reset)


![Aspose Words 10f76c18-138e-4596-a737-d14c93fdc5dd 009](https://user-images.githubusercontent.com/109302402/179350375-1d3a43ea-b471-464f-b541-95c224d94c4c.png)

`			`(Router 4.0 Factory Reset)














# **5.0 BASIC DEVICE CONFIGURATION** 

Basic device configuration involves the configuration of basic security settings, the configuration of a banner message of the day, and the creation of local user accounts. The below basic security configurations have been done on the Main\_Hall Router.


![Aspose Words 10f76c18-138e-4596-a737-d14c93fdc5dd 010](https://user-images.githubusercontent.com/109302402/179350380-e8d092c3-7f81-4af6-9808-a01ba25ea596.png)

We have run a command service password-encryption to encrypt the passwords which further increases the device security. 












# **6.0 PASSWORD RECOVERY**
Password recovery is the process of resetting a forgotten or lost password of a device. Normally network administrators maintain a data sheet to keep their passwords save but it’s also common to forget them.  When we forget a password of a router or a switch, we can’t access the device and can’t modify any configuration on the device.  Therefore, the safety of the passwords is important but when passwords are lost, we use the below techniques to recover them.
## **6.1 CISCO ROUTER PASSWORD RECOVERY** 
The password recovery procedure is always initiated through console access, it can’t be through remote access over telnet or SSH. 

We reboot the router and send CTRL+Break to send break signals to the router when routers accept this break signals its changes the mode to ROMMON Mode which is the small operating system to bypass come configurations when required. At this stage, the model should look like the one below.


![Aspose Words 10f76c18-138e-4596-a737-d14c93fdc5dd 011](https://user-images.githubusercontent.com/109302402/179350383-1f392269-a5f7-4556-a0c3-69e7f21104dc.png)

Now we will change the configuration register of the router so that the router will ignore the start-up configuration upon the next boot process.

![Logo, company name


![Aspose Words 10f76c18-138e-4596-a737-d14c93fdc5dd 012](https://user-images.githubusercontent.com/109302402/179350387-4f7242fa-d2eb-4e64-955f-d987421c7b39.png)

After changing the configuration register, we now reset the router for initiating a reboot process again.


![Aspose Words 10f76c18-138e-4596-a737-d14c93fdc5dd 013](https://user-images.githubusercontent.com/109302402/179350389-76a74274-0dbd-4f27-a595-f6b61f47b875.png)

After successful rebooting the router will not ask for passwords because we have already bypassed the previous configuration by changing the configuration register.

![Background pattern


![Aspose Words 10f76c18-138e-4596-a737-d14c93fdc5dd 014](https://user-images.githubusercontent.com/109302402/179350393-4c8cf437-3d1c-4c50-8ab4-6ceeeb36f2e3.png)

Now we can copy the previous running configuration to the router again, but the passwords need to be set again.
## **6.2 CISCO SWITCH PASSWORD RECOVERY** 
- We need a console connection to the cisco switch for password recovery.
- Hold the mode button and power on the switch.
- Releasee the Hold button when the screen starts showing some initializing steps as below.
- ![Aspose Words 10f76c18-138e-4596-a737-d14c93fdc5dd 015](https://user-images.githubusercontent.com/109302402/179350400-13ea0b5d-ac37-49ee-b43b-62d6ee3f0f91.png)

- Now we find the config file in the flash.
- After finding the config file we rename it.
- Then we run “boot” command to initiate boot process.
- After boot finish the switch will prompt below dialog

*Would you like to enter the initial configuration dialog? [yes/no]: n (we type No)*

- Now we rename the configuration file to its original name before edit.
- Now write the configuration to NVRAM.
- Configure the passwords now and keep them in a safe place.



## **7.0 CONCEPT AND IMPLEMENTATION OF VLAN TECHNOLOGY**
VLAN is a virtual LAN that is basically a group of devices locating on the same network and sharing resources among them. These devices are grouped in a same group ID which is called the VLAN ID. From the same physical switch another group of devices are also connected under another VLAN ID. 

In these cases, the device within the same VLAN ID communicate with each other but can’t communicate with the devices on the devices on other VLAN ID. 

We have used the concept of VLAN’s in the task#3, the output of commands from the switches of this network are below showing the VLAN name, ID and the member ports.


![Aspose Words 10f76c18-138e-4596-a737-d14c93fdc5dd 016](https://user-images.githubusercontent.com/109302402/179350406-ccc40c1e-4338-4951-ac51-d953f98b686f.png)

(Figure 7.0 VLAN Implementation)

We always configure the VLAN’s to optimize network resources and ensure the security between different VLANs. The configuration of VLAN’s introduces network scalability, bandwidth optimization and resource optimization.








# **8.0 IPV4 ROUTING** 
Routing in general is the path followed by an IP packet from a source to a destination. This path finding is done using different routing methods. We have static routing and dynamic routing procedures which have their own Pro & Cons. Static routing is suitable for smaller networks where the administrator has a full exposure to the whole network. For small networks, static routing is ideal as we the routing is under control of the administrator, and he adds only the known routes thus static routing provides a security in the network. Dynamic routing learns the routes automatically when configured and is suitable for large Networks

In this report we have not used dynamic routing, but we have used static routing a will see the output for static routing. The dynamic routing uses dynamic routing protocols like RIP, OSPF, EIGRP, BGP & IS-IS.

R1>

R1>en

R1>enable 

R1#conf t

Enter configuration commands, one per line. End with CNTL/Z.

R1(config)#ip route 0.0.0.0 0.0.0.0 209.165.200.226 

R1(config)#end

R1#

%SYS-5-CONFIG\_I: Configured from console by console

For the static routing we add the required networks on our router and for dynamic we advertise the connected networks.





#


# **9.0 MIGRATION TO IPV6 AND CONFIGURING IPV6 NETWORKS**
Due to the over utilization of IPV4 and less availability of IPV4 now, the IPV6 was introduced with a very large IP capacity. Now-a-days bigger companies are shifting the networks to IPV6 to get rid of the scarcity of IPV4 addresses. 

There are few benefits of IPV6 like the packet processing of IPV6 is very fast as compared to IPV4 and IPV6 doesn’t need any subnetting. We have configured IPv6 Task#2 for one of the set of hosts, the IPV6 configuration has been done as below.


![Aspose Words 10f76c18-138e-4596-a737-d14c93fdc5dd 017](https://user-images.githubusercontent.com/109302402/179350411-fafbc096-2d4e-47df-b743-9f77ab91f03c.png)

`			`(Figure 9.0.1 IPV6 host Configuration)
`			`

![Aspose Words 10f76c18-138e-4596-a737-d14c93fdc5dd 018](https://user-images.githubusercontent.com/109302402/179350415-4f224117-9633-4420-8491-03ba28a7b004.png)



`			`(Figure 9.0.2 IPV6 Router interface Configuration)

# ` `CONCLUSION 
The reports are based on some small IP networks, their design and operation. Moreover, the configuration of different technologies has been discussed. The IP networks are using technologies like.

- Basic Device Security Configuration
- IPV4 configuration
- IPV6 Configuration
- VLAN Configuration
- Inter VLAN Routing
- SSH & Telnet Configuration. 
- VLSM Subnetting
- IPV6 Routing 
- IPV4 Routing.

The networking technologies have been implemented and configured to make the networks functional. Connectivity test and route verifications have been done to make testing’s real that are done like in real world.
# **REFERENCES**
ALshawi, M. (2019). Campus Network Design Guideline. *https://community.cisco.com/, 2*(2), 8.

Lynch, A. (2014). Cisco Network Design Tool. *https://www.edrawsoft.com/author/allison/, 1*(1), 8.

Richardson, S. (2022). *Network Design Methodology.* USA: ccexpert.us.

Stamper, D. A. (2018). Network Design. *encylopedia.com, 1*(2), 2.





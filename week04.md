#  Week 4 journal
- Task 3 a : A switched LAN with one switch and four PCs
 ![part a](./image/week4-task3-lana.png)

- Task 3 b :A switched LAN that has four PCs connected to one switch, four PCs connected to another switch, and those two switches are connected to a third switch in star topology.
 ![part b](./image/week4-task3-lanb.png)

 - Task 4 : Inspect the packets in Wireshark (many are very similar, so focus on the different packets).  
 ![part b](./image/week4task4-ping.png)

- Purpose of ARP Packets
     Address Resolution Protocol (ARP). It can be used to discover the MAC address of a device if the device's IP address is known.

     As you can see in my capture, Windows was trying to ping the OpenWRT guest at 192.168.1.1. Windows was aware of the IP address, but it required the MAC address of OpenWRT.

     The following is a Windows ARP Request message:

     Who has 192.168.1.1?

     Sent to the broadcast MAC address:

     ff:ff:ff:ff:ff:ff
- The list below contains explanations of the first two ICMP packets.Below are the explanations to the first two ICMP packets.
   In my packet capture, the first ICMP packet is #4. It is an ICMP Echo Request sent from Windows PC to OpenWRT virtual machine. When ping is run to see if the OpenWRT VM can be reached, this packet is generated.

   The Windows PC has the MAC address 08:00:27:14:87:98, while the OpenWRT VM has the MAC address 0a:00:27:00:00:05. Thus, Frame 4 is transmitted from the Windows PC (MAC address) to the OpenWRT VM (MAC address).

    This is the second ICMP packet which is an ICMP Echo Reply, ICMP Type 10, Code 0. Once it receives the Echo Request, it is forwarded back to the Windows PC by the OpenWRT VM. The direction of the communication has         changed, hence the MAC addresses have been reversed.

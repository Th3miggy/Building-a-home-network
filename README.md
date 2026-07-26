# Building-a-home-network

## Desricption
This project showcases my actual home network how things are set and why they are the way that they are 

### Objective

This project has a pretty straight forward objectives getting a home network up and running in a Ubiquiti ecosystem.

#### Skills Learned

- Understanding and implemeting hardware newtork device inculding Routers, switch, acces points, cables/connections.
- Understanding networking Topology and Infrastructure.
- Creating and assigning Vlans.
- Working with port configurtion and assgining access/trunk ports.
- Understanding the necssity of subnetting security in Home and enterprise networks.
- Creating and implemeting a Guest Wifi and confiuging how it communties with the rest of the network
- Creating firewall polices 

### Tools Used

- Network hardware equipment APs, switches, routers as well as tools for creating cables run for wired devices.
- Unifi contorl panel for network operations and Unifi proctect.
- Clients device montioring to add clients to network and make all vlans and firewall ploices are being followed.

## Steps
Below are screenshots that will refer the network the steps take for basic setup

Note: some parts of the image will be redacted for privcy

Ref 1: First we obtain Internet access though are ISP and connected our Unifi router and 16 port Switch

![not-working](https://github.com/Th3miggy/Building-a-home-network/blob/main/ChatGPT%20Image%20Jul%2025,%202026,%2009_21_45%20PM.png?raw=true)

Ref 2: After that other Unifi device were add to the network including a accesspoint and a NVR with several cameras

![not-working](https://github.com/Th3miggy/Building-a-home-network/blob/main/Screenshot%20from%202026-07-25%2014-56-22.png?raw=true)

Ref 3: Next we created several Vlans for our devices including a main newtork, IoT network, Camera network and a Guest network (note:
the guest network was setup as a hotspot network for untrusted device as well as having a landing paper)

![not-working](https://github.com/Th3miggy/Building-a-home-network/blob/main/Screenshot%20from%202026-07-25%2014-56-44.png?raw=true)

Ref 4: After the Vlans network were establish we created Wifi for though Vlans (note: a Wifi was not created for the camera network becasue all though device are hard wired)

![not-working](https://github.com/Th3miggy/Building-a-home-network/blob/main/Screenshot%20from%202026-07-25%2014-57-17.png?raw=true)

Ref 5: Once Vlans and wifi were online created firewall policy for device on the network.

![not-working](https://github.com/Th3miggy/Building-a-home-network/blob/main/Screenshot%20from%202026-07-25%2014-57-48.png?raw=true)

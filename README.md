# ✍️ Computer-Networking-Course


## 🎥 Video Tutorials
#### 🧠 Encoding (Line-Block-Scrambiling) : **([👉Click Here](https://youtube.com/playlist?list=PLncy2sD7w4YpbMkd6cF0kVH8SUM-VrpeQ))**

#### 🧠 Network Layer Introduction : **([👉Click Here](https://youtu.be/rW1jPlYgp_0))**

#### 🧠 Network Layer Playlist Bangla: **([👉Click Here](https://youtube.com/playlist?list=PLMW5djzR9cKPDaY5f30lC4VgqL9nRQG6g))**


#### 🧠 Network Layer Playlist Neso Academy: **([👉Click Here](https://youtube.com/playlist?list=PLBlnK6fEyqRi7E6_6rLC5N_v50TW6qlrf))**

<hr>

### Cisco Packet Tracer Tutorials

- **Network Lab Playlist ([👉Click Here](https://youtube.com/playlist?list=PLtPLcjdwym2mhii8gss61nvgLG609sf_H))**

- [Switch & End Device Connection Tutorial](https://www.youtube.com/watch?v=YZRQpZPp4E4&list=PLB57s6OrG8LjS4rXfvYZd95H5oHPabDcF&index=1) - This tutorial demonstrates how to connect switches and end devices using Cisco Packet Tracer.
- [Router on a Stick Inter-VLAN Routing Tutorial](https://www.youtube.com/watch?app=desktop&v=qwJlypSanLc) - Learn how to configure router on a stick for inter-VLAN routing.
- [Static Routing with Connecting 4 Routers Tutorial](https://www.youtube.com/watch?app=desktop&v=rZw_b0wpQ00) - This tutorial explains static routing and shows how to connect four routers in Cisco Packet Tracer.
- [IPv4 Subnetting using Cisco Packet Tracer Tutorial](https://www.youtube.com/watch?app=desktop&v=fvFr7K5SRlM) - This tutorial covers IPv4 subnetting concepts using Cisco Packet Tracer.

## VLan Config Commands

#### Creating VLan

- Switch>en
- Switch#conf t

- Switch(config)#vlan 10
- Switch(config-vlan)#name V10
- Switch(config-vlan)#ex
- Switch(config)#vlan 11
- Switch(config-vlan)#name V11
- Switch(config-vlan)#ex	
- Switch(config)#vlan 12
- Switch(config-vlan)#name V12
- Switch(config-vlan)#ex

- Switch#show vlan

#### VLan setuping - 10

- Switch#conf t
- Switch(config)#int fa 0/1
- Switch(config-if)#switchport mode access
- Switch(config-if)#switchport access vlan 10
- Switch(config-if)#ex

- Switch(config)#int fa 0/6
- Switch(config-if)#switchport a
- Switch(config-if)#switchport access vlan 10

- Switch(config-if)#ex
- Switch(config)#ex
- Switch#

- Switch#show vlan


#### VLan setup - 11

- Switch#conf t

- Switch(config)#int fa 0/2
- Switch(config-if)#sw
- Switch(config-if)#switchport m
- Switch(config-if)#switchport mode a
- Switch(config-if)#switchport mode access 
- Switch(config-if)#sw
- Switch(config-if)#switchport a
- Switch(config-if)#switchport access vlan 11
- Switch(config-if)#ex
- Switch(config)#int fa 0/5
- Switch(config-if)#sw
- Switch(config-if)#switchport m
- Switch(config-if)#switchport mode a
- Switch(config-if)#switchport mode access 
- Switch(config-if)#sw
- Switch(config-if)#switchport a
- Switch(config-if)#switchport access vlan 11
- Switch(config-if)#ex
- Switch(config)#ex
- Switch#


- Switch#show vlan



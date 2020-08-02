# OpenQbitP2P
Mobile phone communication through "Tor" network and synchronization of P2P files with "Syncthing"

![P2P](https://user-images.githubusercontent.com/60530547/89117654-207bef80-d465-11ea-85d4-1114ba89bbe0.png)


Extension OpenQbitP2PwithSSH is located in the Extension directory.

The user manual is in the Handbook directory (Spanish and English)

We are working on the user manuals in languages ​​(Dutch, Russian, Italian, Japanese, Chinese, German, French and Portuguese) in August they will be ready.

This is an extension (OpenQbitP2PwithSSH) to use the communication systems; Red Tor and Syncthing P2P with Blockly programming (App Inventor, AppBuilder, Thunkable, others).

Peer-to-peer networks leverage, manage and optimize the use of bandwidth of other network users through connectivity between them, and thus obtain more performance in connections and transfers than with some conventional centralized methods, where a relatively small number of servers provide the total bandwidth and shared resources for a service or application. 
Such networks are useful for a variety of purposes. They are often used to share files of any kind (e.g. audio, video or software). This type of network is also often used in VoIP telephony to make real-time data transmission more efficient. 
The efficiency of the nodes in the data link and transmission may vary depending on their local configuration (firewall, NAT, routers, etc.), processing speed, bandwidth availability of your network connection and disk storage capacity. 
In our case we will be using the functionalities of two developments with maturity in their use and characteristics in communication, security and diversity for their use.

The first is the "Tor" network - Tor (acronym for The Onion Router) is a project whose main objective is the development of a low-latency distributed communications network superimposed on the Internet, in which the routing of messages exchanged between users does not reveal their identity, i.e. their IP address (anonymity at network level) and which, moreover, maintains the integrity and secrecy of the information that travels through it.
More reference in: https://www.torproject.org/

We will use this "Tor" network for any kind of communication between mobile phones whether they are in a Wifi environment or with a mobile Internet service from any phone company worldwide. Later on we will use it to create a secure channel through this network with an SSH (Secure Shell) service. With this combination we will be able to send, distribute, copy, obtain any kind of data.
Another tool or service that we will be for synchronization and / or data replication is Syncthing.

Syncthing. - It is an open source point-to-point file syncing application available for Windows, Mac, Linux, Android, Solaris, Darwin and BSD.  
You can synchronize files between devices on a local network or between remote devices over the Internet. Data security is integrated into the software design.

How does it work?

Device discovery is achieved through publicly accessible discovery servers hosted by the project developers, local (LAN) discovery through broadcast messages, device history and static addressing/hosting. The project also provides the Syncthing Discovery Server program to host the discovery servers themselves, which can be used in conjunction with or as a replacement for public servers.
The network of community-contributed relay servers allows devices behind different IPv4 NAT firewalls to communicate by transmitting encrypted data through a third party. The retransmission performed is of a similar nature to the TURN protocol, with TLS-encrypted end-to-end traffic between devices (therefore, even the relay server cannot see the data, only the encrypted sequence). Private relays can also be configured and set up, with or without public relays, if desired. Synchronization will automatically switch from relay to direct device-to-device connections if it finds that a direct connection is available.
Synchronization can be used without any connection to the project or community servers: updates, optional usage data, discovery and relaying can be disabled and/or configured independently, so the mesh and its infrastructure can run in a closed system for privacy or confidentiality.

More information can be found in the reference: https://syncthing.net/

Foundation OpenQbit

www.OpenQbit.com

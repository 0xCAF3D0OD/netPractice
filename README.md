![netpractice.png](img/netpractice.png)
## introduction
This project aims to introduce you to the network through practical cases.

## Table content
* ☞&nbsp;&nbsp; **General concept**
  * [ What is a **network protocol**? ](#network)
  * [ What is the **OSI model**? ](#OSI)


* ☞&nbsp;&nbsp; **[ main concept ](#titre)**
  * [ What is the **IP** or Internet Protocol? ](#IP)
    * [ What is the Internet Protocol adress? ](#IPAd)
  * [ What is the **TCP** or Transmission Control Protocol? ](#TCP)


## General information


* **General information on how the network as a whole works.**
<a name="betwork"></a>
### 🔽 What is a network protocol?

----
* In networking, **a `protocol` is a set of rules for formatting and processing data**. Network protocols are like a common 
language for computers. Computers on a network may use very different software and hardware, but **the use of protocols 
allows them to communicate with each other**.

> For example two people who do not speak the same language, one French and one German, would have a second language 
to understand each other, English.

* **On the Internet, there are different protocols for different types of processes.** Protocols are often discussed in 
terms of the layer of the `OSI` model to which they belong.


<a name="OSI"></a>
### 🔽 What is the OSI model? 

----
* The `OSI` (Open Systems Interconnection) model is an abstract representation of how the Internet works.
* It is made up of 7 layers: 

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[<img src="img/osi-model-7-layers.png" width="300">](img/osi-model-7-layers.png)

* Each layer representing a different category of networking functions, **the protocols make these networking 
functions possible**.

* ☞ &nbsp;&nbsp;&nbsp;The [ **Internet Protocol** (`IP`) ](#TCP) makes network-to-network communications possible. `IP` 
is considered a **[network layer](https://www.cloudflare.com/learning/network-layer/what-is-the-network-layer/)** 
(Layer 3) protocol

* ☞ &nbsp;&nbsp;&nbsp;The [ **Transmission Control Protocol** (`TCP`) ](#TCP) ensures the smooth transport of data packets over networks. 
Therefore, TCP is considered a transport layer (Layer 4) protocol.
* ℹ️ More information about OSI [here](https://www.cloudflare.com/learning/ddos/glossary/open-systems-interconnection-model-osi/).

<a name="titre"></a>
## main concept

* **The following themes are important for the net practice project.**

<a name="IP"></a>
### 🔽 What is the internet Protocol (`IP`) ?

----
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[<img src="img/ip.png" width="300">](img/ip.png)
* **Internet Protocol** `(IP)` is a `protocol`, or set of rules, for **routing and addressing data packets** so that they can 
traverse networks and arrive at the correct destination.

<a name="IPad"></a>
#### &nbsp;&nbsp;▶️ What is the internet Protocol address ?
* > the `IP` **address** is similar to the phone number assigned to your smartphone.
* An `IP` **address** is a unique number that **allows a computer to communicate in a network**. 
  * ⚠️ There **cannot** be several **computers** with the **same IP address** in the same network.
  * The unique **number** can be **assigned temporarily or permanently**.
* Each IP address is a series of characters, such as 192.168.1.1,
DNS resolvers translate human-readable domain names into IP addresses.


  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[<img src="img/schema-adresse-ip.png" width="300">](img/schema-adresse-ip.png)


* **Two types of IP addresses**: public IP addresses and local IP addresses:
  * **Local IP addresses**: these are managed at the level of your local network between the **[ADSL modem](https://fr.wikipedia.org/wiki/Modem)** 
  and **[Ethernet or Wi-Fi router](https://fr.wikipedia.org/wiki/Routeur)**, and your equipment (computers, mobiles, connected objects, etc.)
  * **Public IP addresses**: these are managed globally by an organization that allocates these addresses individually to all
  equipment and services connected to the Internet (websites, video hosting sites, etc.).


  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[<img src="img/schema-adresse-ip-interne-externe.png" width="300">](img/schema-adresse-ip-interne-externe.png)


<a name="TCP"></a>
### 🔽 What is the Transmission Control Protocol (`TCP`) ?

----

* `TCP` **is a transport layer protocol that ensures reliable delivery of data**. TCP is intended to be used with IP, and 
the two protocols are often referred to together as TCP/IP.
* > If the IP address is similar to the phone number assigned to your smartphone. 
*  > TCP is all the technology that makes 
the phone ring and allows you to talk to someone on another phone. They are different from each other, 
but they are also meaningless without each other.

* Difference between `TCP/IP` and other protocol **[UDP/ IP](https://www.cloudflare.com/fr-fr/learning/ddos/glossary/user-datagram-protocol-udp/)**

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[<img src="img/tcp-ip_udp-ip.png" width="300">](img/tcp-ip_udp-ip.png)


## Ressources

* [net practice subject](https://cdn.intra.42.fr/pdf/pdf/58600/fr.subject.pdf)


* **Network Protocol documentation**
  * [Qu'est-ce qu'un protocole? | Définition d'un protocole de réseau](https://www.cloudflare.com/fr-fr/learning/network-layer/what-is-a-protocol/)

 
* **IP documentation**
  * [Adresse IP - Définition et Explications](https://www.techno-science.net/glossaire-definition/Adresse-IP.html)
  * [Qu'est-ce qu'une adresse IP? ](https://www.avast.com/fr-fr/c-what-is-an-ip-address)
  * [Qu'est-ce que IP (Internet Protocol)?](https://www.cloudflare.com/fr-fr/learning/network-layer/internet-protocol/)


* **TCP documentation**
  * [Transmission Control Protocol wiki](https://fr.wikipedia.org/wiki/Transmission_Control_Protocol)
  * [rfc support](https://www.rfc-editor.org/rfc/rfc793)
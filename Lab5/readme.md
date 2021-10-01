## Christopher Beale / 9/28/2021

## Executive Summary 
The world we live in, more than ever relies on the transmission of data. In doing so, we have exposed the many possibilities for this sensitive information to be extracted or taken and this has proven to be both helpful and detrimental. Cyberattacks to take people's identity, but also hacking to decode potential threats to the lives of millions. There are a number of methods in which to secure and encrypt this seemingly free flowing information. The importance of each and it's origin are just as important as how they are used or not used today.

## Lucidchart
I have previously used Lucidchart and like it quite a bit. I had used it to create organizational and operational flowcharts for my last job. I find it rather easy to use and very powerful in how much extra that's imbedded in it. 
## Introduction to Networking

### Data Transmission
#### Packet:
A unit of data. A message sent between two host computers is broken up into units of data called packets to carry the necessary information. 
#### Packet-Switching:
Technology that allows packets of data to be routed based on destination address. This is packet forwarding technology that sends data to its target destination within a LAN (Local Area Network).
#### IP Address:
Unique identifying number. Each device connected to the internet is assigned a means of identification.
#### DNS:
Directory of IP address common names. For example 54.239.26.214 might be the IP address of amazon.com. When requesting to access a host with a domain, a DNS server is queried and an IP address is returned, allowing for proper routing. 
#### Protocol:
Set of rules to allow devices to communicate. Either TCP/IP or FTP. 

### Networking Hardware
#### Switch vs. Hub
The benefit of a switch over a hub is that a hub is not intelligent, unlike a switch, which can route data to specific ports. A hub just resends the data packet on all attached ports. Switches copy the addresses of the connected ports. It also reduces unnecessary traffic. 
#### Router vs. Switch and Hub
Hubs and switches are used to create networks while routers are used to connect networks. The router is able to read IP addresses, unlike hubs and switches. 

### Network Topologies
#### Single point of Failure
A single point of filure is when a central point in a network goes down, thus causing the whole network to go down. Common with star and ring topology networks.
#### Infrastrucutre vs. Wireless Mesh
The infrastructure newtork still consists of wired elements that allow for a bridge to the network via router. The Wireless mesh topology is able to wirelessly cover a broad area like an office by having many wireless access points. 
### Network Design
I created a network diagram, but I don't believe there is any specific shape to the network topology other than a general sequence of operation in my mind. The modem acts as the gateway to the network that's distributed through the router. I have a PC directly connected to the router. The router is also connected to a wireless access point for the printer and laptop to utilize.
### NSA/CSS
The Agency collects, processes, and disseminates intelligence information from foreign electronic signals for national foreign intelligence and counterintelligence purposes and to support military operations. NSA/CSS is also tasked with preventing foreign adversaries from gaining access to classified national security information.

## Cybersecurity and Encryption

### Information Systems Security

#### Security Triad
In regards to the confidentiality aspect of the triad, I believe the impact on the approach of a feature like amazon.com online chat would pose some real issues of the typed exchange of personal infomation, especially when verifying identity. 
The integrity of the exchange could also be subject to attack and/or the person on the other end of the chat could be involved with questionable integrity. 
The availability of the data being exchanged and referenced to is also subject to more hesitation because this information is likely needed to always be available, unless the hours of the service are defined otherwise. 
#### Authentication
Three daily tasks that require authentication are unlocking a device, particularly a cellphone, using an ATM to withdraw cash, and accessing an app on a device.
The unlocking of a cellular device in most cases I believe is already able to be convirted to multi-factor by having both a biometric and access key or pin. This very same thing could be done for both of the remaining examples by prompting the user to know a pin/key, or having a contributing item to supplement a biometric feature to verify the identity of the user. 
#### ACL and RBAC
These two feactures of security act as rosters/lists to verify that the input of identification information is synched to a verified user and allow access to all approved data. ACL is great for networks with fewer users, however not great with many and is also difficult to add/remove users from large allocations of info privileges. With RBAC, an added layer of security is implemented by way of assigning specific roles to users. What is accessible to each of those users is governed by the definitions of those roles. 
#### Ciphertext, Public Key and Private Key
The sender of a message has both a public and private access key. In order to send the message, the sender must know the public key of the recipient. When sending the message is encrypted into ciphertext, and can only be decrypted and viewed by the recipient by inputing their private key. 
#### Public Key Cryptography
Public key encryption is important because it allows two people to effectively share public keys in order to encrypt private messages intended for one another but can only be decrypted by each users respective private key and not anyone else. 

### Cryptography
#### Encryption
The encryption is based on a shift of 21 to reveal the accurate letter to decrypt the message, where the letter u = 'a'
#### Frequency Fingerprint
In this interactive model, we are able to see the frequency in which a particular letter is used. This can be used to count a map of letters often used to begin sifting through a greatest common factor idea of the overall message. If you've ever done a cryptogram puzzles, this is a similar idea in decoding the message. Yes, the outcome would be different for other languages because there are different alphabet systems.   
#### Polyalphabetic Cipher
This method of cryptography involves using multiple shifts when decrypting the message being sent. This method involves using a code word that has a corresponding numerical letter placement along with a further shift. 
#### Polyalphabetic Example
Admittedly, I don't fully understand the math behind performing this level of encryption although my mind is really wanting to. Basically, the secret word/code is the integer shift in which to push the letter further away from itself to begin the initial encryption of the message. From there, a further shift is added. Conversely, the subtraction of these shifts will reveal the decrypted message. 
#### Brute-Force
While I do not fully comprehend the math and code used to run this operation, I do understand what is happening. An encrypted message is being run through a program that can reveal the contents of the secret message by argumentatve or boolean function. When a key is called upon to to verify if it matches any of the preloaded symbols within the reference code, it is then returned in some manner as true or false and with its corresponding match. Ultimately, this model runs through all possibilities of decoded in a relentless way, by generating every possible outcome with the given inputs. 

## Conclusion
The transmission of sensitive data is inevitable anymore. We rely on these principles to retain security in how we share information in our current world. The world of mathematics is one that we owe immense thanks to for understanding and creating the foundations of encryption. Like so many other things in our lives, mathematics can generally be found as the reasons/explanations for how things take place, how we can alter outcomes, and even predict results. It is crucial to understand!


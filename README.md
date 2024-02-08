# SQL Injection with Kali Linux

## Abstract

This project report delves into the Denial of Service (DoS) attack detection, leveraging open-source tools and network monitoring techniques. In lieu of traditional machine learning models, the approach focuses on real-time analysis of network traffic using tools like Wireshark, coupled with customized scripts for anomaly detection.

## Introduction

In the interconnected world of today, where our lives are intricately woven into the digital fabric, the threat of cyberattacks looms larger than ever. One particularly disruptive form of cyber threat is the Denial-of-Service (DoS) attack, a malevolent act that renders legitimate users helpless by obstructing access to essential information systems and services.

At its core, a DoS attack disrupts the normal functioning of a computer, network, or service, making it inaccessible to its intended users. The assailant achieves this by overwhelming the targeted host with an excessive amount of traffic, pushing it to the brink until it either cannot respond or succumbs to the sheer volume of data, crashing in the process.

## Common Denial of Service Attacks

There are many different methods for carrying out a DoS attack. The most common method of attack occurs when an attacker floods a network server with traffic. In this type of DoS attack, the attacker sends several requests to the target server, overloading it with traffic. These service requests are illegitimate and have fabricated return addresses, which mislead the server when it tries to authenticate the requestor. As the junk requests are processed constantly, the server is overwhelmed, which causes a DoS condition to legitimate requestors.

- In a Smurf Attack, the attacker sends Internet Control Message Protocol broadcast packets to a number of hosts with a spoofed source Internet Protocol (IP) address that belongs to the target machine. The recipients of these spoofed packets will then respond, and the targeted host will be flooded with those responses.
- A SYN flood attack occurs when an attacker sends a request to connect to the target server but does not complete the connection through what is known as a three-way handshake—a method used in a Transmission Control Protocol (TCP)/IP network to create a connection between a local host/client and server. The incomplete handshake leaves the connected port in an occupied status and unavailable for further requests. An attacker will continue to send requests, saturating all open ports, so that legitimate users cannot connect.

## Conclusion

In conclusion, the project aimed to test network security and determine the overall effects of a denial-of-service attack against a targeted website/network. The project involved testing a denial-of-service SYN flood attack against a targeted system on our local network. We also used virtual machines to set up our testing environment as well as used some tools to analyse the network traffic during the simulation. The results of the project indicate that the detection of denial-of-service attacks is a challenging task, but it is possible to detect them using the mentioned tools. The study also proposes a creative, effective, efficient, and comprehensive prevention and detection of an actual Denial of Service (DoS) attack.

Project done for my professional elective - Offensive Security

## References

1. DoS Attack - Definition, Examples and Prevention (crashtest-security.com)
2. Denial of Service (DoS) guidance - NCSC.GOV.UK
3. Understanding Denial-of-Service Attacks | CISA
4. Denial-of-service attack - Wikipedia

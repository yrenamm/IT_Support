# Network Attacks

## Question 1

*What are the dangers of a man-in-the-middle attack? Check all that apply.*

* **An attacker can block or redirect traffic.**
* **An attacker can eavesdrop on unencrypted traffic.**
* **An attacker can modify traffic in transit.**
* An attacker can destroy data at rest.

> A man-in-the-middle attack means that the attacker has access to your network traffic. This allows them to eavesdrop, modify traffic in transit, or block traffic entirely. Yikes!

## Question 2

*Why is a DNS cache poisoning attack dangerous? Check all that apply.*

* **It allows an attacker to redirect targets to malicious webservers.**
* **It affects any clients querying the poisoned DNS server.**
* Errrr...it's not actually dangerous.
* It allows an attacker to remotely control your computer.

> By inserting fake DNS records into a DNS server's cache, every client that queries this record will be served the fake information. This allows an attacker to redirect clients to a web server of their choosing.

## Question 3

*Which of the following is true of a DDoS attack?*

* This type of attack causes a significant loss of data.
* An attacker sends attack traffic directly to the target.
* Attack traffic is encrypted.
* **Attack traffic comes from lots of different hosts.**

> The "Distributed" in DDoS means that the attack traffic is distributed across a large number of hosts, resulting in the attack coming from many different machines.

## Question 4

*Which of the following result from a denial-of-service attack? Check all that apply.*

* **Slow network performance**
* **Service unreachable**
* Malware infection
* Data destruction

> A denial-of-service attack is meant to prevent legitimate traffic from reaching a service. This is usually done by flooding the victim with attack traffic, degrading network and system performance, and rendering services unreachable.
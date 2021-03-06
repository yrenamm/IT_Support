# Defense in Depth

## Question 1

*While antivirus software operates using a ______, binary whitelisting software uses a whitelist instead.*

* Secure list
* Whitelist
* Greylist
* **Blacklist**

>  Antivirus software operates using a blacklist, which blocks anything that's detected as matching on the list. Binary whitelisting software operates using a whitelist, blocking everything by default, unless it's on the whitelist.

## Question 2

*What does full-disk encryption protect against? Check all that apply.*

* **Data tampering**
* Eavesdropping
* **Data theft**
* Malware 

> Encrypting the entire disk prevents unauthorized access to the data in case it's lost or stolen. It also protects against malicious tampering of the files contained on the disk.

## Question 3

*What does applying software patches protect against? Check all that apply.*

* **Undiscovered vulnerabilities**
* **Newly found vulnerabilities**
* MITM attacks
* Data tampering 

> Software updates or patches can fix recently discovered vulnerabilities or close ones that you weren't aware of.

## Question 4

*How are attack vectors and attack surfaces related?*

* **An attack surface is the sum of all attack vectors.**
* They're the same thing.
* An attack vector is the sum of all attack surfaces.
* They're not actually related. 

> An attack surface is the sum of all attack vectors in a system or environment.

## Question 5

*When looking at aggregated logs, you are seeing a large percentage of Windows hosts connecting to an Internet Protocol (IP) address outside the network in a foreign country. Why might this be worth investigating more closely?*

* It can indicate ACLs are not configured correctly.
* **It can indicate a malware infection.**
* It can indicate log normalization.
* It can indicate what software is on the binary whitelist. 

> When looking at aggregated logs, you should pay attention to patterns and correlations between traffic. For example, if you are seeing a large percentage of hosts all connecting to a specific address outside your network, that might be worth investigating more closely, as it could indicate a malware infection.

## Question 6

*Which of these protects against the most common attacks on the internet via a database of signatures, but at the same time actually represents an additional attack surface that attackers can exploit to compromise systems?*

* Security Information and Event Management (SIEM) system
* **Antivirus software**
* Binary whitelisting software
* Full disk encryption (FDE) 

> Antivirus, which is designed to protect systems, actually represents an additional attack surface that attackers can exploit to compromise systems.

## Question 7

*A hacker exploited a bug in the software and triggered unintended behavior which led to the system being compromised by running vulnerable software. Which of these helps to fix these types of vulnerabilities?*

* **Software patch management**
* Log analysis
* Application policies
* Implicit deny 

> Vulnerabilities can be fixed through software patches and updates which correct the bugs that attackers exploit.

## Question 8

*What is a class of vulnerabilities that are unknown before they are exploited?*

* Attack Vectors
* ACLs
* Attack Surfaces
* **0-days**

> 0-day vulnerabilities are unique in that they are previously unknown before being exploited in the wild.
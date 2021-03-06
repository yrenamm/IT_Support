# Hashing

## Question 1

*How can you defend against brute-force password attacks? Check all that apply.*

* **Incorporate salts into password hashing.**
* **Run passwords through the hashing function multiple times.**
* **Enforce the use of strong passwords.**
* Store passwords in a rainbow table.

> A brute-force password attack involves guessing the password. So, having complex and long passwords will make this task much harder and will require more time and resources for the attacker to succeed. Incorporating salts into password hashes will protect against rainbow table attacks, and running passwords through the hashing algorithm lots of times also raises the bar for an attacker, requiring more resources for each password guess.

## Question 2

*How is a Message Integrity Check (MIC) different from a Message Authentication Code (MAC)?*

* **A MIC only hashes the message, while a MAC incorporates a secret key.**
* A MAC requires a password, while a MIC does not.
* A MIC is more reliable than a MAC.
* They're the same thing.

> A MIC can be thought of as just a checksum or hash digest of a message, while a MAC uses a shared secret to generate the checksum. This also makes it authenticated, since the other party must also have the same shared secret, preventing a third party from forging the checksum data.

## Question 3

*What's a hash collision?*

* **When two different files generate the same hash digest**
* When two identical files generate different hash digests
* When a hash digest is reversed to recover the original
* When two different hashing algorithms produce the same hash

> If two different files result in the same hash, this is referred to as a hash collision. Hash collisions aren't awesome, as this would allow an attacker to create a fake file that would pass hash verification.

## Question 4

*How is hashing different from encryption?*

* **Hashing operations are one-directional.**
* Hashing is meant for large amounts of data, while encryption is meant for small amounts of data.
* It's less secure.
* It's faster.

> Hash functions, by definition, are one-way, meaning that it's not possible to take a hash and recover the input that generated the hash. Encryption, on the other hand, is two-directional, since data can be both encrypted and decrypted.
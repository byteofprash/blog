### Chapter 3

#### Security Designs:
The idea is to map security requriements to mechanisms.

* Least privilege:
  - Every subject should not have more privelges than necessary to complete the given task. Door access control in major corporations for example. This way, we reduce the operating erorrs and hence also reduce the deliberate attacks carried out by the subjects. 
**Eg:** Normal users don't need the web server's admin rights. 
Doors for the server room is not given to the employees.
 
* Complete Mediation: 
  - Access to things must be in a linear defined way. There shouldn't be any other way around to the end goal. 

* Security: Implicit Deny
  - Security mechanisms should start and end in a secure state

* Compartmentalization: 
  - Organize resources into groups isolated from each other. Pretty much like docker for real life

* Minimum Exposure:
  - Minimize the attack surface: Don't give any potential to attack
  - Harden the OS by disabling unneeded functionaltity. Eg FTP ports
  - Eg: In castles there is just 1 entry and not many

* Open Design:
  - Design is secure and open, that there is no need for unnecessary obfuscation or obscurity
  - Eg: AES, RSA

* Economy of Mechanism:
  - Security mechanism must be as simple as possible. When they are simple it's easy to deug and chances of bugs are also low. 
  Eg: Simple by not over engineering.

* Defense in Depth:
  - Security must be deployed in multiple layers so we can. 
  - Eg: 2 factor authentication. 

* Lease common Mechanism:
  Very similar to point "least previlege"

* Psychological acceptability:
  - Systems must be easier to access with the security and not without the security hence users won't be annoyed. 
  eg: Certain bank's security system is too annoying that we use weak passwords or write them on paper.

********* **we have security patters after this to be read and summarized**  *********

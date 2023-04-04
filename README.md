# Dreadnought-Video-Game-Security-Audit

![Screen Shot 2023-04-04 at 5 48 48 PM](https://user-images.githubusercontent.com/83922342/229946668-8178d548-d715-4b31-bd69-49ca013036ea.png)

This repository contains the results of a security audit performed on the Dreadnought video game. The audit identified four critical vulnerabilities that could lead to unauthorized access, data breaches, or other security risks. The vulnerabilities discovered are as follows:

* **SQL Injection Vulnerability:** Affects the user registration system and may expose sensitive user information or enable unauthorized database access.

* **Remote Code Execution (RCE) Vulnerability:** Found in the game's custom web server, allowing attackers to execute arbitrary code on the server.
Insecure File Upload: The game's file upload system lacks proper validation, enabling the upload of malicious files.

* **Unencrypted Network Traffic:** Network traffic between players and the game server is unencrypted, making it susceptible to Man-in-the-Middle (MITM) attacks.


*Detailed information on each vulnerability, along with proposed mitigation strategies, can be found in the full Penetration Testing Report.*

*Developers should address these vulnerabilities promptly and conduct regular security audits to ensure a secure and enjoyable gaming experience.*

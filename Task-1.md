### **The Definitive Cybersecurity Doctrine: 2026 Examination Master Script**

**I. The Core Philosophy: The CIA Triad**
The **CIA Triad** is the benchmark model for evaluating security. A "Secure System" is defined by its ability to maintain these three states simultaneously:

1. **Confidentiality:** Ensuring data is accessible only to authorized parties.
* *Mechanism:* Encryption, MFA, ACLs.
* *Example:* Banking apps using AES-256 encryption so only you and the bank see your statements.


2. **Integrity:** Assurance that data is accurate and has not been modified by unauthorized users.
* *Mechanism:* Hashing (SHA-256), Digital Signatures.
* *Example:* Ensuring a WhatsApp message cannot be altered by a third party while in transit.


3. **Availability:** Ensuring systems and data are accessible when needed.
* *Mechanism:* Redundancy, Load Balancing, DDoS Mitigation.
* *Example:* Ensuring a government tax portal stays online during the filing deadline.



**II. Threat Actor Taxonomy (Motivations & Ethics)**
Actors are classified by their **Sophistication** and their **Ethical "Hat"** color.

* **The "Hats":**
* **White Hat:** Ethical hackers; work with permission to find and fix bugs.
* **Black Hat:** Malicious hackers; break laws for personal gain or destruction.
* **Gray Hat:** Operate without permission; may find bugs illegally but report them ethically.
* **Red Hat:** Vigilante hackers who actively "attack the attacker" to disable them.


* **The Actors:**
* **Script Kiddies:** Low-skill; use pre-made tools. Motivated by ego/notoriety.
* **Insiders:** Employees/Contractors. Dangerous because they are already inside the **Perimeter Defense**.
* **Hacktivists:** Motivated by politics/ideology (e.g., Anonymous).
* **Nation-State Actors:** Government-backed; conduct **Advanced Persistent Threats (APTs)** for espionage.



**III. The Attack Surface & Data Flow**
The **Attack Surface** is the sum of all "entry points" (Web, Mobile, APIs, Network, Cloud). To secure them, we map the **Data Flow**:
**User/Client Interface**  **Network Transit**  **Application Server**  **Database**

* **At the User:** Risk of **Phishing** and **Keyloggers**.
* **In Transit:** Risk of **Man-in-the-Middle (MitM)**. (Mitigation: **TLS 1.3**).
* **At the Server:** Risk of **Injection** and **Logic Flaws**. (Mitigation: **Input Sanitization**).
* **At the Database:** Risk of **Data Breaches**. (Mitigation: **Encryption at Rest**).

**IV. OWASP Top 10: 2025 (Standardized Risks)**

1. **A01: Broken Access Control:** Users acting outside their permissions.
2. **A02: Security Misconfiguration:** Default passwords or open ports.
3. **A03: Software Supply Chain Failures:** Risks from untrusted 3rd-party libraries/dependencies.
4. **A04: Cryptographic Failures:** Use of weak or no encryption for sensitive data.
5. **A05: Injection:** Tricking a server into executing malicious commands (SQLi/XSS).
6. **A06: Insecure Design:** Fundamental flaws in the application's logical architecture.
7. **A07: Authentication Failures:** Weak session management or lack of MFA.
8. **A08: Software and Data Integrity Failures:** Not verifying the source of code or updates.
9. **A09: Security Logging & Alerting Failures:** Failing to detect or alert on a breach.
10. **A10: Mishandling of Exceptional Conditions:** Error messages that leak system info or cause crashes.

**V. Defense Strategy: Layers and Models**

1. **Defense in Depth:** Using multiple, redundant layers of security (e.g., Firewall + Antivirus + Encryption).
2. **Zero Trust Architecture (ZTA):** The modern mantra: *"Never Trust, Always Verify."* No user is trusted by default, regardless of their location.
3. **The Cyber Kill Chain:** Stages of an attack: *Reconnaissance*  *Weaponization*  *Delivery*  *Exploitation*  *Installation*  *Command & Control*.

**VI. Technical Glossary**

* **Vulnerability:** A weakness (the "hole" in the wall).
* **Threat:** The potential for exploitation (the "thief").
* **Risk:** Probability  Impact ().
* **Zero-Day:** A vulnerability for which there is no patch yet.
* **Principle of Least Privilege (PoLP):** Providing users the bare minimum access they need.
* **Payload:** The part of the malware that performs the actual malicious action.
* **Air-Gapping:** Physically isolating a computer from any network for maximum security.

**VII. Summary**
Cybersecurity is the strategic defense of the **CIA Triad** using **Defense in Depth** and **Zero Trust**. By understanding **Threat Actors** and the **Cyber Kill Chain**, we can proactively reduce our **Attack Surface** and mitigate **OWASP Top 10: 2025** risks throughout the entire **Data Flow** cycle.


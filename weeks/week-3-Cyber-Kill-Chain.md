- **Cyber Kill Chain**
- It consists of target identification, decision and order to attack the target, and finally the target destruction.
- It can be used to assess your network and system security by identifying missing security controls and closing certain security gaps based on a company's infrastructure.
- Advanced Persistent Threats (APTs) 
- Attack phases :
- Reconnaissance
- Weaponization
- Delivery
- Exploitation
- Installation
- Command & Control
- Actions on Objectives

-**Reconnaissance** involves identifying and collecting data on systems and victims before launching an attack.
**OSINT** (Open-Source Intelligence) plays a major role, helping attackers gather public information like emails, employee names, and company details.
- Common reconnaissance tactics include email harvesting, used for phishing and other social engineering attacks.
  
- 🛠️ Tools Studied:

- theHarvester: Gathers emails, subdomains, IPs, URLs, and more.
- Hunter.io: Identifies contact details linked to domains.
- OSINT Framework: A categorized collection of OSINT tools.

-**Weaponization Phase**

Summary:
- After Reconnaissance, the attacker ("Megatron") prepares a malicious payload.
- This phase combines malware + exploit into a deliverable package (no direct victim interaction yet).

Key Concepts:
- **Malware**: Malicious software (e.g., viruses, worms).
- **Exploit**: Code that takes advantage of system vulnerabilities.
- **Payload**: The harmful code executed on the victim’s system.
- **Weaponizer**: Tool/method to combine malware and exploit.
- **Backdoor**: Secret way to maintain access to the system.
- **C2 (Command & Control)**: Used for remote access and control after infection.

Common Methods:
- Infected Office docs with **macros/VBA scripts**.
- Dropping **malware-infected USB drives** in public.
- Buying malware from the **Dark Web**.
- Creating custom malware to **evade detection** (used by APTs).

Key Takeaway:
Weaponization is a behind-the-scenes phase where the attacker builds or obtains the tools needed to execute the attack.

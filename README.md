# [h3 Web](https://terokarvinen.com/2024/information-security-2024-spring/#homework)
Homework for week 3



## x) OWASP: OWASP 10 2021

### [A03:2021-Injection](https://owasp.org/Top10/A03_2021-Injection/)

The article is about "Injection," which is when attackers manipulate a computer system by inserting harmful data. This problem ranks third in the list of common security issues, with 94% of applications being tested for it.

When an application doesn't properly check the information it receives from users, attackers can sneak in harmful data. This can lead to various types of attacks, such as Cross-site Scripting (XSS) and SQL Injection, where attackers can manipulate or steal sensitive information.

To prevent this, it's important to keep user data separate from commands and queries in the application's code. Developers can use secure programming practices and tools to make sure the system is resistant to these types of attacks.

For example, when an application uses user-provided data in constructing a database query. If not handled correctly, attackers can manipulate the data to retrieve or modify sensitive information within the system.

### [A06:2021 – Vulnerable and Outdated Components](https://owasp.org/Top10/A06_2021-Vulnerable_and_Outdated_Components/)

This part is about using outdated and vulnerable components in computer systems, which can make them open to attacks. These components include various software parts like frameworks, libraries, and other building blocks of applications.

The analysis shows that nearly 28% of systems are at risk because they use outdated or vulnerable components. The concern arises when users don't keep track of the versions of these components, use software that is outdated or unsupported, or fail to regularly check for and fix vulnerabilities.

To prevent these issues, it's essential to have a process in place for regularly updating and securing all the components used in a system. This includes removing unnecessary parts, keeping track of component versions, and regularly checking for any security issues related to these components.

When attackers exploit vulnerabilities in these components, they can successfully gain unauthorized access or seize control of a system. This emphasizes the importance of keeping all software components up to date to ensure the security of computer systems.

### [A05:2021-Security Misconfiguration](https://owasp.org/Top10/A05_2021-Security_Misconfiguration/)

Security misconfiguration is when computer systems or applications are set up in a way that makes them vulnerable to attacks. This can happen if the security settings are not properly done, such as having weak passwords, leaving unnecessary features enabled, or not updating software regularly.

Based on that article, it was found that about 90% of applications were tested for these misconfigurations, and over 208,000 instances of such vulnerabilities were identified. Common issues include not securing parts of the application, using default passwords, and revealing too much information when errors occur.

To prevent these problems, it's important to follow secure installation processes. This includes making sure all environments (like development and production) are configured the same way with strong security measures. Unnecessary features should be removed, and regular reviews and updates should be done to keep everything secure. Additionally, it's crucial to check and secure cloud storage permissions.

For example, an attacker could take advantage of misconfigurations to compromise a server, access sensitive information, or exploit vulnerabilities. To stay safe, it's essential to have a repeatable and automated process for setting up and maintaining secure configurations.

## Recources:
1. Tero Karvinen homepage. URL: https://terokarvinen.com/2024/information-security-2024-spring/#homework. Accessed: 2.2.2024.
2. OWASP: OWASP 10 2021. A05:2021 – Security Misconfiguration. URL: https://owasp.org/Top10/A05_2021-Security_Misconfiguration/. Accessed: 2.2.2024.
3. OWASP: OWASP 10 2021. A06:2021 – Vulnerable and Outdated Components. URL: https://owasp.org/Top10/A06_2021-Vulnerable_and_Outdated_Components/. Accessed: 2.2.2024.
4. OWASP: OWASP 10 2021. A03:2021 – Injection. URL: https://owasp.org/Top10/A03_2021-Injection/. Accessed: 2.2.2024.

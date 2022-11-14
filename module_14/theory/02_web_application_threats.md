# Section 02: Web Applications Threats

## Web Application Threats
OWASP (Open web application security project)
> The Open Web Application Security Project® (OWASP) is a nonprofit foundation that works to improve the security of software.
> Through community-led open-source software projects, hundreds of local chapters worldwide, tens of thousands of members, and leading educational and training conferences, the OWASP Foundation is the source for developers and technologists to secure the web.

OWASP top 10
> The OWASP Top 10 is a standard awareness document for developers and web application security.
> It represents a broad consensus about the most critical security risks to web applications.

- [A01:2021-Broken Access Control](https://owasp.org/Top10/A01_2021-Broken_Access_Control) moves up from the fifth position; 94% of applications were tested for some form of broken access control. The 34 Common Weakness Enumerations (CWEs) mapped to Broken Access Control had more occurrences in applications than any other category.
- [A02:2021-Cryptographic Failures](https://owasp.org/Top10/A02_2021-Cryptographic_Failures) shifts up one position to #2, previously known as Sensitive Data Exposure, which was broad symptom rather than a root cause. The renewed focus here is on failures related to cryptography which often leads to sensitive data exposure or system compromise.
- [A03:2021-Injection](https://owasp.org/Top10/A03_2021-Injection) slides down to the third position. 94% of the applications were tested for some form of injection, and the 33 CWEs mapped into this category have the second most occurrences in applications. Cross-site Scripting is now part of this category in this edition.
- [A04:2021-Insecure Design](https://owasp.org/Top10/A04_2021-Insecure_Design) is a new category for 2021, with a focus on risks related to design flaws. If we genuinely want to “move left” as an industry, it calls for more use of threat modeling, secure design patterns and principles, and reference architectures.
- [A05:2021-Security Misconfiguration](https://owasp.org/Top10/A05_2021-Security_Misconfiguration) moves up from #6 in the previous edition; 90% of applications were tested for some form of misconfiguration. With more shifts into highly configurable software, it’s not surprising to see this category move up. The former category for XML External Entities (XXE) is now part of this category.
- [A06:2021-Vulnerable and Outdated Components](https://owasp.org/Top10/A06_2021-Vulnerable_and_Outdated_Components) was previously titled Using Components with Known Vulnerabilities and is #2 in the Top 10 community survey, but also had enough data to make the Top 10 via data analysis. This category moves up from #9 in 2017 and is a known issue that we struggle to test and assess risk. It is the only category not to have any Common Vulnerability and Exposures (CVEs) mapped to the included CWEs, so a default exploit and impact weights of 5.0 are factored into their scores.
- [A07:2021-Identification and Authentication Failures](https://owasp.org/Top10/A07_2021-Identification_and_Authentication_Failures) was previously Broken Authentication and is sliding down from the second position, and now includes CWEs that are more related to identification failures. This category is still an integral part of the Top 10, but the increased availability of standardized frameworks seems to be helping.
- [A08:2021-Software and Data Integrity Failures](https://owasp.org/Top10/A08_2021-Software_and_Data_Integrity_Failures) is a new category for 2021, focusing on making assumptions related to software updates, critical data, and CI/CD pipelines without verifying integrity. One of the highest weighted impacts from Common Vulnerability and Exposures/Common Vulnerability Scoring System (CVE/CVSS) data mapped to the 10 CWEs in this category. Insecure Deserialization from 2017 is now a part of this larger category.
- [A09:2021-Security Logging and Monitoring Failures](https://owasp.org/Top10/A09_2021-Security_Logging_and_Monitoring_Failures) was previously Insufficient Logging & Monitoring and is added from the industry survey (#3), moving up from #10 previously. This category is expanded to include more types of failures, is challenging to test for, and isn’t well represented in the CVE/CVSS data. However, failures in this category can directly impact visibility, incident alerting, and forensics.
- [A10:2021-Server-Side Request Forgery](https://owasp.org/Top10/A10_2021-Server-Side_Request_Forgery_%28SSRF%29) is added from the Top 10 community survey (#1). The data shows a relatively low incidence rate with above average testing coverage, along with above-average ratings for Exploit and Impact potential. This category represents the scenario where the security community members are telling us this is important, even though it’s not illustrated in the data at this time.

SQL (Structured query language) injection
> In computing, SQL injection is a code injection technique used to attack data-driven applications, in which malicious SQL statements are inserted into an entry field for execution (e.g. to dump the database contents to the attacker).

Command injection
> Command injection is a cyber attack that involves executing arbitrary commands on a host operating system (OS).
> Typically, the threat actor injects the commands by exploiting an application vulnerability, such as insufficient input validation.

XSS (Cross site scripting)
> Cross-site scripting (XSS) is a type of security vulnerability that can be found in some web applications.
> XSS attacks enable attackers to inject client-side scripts into web pages viewed by other users.

Cross site request forgery
> Cross-site request forgery, also known as one-click attack or session riding and abbreviated as CSRF (sometimes pronounced sea-surf) or XSRF, is a type of malicious exploit of a website or web application where unauthorized commands are submitted from a user that the web application trusts.

XML (extensible markup language)
> Extensible Markup Language (XML) is a markup language and file format for storing, transmitting, and reconstructing arbitrary data.
> It defines a set of rules for encoding documents in a format that is both human-readable and machine-readable

XXE (XML external entity) attack
> XML External Entity attack (XXE attack) is a type of attack against an application that parses XML input.
> This attack occurs when XML input containing a reference to an external entity is processed by a weakly configured XML parser.
> This attack may lead to the disclosure of confidential data, denial of service (DoS), server side request forgery, port scanning from the perspective of the machine where the parser is located, and other system impacts.

Directory traversal
> A directory traversal (or path traversal) attack exploits insufficient security validation or sanitization of user-supplied file names, such that characters representing "traverse to parent directory" are passed through to the operating system's file system API.
> An affected application can be exploited to gain unauthorized access to the file system.

Watering hole attack
> Watering hole is a computer attack strategy in which an attacker guesses or observes which websites an organization often uses and infects one or more of them with malware.
> Eventually, some member of the targeted group will become infected.

Session poisoning
> Session poisoning (also referred to as "session data pollution" and "session modification") is a method to exploit insufficient input validation within a server application.
> Typically a server application that is vulnerable to this type of exploit will copy user input into session variables.

Clickjacking
> Clickjacking (classified as a user interface redress attack or UI redressing) is a malicious technique of tricking a user into clicking on something different from what the user perceives, thus potentially revealing confidential information or allowing others to take control of their computer while clicking on seemingly innocuous objects, including web pages.

Pass the hash
> In computer security, pass the hash is a hacking technique that allows an attacker to authenticate to a remote server or service by using the underlying NTLM or LanMan hash of a user's password, instead of requiring the associated plaintext password as is normally the case.
> It replaces the need for stealing the plaintext password to gain access with stealing the hash.

Links
- [https://owasp.org](https://owasp.org)
- [https://owasp.org/www-project-top-ten](https://owasp.org/www-project-top-ten)
- [https://en.wikipedia.org/wiki/SQL_injection](https://en.wikipedia.org/wiki/SQL_injection)
- [https://en.wikipedia.org/wiki/Cross-site_scripting](https://en.wikipedia.org/wiki/Cross-site_scripting)
- [https://en.wikipedia.org/wiki/Cross-site_request_forgery](https://en.wikipedia.org/wiki/Cross-site_request_forgery)
- [https://en.wikipedia.org/wiki/XML](https://en.wikipedia.org/wiki/XML)
- [https://en.wikipedia.org/wiki/XML_external_entity_attack](https://en.wikipedia.org/wiki/XML_external_entity_attack)
- [https://en.wikipedia.org/wiki/Directory_traversal_attack](https://en.wikipedia.org/wiki/Directory_traversal_attack)
- [https://en.wikipedia.org/wiki/Watering_hole_attack](https://en.wikipedia.org/wiki/Watering_hole_attack)
- [https://en.wikipedia.org/wiki/Session_poisoning](https://en.wikipedia.org/wiki/Session_poisoning)
- [https://en.wikipedia.org/wiki/Clickjacking](https://en.wikipedia.org/wiki/Clickjacking)
- [https://en.wikipedia.org/wiki/Pass_the_hash](https://en.wikipedia.org/wiki/Pass_the_hash)

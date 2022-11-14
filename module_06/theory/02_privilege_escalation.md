# Section 02: Privilege Escalation

## Privilege Escalation
Privilege escalation
> Privilege escalation is the act of exploiting a bug, a design flaw, or a configuration oversight in an operating system or software application to gain elevated access to resources that are normally protected from an application or user.

There are two types of privilege escalation
- horizontal privilege escalation
- vertical privilege escalation

LinPeas
> LinPEAS is a script that search for possible paths to escalate privileges on Linux/Unix*/MacOS hosts. The checks are explained on book.hacktricks.xyz

LinEnum
> Linux privilege escalation script.

Defenses against privilege escalation
- Run services using unprivileged accounts.
- Regularly patch the OS/kernel.
- Keep as many files as read only as possible.
- Implement strong password policy.

Links
- [https://en.wikipedia.org/wiki/Privilege_escalation](https://en.wikipedia.org/wiki/Privilege_escalation)
- [https://github.com/carlospolop/PEASS-ng/tree/master/linPEAS](https://github.com/carlospolop/PEASS-ng/tree/master/linPEAS)
- [https://github.com/rebootuser/LinEnum](https://github.com/rebootuser/LinEnum)

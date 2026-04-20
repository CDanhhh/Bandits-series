# Bandit Series - OverTheWire Wargames

A complete walkthrough of the renowned [Bandit](https://overthewire.org/wargames/bandit/) CTF challenge series by OverTheWire.

## Overview

Bandit is the foundational wargame on OverTheWire, designed to teach Linux fundamentals, security concepts, and penetration testing through progressive levels. This repository documents my systematic approach to solving levels 27-31.

## Skills Demonstrated

| Category | Technologies |
|----------|-------------|
| **System Exploration** | File system navigation, process analysis, service discovery |
| **Scripting** | Bash scripting, automation, cron jobs |
| **Networking** | SSH, port scanning, netcat,Reverse Shells |
| **Cryptography** | Encoding (Base64, Rot13), hash analysis |
| **Privilege Escalation** | Sudo misconfigurations, SUID binaries, permission abuse |
| **Security Auditing** | Code review, vulnerability identification |

## Approach

Each level required:

1. **Enumeration** - Identifying available resources and potential attack vectors
2. **Analysis** - Understanding the security mechanism in place
3. **Exploitation** - Developing a working payload to retrieve the credentials
4. **Documentation** - Recording the methodology for future reference

## Key Takeaways

- **Persistence wins** - Many challenges require multiple attempts and creative thinking
- **Tool mastery** - Shell commands, grep, awk, and piping are essential
- **Security mindset** - Thinking like an attacker to find vulnerabilities
- **Documentation** - Clear notes accelerate future problem-solving

## Level Breakdown

| Level | Focus Area |
|-------|------------|
| 27 | Git repository analysis |
| 28 | Git internals, credentials exposure |
| 29 | Git branches, commit history |
| 30 | Git submodules, bare repositories |
| 31 | Git push, remote repository interaction |

## Tools & Environment

- **OS**: Kali Linux / Ubuntu
- **Key Tools**: git, ssh, scp, bash, grep, awk, netcat
- **Version Control**: Git (local + remote)

## References

- [OverTheWire Bandit](https://overthewire.org/wargames/bandit/)
- [Bandit Wiki](https://wiki.overthewire.org/solutions/bandit/)

---

*"Security is not a product, but a process."* — Bruce Schneier
# 🔐 Awesome Cybersecurity Tools & Resources

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
[![Track Awesome List](https://www.trackawesomelist.com/badge.svg)](https://www.trackawesomelist.com/guidryheal-create/awesome-offensive-security)
[![Last Commit](https://img.shields.io/github/last-commit/guidryheal-create/awesome-offensive-security)](https://github.com/guidryheal-create/awesome-offensive-security/commits)
[![Contributions Welcome](https://img.shields.io/badge/contributions-welcome-brightgreen.svg)](CONTRIBUTING.md)
[![License](https://img.shields.io/github/license/guidryheal-create/awesome-offensive-security)](LICENSE)
[![Maintenance](https://img.shields.io/badge/maintained-yes-green.svg)]()

> A comprehensive, professionally curated collection of cybersecurity tools, frameworks, resources, and learning materials for penetration testers, red teamers, security researchers, and defensive practitioners. Organized by category with detailed descriptions for easy discovery and learning.

## 📋 About This List

This repository provides a meticulously organized collection of **400+ cybersecurity resources** across **30+ categories**, from offensive security tools to defensive frameworks. Whether you're starting your journey in cybersecurity or looking for specialized advanced tools, you'll find curated recommendations with clear descriptions of each tool's purpose and capabilities.

**Key Features:**
- ✅ **Tool-focused** - Primarily GitHub repositories and open-source projects
- ✅ **Resource-rich** - Learning platforms, databases, and documentation
- ✅ **Well-organized** - 30+ categories with modular structure
- ✅ **Professional descriptions** - Each entry includes detailed context
- ✅ **Actively maintained** - Regular updates and community contributions welcome

---

## 🚀 Quick Start - Essential Tools

New to security? Start here with the most fundamental and widely-used tools:

### Reconnaissance & Enumeration
- **[Nmap](https://github.com/nmap/nmap)** - The standard network discovery and enumeration tool. Essential for any security professional.
- **[Amass](https://github.com/OWASP/Amass)** - OWASP's comprehensive attack surface mapping and asset discovery platform.
- **[SpiderFoot](https://github.com/smicallef/spiderfoot)** - Automated OSINT collection and intelligence gathering.

### Exploitation & Frameworks
- **[Metasploit Framework](https://github.com/rapid7/metasploit-framework)** - The industry standard penetration testing framework with thousands of exploits.
- **[PayloadsAllTheThings](https://github.com/swisskyrepo/PayloadsAllTheThings)** - Essential payload collection for web application testing and exploitation.

### Web Application Security
- **[PortSwigger Academy](https://portswigger.net/web-security/all-labs)** - Learn web security with interactive labs (free tier available).
- **[OWASP Top 10 Tools](https://owasp.org/)** - Resources for the most critical web vulnerabilities.

### Reverse Engineering & Analysis
- **[Ghidra](https://github.com/NationalSecurityAgency/ghidra)** - NSA's powerful reverse engineering framework for binary analysis.
- **[Radare2](https://github.com/radare/radare2)** - UNIX-like reverse engineering framework.

### Network Security
- **[Zeek](https://github.com/zeek/zeek)** - Network security monitor for threat detection and analysis.
- **[Suricata](https://github.com/OISF/suricata)** - High-performance IDS/IPS/NSM engine.

### Learning & Practice
- **[Vulhub](https://github.com/vulhub/vulhub)** - Pre-built vulnerable environments for hands-on practice.
- **[HackTheBox](https://www.hackthebox.com/)** - Interactive platform for learning and practicing hacking skills.
- **[TryHackMe](https://tryhackme.com/)** - Beginner-friendly security training platform.

---

## 📑 Complete Category Index

### 🛠️ Tools by Category

#### Offensive Security Tools

| Category | Purpose | Tools |
|----------|---------|-------|
| **Core Frameworks** | Comprehensive exploitation and penetration testing platforms | [View All](doc/core-frameworks.md) - Metasploit, Empire, Sliver, Mythic |
| **Payloads & Exploitation** | Payload collections, exploitation techniques, and post-exploitation tools | [View All](doc/payloads-exploitation.md) - PayloadsAllTheThings, PEASS-ng |
| **Reconnaissance & OSINT** | Intelligence gathering and open-source information collection | [View All](doc/recon-osint.md) - Amass, SpiderFoot, theHarvester, Sherlock |
| **Network Scanning** | Port scanning, network enumeration, and discovery tools | [View All](doc/network-scanning.md) - Nmap, RustScan, Masscan, ZMap |
| **Web Security & Fuzzing** | Web application testing, vulnerability discovery, and fuzzing | [View All](doc/web-security-fuzzing.md) - XSStrike, Corsy, Gobuster, FuzzDB |
| **Exploit Development** | Reverse engineering, binary analysis, and exploit development | [View All](doc/exploit-development.md) - Pwntools, Ghidra, Radare2, Pwndbg |
| **Credential Attacks** | Password cracking, credential testing, and authentication bypass | [View All](doc/credential-attacks.md) - Hate_Crack, Gocrack, JWT Cracker |
| **Command & Control** | C2 frameworks for post-exploitation communications | [View All](doc/c2.md) - TrevorC2, Dnscat2, Sliver, Empire |
| **Red Team Operations** | Automated exploitation, red team toolkits, and operational frameworks | [View All](doc/red-team-toolkits.md) - Osmedeus, AutoRecon, Sn1per |
| **Active Directory** | Windows domain exploitation and lateral movement | [View All](doc/active-directory.md) - CrackMapExec, Impacket, NoPac |

#### Security Analysis & Detection

| Category | Purpose | Tools |
|----------|---------|-------|
| **Cloud & Container Security** | Vulnerability scanning for cloud infrastructure and containers | [View All](doc/cloud-container-security.md) - Trivy, CloudHunter, Docker Bench |
| **Malware Analysis & Forensics** | Memory forensics, malware analysis, and incident response | [View All](doc/malware-forensics.md) - Volatility, Ghidra, FLARE-VM |
| **Threat Hunting & Detection** | Network monitoring, threat detection, and security monitoring | [View All](doc/threat-hunting.md) - Zeek, Suricata, Osquery, CrowdSec |
| **Vulnerability Scanning** | Automated vulnerability discovery and assessment | [View All](doc/vulnerability-scanners.md) - Nuclei, Tsunami, Vuls |
| **MITM & Traffic Analysis** | Network traffic interception and analysis | [View All](doc/mitm-traffic.md) - Mitmproxy, Stenographer, Ngrep |
| **SSL/TLS & Crypto Analysis** | Certificate and encryption protocol testing | [View All](doc/ssl-crypto.md) - TestSSL.sh, SSLyze, Cipherscan |
| **DevSecOps & Code Security** | Secret detection, code analysis, and secure development | [View All](doc/devsecops.md) - Gitleaks, CodeQL, Shhgit |

#### Specialized & Advanced

| Category | Purpose | Tools |
|----------|---------|-------|
| **Wireless & Hardware** | RF security, hardware hacking, and wireless testing | [View All](doc/wireless-hardware.md) - MagSpoof, Flipper Zero, IMSI-catcher |
| **Rootkits & Kernel** | Advanced kernel-level malware and rootkit development | [View All](doc/rootkits.md) - Diamorphine, Reptile, R77 Rootkit |
| **AI & Automation** | AI-powered security tools and automated analysis | [View All](doc/ai-automation.md) - PentestGPT, Pentest AI Agents |

### 📚 Learning & Resources

| Category | Purpose | Resources |
|----------|---------|-----------|
| **Learning Platforms** | Training courses and educational platforms | [View All](doc/learning-platforms.md) - Hackers Arise, NetworkChuck, David Bombal |
| **Knowledge Bases** | Comprehensive security guides and references | [View All](doc/knowledge-bases.md) - PortSwigger Academy, Internal All The Things |
| **Labs & Practice** | Vulnerable environments for hands-on practice | [View All](doc/labs-practice.md) - Vulhub, Metasploitable3, OWASP Shepherd |
| **Cheat Sheets** | Quick reference guides and command collections | [View All](doc/cheat-sheets.md) - SecLists, PayloadsAllTheThings, PEASS-ng |
| **CVE Databases** | Vulnerability repositories and exploit collections | [View All](doc/exploits-cves.md) - Exploit-DB, NVD, OpenCVE |
| **OSINT Resources** | OSINT tools, databases, and reconnaissance platforms | [View All](doc/osint-resources.md) - Censys, Shodan, ZoomEye |
| **Threat Intelligence** | Security news, advisories, and threat research | [View All](doc/threat-intelligence.md) - CyberNews, Vulnu |
| **GitHub Security** | GitHub-specific security advisories and tools | [View All](doc/github-security.md) - GitHub Security Lab, CodeQL |
| **Standards & Frameworks** | Security frameworks, standards, and governance | [View All](doc/standards-governance.md) - CISA, NSA, ISO Standards |

### 🔗 See All Categories

**Tools (30+ categories):**
- [Core Frameworks & Platforms](doc/core-frameworks.md)
- [Payloads, Exploitation & Post-Exploitation](doc/payloads-exploitation.md)
- [Reconnaissance & OSINT](doc/recon-osint.md)
- [Network Scanning & Enumeration](doc/network-scanning.md)
- [Web Security & Fuzzing](doc/web-security-fuzzing.md)
- [Exploit Development & Reverse Engineering](doc/exploit-development.md)
- [Credential Attacks & Cracking](doc/credential-attacks.md)
- [Command & Control (C2)](doc/c2.md)
- [Cloud & Container Security](doc/cloud-container-security.md)
- [Malware Analysis & Forensics](doc/malware-forensics.md)
- [Threat Hunting & Detection](doc/threat-hunting.md)
- [Vulnerability Scanners](doc/vulnerability-scanners.md)
- [MITM & Traffic Analysis](doc/mitm-traffic.md)
- [Red Team Toolkits & Automation](doc/red-team-toolkits.md)
- [Active Directory & Lateral Movement](doc/active-directory.md)
- [SSL / TLS / Crypto Analysis](doc/ssl-crypto.md)
- [DevSecOps & Code Security](doc/devsecops.md)
- [AI & Automation in Security](doc/ai-automation.md)
- [Wireless / Hardware / RF](doc/wireless-hardware.md)
- [Rootkits & Kernel-Level](doc/rootkits.md)
- [Labs, Practice & Vulnerable Apps](doc/labs-practice.md)
- [Cheat Sheets & Knowledge](doc/cheat-sheets.md)

**Resources & Learning (15+ categories):**
- [Learning Platforms & Courses](doc/learning-platforms.md)
- [Knowledge Bases & Cheatsheets](doc/knowledge-bases.md)
- [Pentesting & Offensive Security Tools Docs](doc/pentesting-docs.md)
- [Awesome Lists](doc/awesome-lists.md)
- [Exploits, CVEs & Vulnerability Databases](doc/exploits-cves.md)
- [OSINT & Reconnaissance Resources](doc/osint-resources.md)
- [Forensics & Incident Response Resources](doc/forensics-resources.md)
- [Standards, Frameworks & Governance](doc/standards-governance.md)
- [Threat Intelligence & Security News](doc/threat-intelligence.md)
- [GitHub Security & Advisories](doc/github-security.md)
- [AI, Automation & Modern Security Resources](doc/ai-modern-security.md)
- [DevOps, Infra & Engineering](doc/devops-infra.md)
- [Detection Engineering & Rules](doc/detection-engineering.md)
- [Research & Academic Sources](doc/research-academic.md)
- [Misc / Low-Level / Systems](doc/misc-systems.md)

---

## 🎯 Roadmaps by Role

### 🔴 Red Team / Offensive Security
Focus on exploitation, persistence, and evasion:
1. **Foundation** → Nmap + Metasploit + Burp Suite
2. **Recon** → Amass + SpiderFoot + theHarvester
3. **Exploitation** → PayloadsAllTheThings + Exploit-DB
4. **Post-Exploitation** → CrackMapExec + Impacket + Empire
5. **Advanced** → C2 Frameworks (Sliver, Mythic) + Custom Malware Development

**Key Resources:** [Red Team Toolkits](doc/red-team-toolkits.md) | [Active Directory](doc/active-directory.md) | [Rootkits](doc/rootkits.md)

### 🔵 Blue Team / Defensive Security
Focus on detection, analysis, and defense:
1. **Foundation** → Zeek + Suricata + Osquery
2. **Malware Analysis** → Volatility + Ghidra + FLARE-VM
3. **Threat Hunting** → CrowdSec + Maltrail
4. **SIEM/Detection** → Detection Engineering with YARA rules
5. **Advanced** → Incident Response + Forensics

**Key Resources:** [Threat Hunting](doc/threat-hunting.md) | [Malware Forensics](doc/malware-forensics.md) | [Detection Engineering](doc/detection-engineering.md)

### 🟣 Security Researcher / Exploit Developer
Focus on analysis, reverse engineering, and research:
1. **Foundation** → Ghidra + Radare2 + GDB
2. **Binary Analysis** → Pwntools + Pwndbg + Capstone
3. **Vulnerability Research** → Finding and analyzing CVEs
4. **Proof-of-Concept** → Exploit development techniques
5. **Advanced** → Kernel exploitation + Hardware hacking

**Key Resources:** [Exploit Development](doc/exploit-development.md) | [Labs & Practice](doc/labs-practice.md) | [Research Sources](doc/research-academic.md)

### 🟡 Security Beginner
Start with fundamentals and build progressively:
1. **Learn Basics** → Networking + Linux fundamentals
2. **First Tools** → Nmap + Burp Suite + VulnHub
3. **Web Security** → PortSwigger Academy labs
4. **CTF Competitions** → HackTheBox + TryHackMe
5. **Specialization** → Choose your area of interest

**Key Resources:** [Learning Platforms](doc/learning-platforms.md) | [Knowledge Bases](doc/knowledge-bases.md) | [Labs & Practice](doc/labs-practice.md)

---

## 🎓 Learning Paths by Topic

- **Web Application Security** → [Web Security & Fuzzing](doc/web-security-fuzzing.md) + [Knowledge Bases](doc/knowledge-bases.md) + [Exploits/CVEs](doc/exploits-cves.md)
- **Network Security** → [Network Scanning](doc/network-scanning.md) + [Threat Hunting](doc/threat-hunting.md) + [SSL/TLS Analysis](doc/ssl-crypto.md)
- **Reverse Engineering** → [Exploit Development](doc/exploit-development.md) + [Malware Forensics](doc/malware-forensics.md) + [Labs](doc/labs-practice.md)
- **Cloud Security** → [Cloud & Container Security](doc/cloud-container-security.md) + [DevSecOps](doc/devsecops.md)
- **OSINT** → [Reconnaissance & OSINT](doc/recon-osint.md) + [OSINT Resources](doc/osint-resources.md)

---

## 💡 How to Use This List

1. **For Quick Lookup** → Use the Quick Start section or role-based roadmaps
2. **For Deep Dives** → Navigate to specific category documentation in `/doc` folder
3. **For Learning** → Check learning platforms and practice labs
4. **For Reference** → Use cheat sheets and knowledge bases
5. **For Research** → Consult CVE databases, academic sources, and threat intelligence

---

## 🤝 Contributing

Contributions are welcome! Please read [CONTRIBUTING.md](CONTRIBUTING.md) for guidelines on:
- Adding new tools (must be open-source and actively maintained)
- Improving descriptions and documentation
- Reporting dead links
- Organizing resources by category

---

## 📄 License

This project is licensed under the [MIT License](LICENSE). See LICENSE file for details.

---

## 🎯 Suggested Usage Strategy

Don't try to use everything. That's a trap.

* **Start with:** **Nmap + Metasploit + Burp (not listed but essential)**
* **Add recon:** Amass + SpiderFoot
* **Add exploitation:** PayloadsAllTheThings
* **Then specialize:**
  * 🔴 **Red Team** → C2 + AD tools + Red Team Toolkits
  * 🔵 **Blue Team** → Zeek + Suricata + Volatility
  * 🟣 **Research** → Ghidra + pwntools + Exploit-DB

---

## 📞 Support & Questions

- **Found a broken link?** → Open an issue with the URL and category
- **Have a tool suggestion?** → Create a pull request with the tool details
- **Questions about content?** → Check existing issues or create a new discussion

---

## 🔗 Related Awesome Lists

- [Awesome Pentest](https://github.com/enaqx/awesome-pentest)
- [Awesome Red Teaming](https://github.com/HildeTeamTNT/Awesome-Red-Teaming)
- [Awesome Hacking](https://github.com/Hack-with-Github/Awesome-Hacking)
- [Awesome OSINT](https://github.com/jivoi/awesome-osint)

---

**Last Updated:** 2026 | **Maintained by:** Security Community | **PRs Welcome**
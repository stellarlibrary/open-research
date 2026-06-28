# 18. Cybersecurity & Information Assurance

## Degree Programs

| Level | Programs |
|---|---|
| Undergraduate | Cybersecurity (BS), Information Security, Computer Science with Security concentration |
| Masters | MS in Cybersecurity, MS in Information Security, MS in Digital Forensics, MS in Security Engineering, MSCS with Security focus |
| PhD | Computer Science (security specialization), Cybersecurity (emerging programs) |

**Note:** Cybersecurity is the practice and science of protecting systems, networks, and data from digital attacks. As a standalone academic discipline it's relatively young — most deep research lives within CS departments — but dedicated programs have expanded rapidly due to workforce demand. The field spans from deep mathematical foundations (cryptography) to hands-on operations (incident response, penetration testing).

---

## 18.1 Core Curriculum (Undergraduate)

### Foundation
Programming (C, Python, systems-level), Computer Architecture, Operating Systems, Networking — same CS core, plus:

### Core Cybersecurity Courses

| Course | Content |
|---|---|
| **Introduction to Cybersecurity** | CIA triad (confidentiality, integrity, availability), threat landscape, attack types, security principles, defense in depth, risk management frameworks |
| **Cryptography** | Symmetric encryption (AES, DES), asymmetric encryption (RSA, ECC, Diffie-Hellman), hash functions (SHA, HMAC), digital signatures, PKI/certificates, key management, TLS/SSL |
| **Network Security** | Firewalls, IDS/IPS, VPN, network protocols security (DNS, BGP, TLS), DDoS defense, network monitoring, packet analysis (Wireshark), wireless security |
| **Operating Systems Security** | Access control models (DAC, MAC, RBAC), OS hardening, privilege escalation, buffer overflows, secure boot, sandboxing, Linux security modules (SELinux, AppArmor) |
| **Web Application Security** | OWASP Top 10, injection attacks (SQL, XSS, CSRF), authentication/session management, secure coding practices, web application firewalls, API security |
| **Malware Analysis** | Types (viruses, worms, trojans, ransomware, rootkits), static/dynamic analysis, reverse engineering (assembly, debuggers), behavioral analysis, sandbox environments |
| **Digital Forensics** | Evidence acquisition, chain of custody, disk forensics, memory forensics, network forensics, mobile forensics, forensic tools (Autopsy, FTK, Volatility), legal considerations |
| **Security Operations** | SIEM (Splunk, ELK), log analysis, incident response lifecycle (NIST), threat intelligence, SOC operations, vulnerability management, patch management |
| **Ethics & Law** | Computer fraud laws (CFAA), privacy regulations (GDPR, HIPAA, CCPA), ethical hacking scope, responsible disclosure, cyber warfare law, intellectual property |

**Key Textbooks:**
- Stallings & Brown – *Computer Security: Principles and Practice*
- Paar & Pelzl – *Understanding Cryptography*
- Katz & Lindell – *Introduction to Modern Cryptography*
- Tanenbaum & Wetherall – *Computer Networks* (security chapters)
- Sikorski & Honig – *Practical Malware Analysis*
- Kim & Solomon – *Fundamentals of Information Systems Security*
- Anderson – *Security Engineering*

---

## 18.2 Graduate / Advanced Specialization Areas

#### A. Cryptography
- Post-quantum cryptography (lattice-based, code-based, hash-based, isogeny-based), multi-party computation (MPC), fully homomorphic encryption (FHE), zero-knowledge proofs (ZKPs, zk-SNARKs, zk-STARKs), attribute-based encryption, functional encryption, blockchain cryptography, formal verification of cryptographic protocols

#### B. Systems Security
- OS kernel security, browser security, hardware security (side-channel attacks — Spectre, Meltdown, Rowhammer), trusted execution environments (SGX, TrustZone, SEV), binary analysis, fuzzing (AFL, libFuzzer), program analysis for security, secure compilation, memory safety (Rust, CHERI)

#### C. Network & Infrastructure Security
- SDN security, cloud security (IAM, container security, serverless), 5G security, IoT security, critical infrastructure protection (SCADA/ICS), BGP security (RPKI), DNS security (DNSSEC), traffic analysis defense, censorship resistance (Tor)

#### D. Software Security
- Static analysis for vulnerabilities, symbolic execution, taint analysis, secure software development lifecycle (SSDLC), DevSecOps, supply chain security (SBOMs, dependency analysis), vulnerability discovery and disclosure, bug bounty

#### E. AI Security & Adversarial ML
- Adversarial examples, model poisoning/backdoor attacks, model stealing/extraction, deepfakes and detection, LLM security (prompt injection, jailbreaking), AI for security (ML-based detection), security of AI systems

#### F. Privacy & Anonymity
- Differential privacy (mechanisms, composition), federated learning security, anonymous communication (Tor, mixnets), metadata protection, private information retrieval, privacy regulations compliance engineering, de-identification

#### G. Digital Forensics & Incident Response
- Advanced disk/memory/network forensics, cloud forensics, anti-forensics techniques, threat hunting, APT analysis, DFIR automation, forensic readiness, cryptocurrency tracing

#### H. Offensive Security / Red Team
- Penetration testing methodology, exploit development, social engineering, red team operations, adversary simulation (MITRE ATT&CK), vulnerability research, fuzzing, responsible disclosure

---

## 18.3 Key Methods & Tools

| Category | Examples |
|---|---|
| **Penetration Testing** | Metasploit, Burp Suite, Nmap, SQLMap, Cobalt Strike, BloodHound (AD), Impacket |
| **Forensics** | Autopsy/Sleuth Kit, Volatility, FTK, EnCase, Cellebrite (mobile), Wireshark |
| **Malware Analysis** | IDA Pro, Ghidra, x64dbg, YARA, Cuckoo Sandbox, REMnux |
| **SIEM / Monitoring** | Splunk, Elastic/ELK Stack, Microsoft Sentinel, Suricata, Zeek (Bro) |
| **Vulnerability Scanning** | Nessus, Qualys, OpenVAS, Nuclei |
| **Cloud Security** | AWS Security Hub, Azure Defender, GCP Security Command Center, Prowler, ScoutSuite |
| **Crypto Libraries** | OpenSSL, libsodium, BouncyCastle, PyCryptodome |
| **Fuzzing** | AFL++, libFuzzer, Honggfuzz, OSS-Fuzz |
| **Frameworks** | NIST CSF, MITRE ATT&CK, OWASP, CIS Benchmarks, ISO 27001 |

---

## 18.4 Foundational Texts

### Core Textbooks

#### Undergraduate Core

| Subject | Standard text | Notes |
|---|---|---|
| Broad Security | Anderson — *Security Engineering* | Standard broad systems/security text |
| Intro Security | Stallings & Brown — *Computer Security* | Common undergraduate survey |
| Cryptography | Katz & Lindell — *Introduction to Modern Cryptography* | Standard crypto text |
| Applied Cryptography | Paar & Pelzl — *Understanding Cryptography* | Common implementation-oriented text |
| Network Security | Kaufman, Perlman & Speciner — *Network Security* | Standard networking-security text |
| Malware Analysis | Sikorski & Honig — *Practical Malware Analysis* | Standard defensive malware text |
| Web Security | Stuttard & Pinto — *The Web Application Hacker's Handbook* | Common web-security text |
| Forensics | Casey — *Digital Evidence and Computer Crime* | Standard forensics text |

#### Graduate / Reference Texts

| Subject | Standard text | Notes |
|---|---|---|
| Modern Crypto | Boneh & Shoup — *A Graduate Course in Applied Cryptography* | Standard free graduate reference |
| Systems Security | Rossow / Provos / Paxson literature stack | Standard paper-driven area |
| Privacy | Dwork & Roth — *The Algorithmic Foundations of Differential Privacy* | Canonical DP text |
| Binary Analysis | Egele / Schwartz / Balakrishnan review literature | Paper-driven domain |
| Software Security | Dowd, McDonald & Schuh — *The Art of Software Security Assessment* | Standard secure-software reference |

### Recommended Papers

#### Classic / Foundational
- Bell & LaPadula (1973/1976) — multilevel security model.
- Lampson (1974) — protection.
- Saltzer & Schroeder (1975) — protection principles.
- Denning (1976) — lattice model of secure information flow.
- Diffie & Hellman (1976) — new directions in cryptography.
- Rivest, Shamir & Adleman (1978) — RSA.
- Needham & Schroeder (1978) — authentication protocol.
- Lamport (1981) — password authentication over insecure channels.
- Thompson (1984) — trusting-trust supply-chain attack.
- Cohen (1987) — computer viruses theory and experiments.

#### Methods / Canonical Frameworks
- Lampson et al. — authentication in distributed systems.
- Burrows, Abadi & Needham (1989) — BAN logic.
- Miller, Fredriksen & So (1990) — fuzz testing.
- Lowe (1995) — model-checking attack on Needham-Schroeder.
- Forrest et al. (1996) — anomaly detection through short system-call sequences.
- Bleichenbacher (1998) and Vaudenay (2002) — padding-oracle / chosen-ciphertext implementation attacks.
- Paxson (1999) — Bro network intrusion detection foundations.
- Song, Wagner & Perrig (2000) — timing attacks on SSH.
- Sweeney (2002) — k-anonymity.
- Provos (2003) — honeyd / deception foundations.
- Dwork (2006) — differential privacy.
- Narayanan & Shmatikov (2008) — robust de-anonymization results.

#### Modern Field-Defining Results
- Boneh, Lynn & Shacham (2001) — short signatures.
- Gentry (2009) — fully homomorphic encryption.
- Durumeric et al. (2013) — internet-wide measurement with ZMap.
- Tramèr et al. (2016) — stealing machine-learning models via prediction APIs.
- Vanhoef & Piessens (2017) — KRACK.
- Spectre and Meltdown papers (2018) — speculative-execution attacks.
- Google BeyondCorp papers — zero-trust architecture.
- Sigstore, in-toto, and modern software-supply-chain integrity papers.
- Carlini et al. adversarial ML and model-extraction papers.
- Prompt-injection, agent jailbreak, and tool-misuse papers from 2023–2025.
- NIST PQC standardization and transition papers on ML-KEM / ML-DSA.

#### Reviews / Orientation
- Garfinkel & Rosenblum — virtual-machine introspection for security.
- Herley (2009) — economics of security behavior.
- Egele, Scholte, Kirda & Kruegel — survey on malware analysis.
- Zeller, Sounthiraraj, and later supply-chain security review papers.
- Symantec / Microsoft / academic ransomware review papers.
- Dwork & Roth review chapters on privacy.

## 18.5 Open Problems & Research Frontiers

- **Post-quantum cryptography transition** — NIST has standardized PQC algorithms (ML-KEM, ML-DSA, SLH-DSA); massive migration of internet infrastructure; crypto-agility; hybrid schemes during transition
- **AI-powered attacks & defense** — LLMs for phishing/social engineering at scale; AI-assisted vulnerability discovery; autonomous attack agents; AI-driven SOC automation; adversarial ML robustness
- **Supply chain security** — Software supply chain attacks (SolarWinds-style); SBOM adoption; build provenance; dependency confusion; signing and attestation (Sigstore)
- **IoT and embedded security** — Billions of constrained devices; lightweight crypto; secure update mechanisms; hardware roots of trust; medical device security
- **Zero trust architecture** — Moving from perimeter-based to identity-based security; micro-segmentation; continuous verification; BeyondCorp model; practical deployment
- **Ransomware resilience** — Preventing, detecting, and recovering from ransomware; backup strategies; paying vs. not paying; cyber insurance; law enforcement coordination
- **Privacy-enhancing technologies** — Practical deployment of MPC, FHE, differential privacy; privacy-preserving analytics; compliant data sharing
- **Critical infrastructure protection** — OT/IT convergence; ICS/SCADA security; nation-state threats; grid security; water/transportation systems

---

## 18.6 Career Paths & Salary Benchmarks

| Role | Range (US) |
|---|---|
| Security analyst (entry) | $70K–$95K |
| Penetration tester | $85K–$140K |
| Security engineer | $110K–$200K |
| Cloud security engineer | $120K–$200K |
| Security architect | $140K–$220K |
| Incident response / DFIR | $90K–$150K |
| Malware analyst / reverse engineer | $100K–$160K |
| CISO (Chief Information Security Officer) | $200K–$400K+ |
| Cryptographer (PhD) | $130K–$250K+ |
| Bug bounty hunter (top tier) | Variable, $100K–$500K+ |
| Faculty (R1, security) | $110K–$180K |

**Certifications:** CISSP, OSCP, CEH, CompTIA Security+, GIAC (GSEC, GPEN, GCIH, GREM), CISM, AWS Security Specialty.

**Major Employers:** CrowdStrike, Palo Alto Networks, Mandiant/Google, Microsoft, Amazon, NSA, CISA, FBI, national labs, Cloudflare, Fortinet, Zscaler, consulting (Deloitte, Accenture, Booz Allen), every large enterprise (internal security teams).

---

## 18.7 Connections to Other Fields

| Field | Connection |
|---|---|
| **Computer Science** | Security is a CS subfield; systems, networking, PL, and theory all connect |
| **Mathematics** | Cryptography (number theory, algebra, lattices), information theory, probability |
| **Electrical Engineering** | Hardware security, side channels, embedded systems, IoT |
| **Law** | Cyber law, privacy regulation, digital evidence, export controls, responsible disclosure |
| **Political Science / IR** | Cyber warfare, nation-state actors, cyber policy, deterrence, international norms |
| **Psychology** | Social engineering, phishing, security usability, insider threat behavior |
| **Business** | Risk management, compliance, cyber insurance, business continuity |

---

## Appendix: Key Security Conferences

| Conference | Focus |
|---|---|
| **IEEE S&P (Oakland)** | Premier academic security & privacy |
| **USENIX Security** | Systems security |
| **CCS (ACM)** | Broad computer & communications security |
| **NDSS** | Network and distributed system security |
| **CRYPTO / EUROCRYPT / ASIACRYPT** | IACR cryptography conferences |
| **Black Hat / DEF CON** | Industry & hacker conferences |
| **RSA Conference** | Industry/enterprise security |
| **ACSAC** | Applied computer security |

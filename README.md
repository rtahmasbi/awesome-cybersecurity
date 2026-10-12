# awesome-cybersecurity


# Timeline
## 2026/10/08
https://www.anthropic.com/news/anthropic-cyber-mission
- Critical infrastructure: introducing the Critical Infrastructure Defense Program (CIDP), which brings frontier models, on-site engineers, and threat research to the defenders that protect operational technology.
- Open-source software: launching OSS Scanner, which offers open-source projects regular security scans from our strongest models, for free. https://red.anthropic.com/oss-scanner/


## 2026/10/10
https://www.marktechpost.com/2026/10/10/orcarouter-releases-orcacyber-zero-1-5-cybersecurity-model-with-1m-context/

**How does it compare with other cyber models?**

| Feature | OrcaCyber Zero 1.5 | OrcaCyber Zero 1.0 | Claude Mythos Preview | GPT-5.5-Cyber | Sakana Fugu-Cyber |
|---|---|---|---|---|---|
| **Developer** | Orca (OrcaRouter) | Orca (OrcaRouter) | Anthropic | OpenAI | Sakana AI |
| **Release** | Oct 10, 2026 | Sep 17, 2026 | Apr 7, 2026 | Jun 22, 2026 (full) | Jul 21, 2026 |
| **Type** | Post-trained model | Post-trained coding model | General frontier model | Cyber-tuned GPT-5.5 | Multi-agent orchestration |
| **Parameters** | Not disclosed | Not disclosed | Not disclosed | Not disclosed | Not disclosed |
| **Context** | 1M | 1M | Not disclosed | Not disclosed | Not disclosed |
| **CyberGym** | Not disclosed | 98.07% (harness, pass@1) | 83.1% | 85.6% | 86.9% |
| **Other headline score** | Cybench 100% | Not disclosed | SWE-bench Pro 77.8% | Not disclosed | CTI-REALM 72.1% |
| **Price (in / out per 1M)** | $3.00 / $7.50 | $3.00 / $7.50 | $25 / $125 after credits | Not disclosed | Not disclosed |
| **Access** | Gated Security Research tier | Gated, closed beta | Glasswing partners | Vetted defenders only | Application review |

- [Website](https://orca.security/)


# OSS (open-source software)
- OSS-Fuzz: https://google.github.io/oss-fuzz/


# SIEM (Security Information and Event Management)
## SIGMA
- [website](https://sigmahq.io/)
- [Github](https://github.com/sigmahq/sigma)

Sigma is a generic and open signature format that allows you to describe relevant log events in a straightforward manner. The rule format is very flexible, easy to write and applicable to any type of log file.

Sigma is for log files what [Snort](https://www.snort.org/) is for network traffic and [YARA](https://github.com/VirusTotal/yara) is for files.


## Snort
Snort is the foremost Open Source Intrusion Prevention System (IPS) in the world. Snort IPS uses a series of rules that help define malicious network activity and uses those rules to find packets that match against them and generates alerts for users.

- [Website](https://www.snort.org/)
- [download rules link](https://www.snort.org/downloads/#rule-downloads)

## Yara
YARA is a tool aimed at (but not limited to) helping malware researchers to identify and classify malware samples. With YARA you can create descriptions of malware families (or whatever you want to describe) based on textual or binary patterns. Each description, a.k.a. rule, consists of a set of strings and a boolean expression which determine its logic.

- [Github](https://github.com/VirusTotal/yara)
- [Yara rules](https://github.com/yara-rules/rules)



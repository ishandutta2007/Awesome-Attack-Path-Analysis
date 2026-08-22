# 🚀 Top Attack Path Analysis Platforms

> A curated list of **Attack Path Analysis (APA), Attack Graph Analysis, Exposure Management, Threat Exposure Management, Security Graph, and Risk-Based Prioritization** platforms and open-source projects.

Attack Path Analysis helps security teams understand how vulnerabilities, misconfigurations, excessive privileges, exposed identities, network connectivity, and other security conditions can combine into a viable route from an initial foothold to a critical asset. Modern platforms increasingly combine **attack graphs, identity relationships, vulnerability data, cloud permissions, business context, and threat intelligence** to prioritize the paths that matter most.

---

## 🏢 SaaS / Hosted Platforms

| Platform | Description | Primary Focus |
|---|---|---|
| [XM Cyber](https://xmcyber.com/) | Continuous exposure management platform centered around attack graph analysis, validated attack paths, exposure prioritization, and business-impact analysis. | Attack Path / Exposure Management |
| [Tenable One](https://www.tenable.com/products/tenable-one) | Exposure management platform combining vulnerability, identity, cloud, attack surface, and attack-path insights. | Exposure Management |
| [Tenable ExposureAI](https://www.tenable.com/) | AI-assisted exposure analysis and prioritization capabilities within Tenable's exposure management ecosystem. | AI / Exposure Prioritization |
| [Palo Alto Networks Cortex XSIAM](https://www.paloaltonetworks.com/cortex/cortex-xsiam) | AI-driven security operations platform correlating endpoint, network, cloud, identity, and security data to identify attack activity and risk. | XDR / Security Operations |
| [Microsoft Security Exposure Management](https://www.microsoft.com/en-us/security/business/security-exposure-management) | Microsoft's exposure management capability for discovering, correlating, and prioritizing security risks across enterprise environments. | Exposure Management |
| [Balbix](https://www.balbix.com/) | AI-powered cyber risk management and security posture platform providing asset intelligence, attack surface analysis, and risk prioritization. | Cyber Risk / Attack Paths |
| [Brinqa](https://www.brinqa.com/) | Cyber risk orchestration and exposure management platform using a security knowledge graph to connect vulnerabilities, assets, controls, and business context. | Security Graph / Risk |
| [FireMon](https://www.firemon.com/) | Network security policy management and risk platform with path analysis and policy optimization capabilities. | Network Security / Path Analysis |
| [Pathlock](https://pathlock.com/) | Application security and access governance platform analyzing access risks, permissions, and toxic combinations. | Identity / Access Risk |
| [Cymulate](https://cymulate.com/) | Breach and attack simulation platform that continuously validates security controls and attack scenarios. | BAS / Attack Simulation |
| [AlgoSec](https://www.algosec.com/) | Network security management platform providing application connectivity mapping, risk analysis, and security policy optimization. | Network Path Analysis |
| [Microsoft Defender Exposure Management](https://www.microsoft.com/en-us/security/business/threat-protection/microsoft-defender-external-attack-surface-management) | Microsoft security exposure capabilities connecting assets, vulnerabilities, identities, attack surfaces, and security recommendations. | Exposure Management |
| [Rapid7 Exposure Command](https://www.rapid7.com/) | Exposure management capabilities designed to correlate vulnerabilities, assets, identities, and attack risk. | Exposure Management |
| [Qualys TotalCloud](https://www.qualys.com/) | Cloud security and exposure management capabilities for identifying relationships and exploitable cloud risks. | Cloud Exposure |
| [CrowdStrike Falcon Exposure Management](https://www.crowdstrike.com/) | Exposure management capabilities combining endpoint, identity, cloud, vulnerability, and threat data. | Exposure Management |
| [Wiz](https://www.wiz.io/) | Cloud security platform that maps cloud resources, vulnerabilities, identities, permissions, and attack paths. | Cloud Attack Paths |
| [Orca Security](https://orca.security/) | Cloud security platform identifying attack paths across cloud assets, vulnerabilities, identities, and permissions. | Cloud Attack Paths |
| [Palo Alto Networks Prisma Cloud](https://www.paloaltonetworks.com/prisma/cloud) | Cloud-native application protection platform with cloud identity, vulnerability, configuration, and attack-path analysis. | Cloud Security |
| [Ermetic / Tenable Cloud Security](https://www.tenable.com/products/tenable-cloud-security) | Cloud security and identity risk analysis focused on permissions, exposures, and attack paths. | Cloud IAM / Attack Paths |
| [Sonrai Security](https://sonraisecurity.com/) | Cloud identity and entitlement management platform that analyzes relationships between identities, permissions, data, and cloud resources. | Cloud Identity |
| [Permiso Security](https://permiso.io/) | Cloud identity security platform mapping identities, privileges, activity, and attack paths across cloud environments. | Cloud Identity / Attack Paths |
| [SentinelOne Singularity Exposure Management](https://www.sentinelone.com/) | Security exposure capabilities connecting endpoint, identity, cloud, and vulnerability context. | Exposure Management |
| [Balbix Cyber Risk Platform](https://www.balbix.com/) | Cyber-risk platform that models enterprise assets, vulnerabilities, controls, and potential attack scenarios. | Cyber Risk |
| [ThreatConnect](https://threatconnect.com/) | Threat intelligence and security operations platform that can correlate adversary, asset, and risk relationships. | Threat Intelligence / Risk |
| [SafeBreach](https://www.safebreach.com/) | Breach and attack simulation platform that validates attack paths and security controls against simulated attack techniques. | BAS / Attack Validation |
| [Picus Security](https://www.picussecurity.com/) | Security control validation and breach simulation platform for evaluating attack techniques and defensive coverage. | BAS / Attack Simulation |
| [Pentera](https://pentera.io/) | Automated security validation platform that emulates real-world attacks to discover exploitable attack chains. | Automated Security Validation |
| [Randori](https://www.randori.com/) | Attack surface and adversary perspective platform focused on external attack paths and attacker reconnaissance. | Attack Surface / Adversary Intelligence |
| [CyCognito](https://www.cycognito.com/) | External attack surface management platform discovering unknown assets and externally reachable attack exposure. | External Attack Surface |
| [Mandiant Advantage](https://cloud.google.com/security/mandiant) | Threat intelligence and security validation ecosystem providing adversary, vulnerability, and attack-context analysis. | Threat Intelligence |
| [Recorded Future](https://www.recordedfuture.com/) | Intelligence platform correlating vulnerabilities, threat actors, infrastructure, and external exposure. | Threat Intelligence / Exposure |

---

## 🧑‍💻 Open-Source

> The open-source ecosystem is smaller than the commercial exposure-management market, but several projects provide powerful building blocks for **attack graphs, privilege-path analysis, cloud relationship mapping, vulnerability reasoning, and security graph construction**.

### ⭐ Major Open-Source Attack Path / Attack Graph Projects

| Project | Description | Primary Focus |
|---|---|---|
| [BloodHound Community Edition](https://github.com/SpecterOps/BloodHound) | Graph-based security analysis platform that reveals hidden relationships and attack paths across identity environments. | Identity / AD Attack Paths |
| [SharpHound](https://github.com/SpecterOps/SharpHound) | BloodHound data collector for Active Directory environments. | AD Relationship Discovery |
| [AzureHound](https://github.com/SpecterOps/BloodHound) | BloodHound ecosystem support for collecting Azure identity and relationship data. | Azure Identity |
| [OpenGraph](https://github.com/SpecterOps/BloodHound) | Graph data model used by the modern BloodHound platform for representing security relationships. | Security Graph |
| [MulVAL](https://github.com/risksense/mulval) | Logic-based multi-host, multi-stage vulnerability analysis system that generates attack graphs from network and vulnerability information. | Attack Graphs |
| [Cartography](https://github.com/lyft/cartography) | Open-source asset inventory tool that imports infrastructure and identity relationships into Neo4j for graph-based analysis. | Security Graph |
| [CloudMapper](https://github.com/duo-labs/cloudmapper) | AWS visualization and security analysis tool for mapping cloud infrastructure and relationships. | AWS Attack Surface |
| [PMapper](https://github.com/nccgroup/PMapper) | AWS IAM privilege escalation analysis tool that models IAM relationships and identifies effective privilege paths. | AWS IAM Attack Paths |
| [CloudFox](https://github.com/BishopFox/cloudfox) | AWS situational-awareness toolkit for enumerating cloud resources, permissions, and potential privilege paths. | AWS Security Analysis |
| [Steampipe](https://github.com/turbot/steampipe) | Open-source framework for querying cloud and infrastructure data as relational tables, useful for constructing security graphs and exposure analysis. | Cloud Security Data |
| [Neo4j](https://github.com/neo4j/neo4j) | Graph database frequently used as the underlying graph engine for security relationship and attack-path analysis. | Graph Database |
| [Graphistry](https://github.com/graphistry/pygraphistry) | GPU-accelerated graph visualization and analytics toolkit useful for exploring large security graphs. | Graph Analytics |
| [NetworkX](https://github.com/networkx/networkx) | Python graph-analysis library that can be used to model and calculate attack paths, shortest paths, centrality, and graph cuts. | Graph Algorithms |
| [igraph](https://github.com/igraph/igraph) | High-performance graph analysis library useful for large-scale attack graph computation. | Graph Analytics |
| [OpenCTI](https://github.com/OpenCTI-Platform/opencti) | Open-source cyber threat intelligence platform representing entities and relationships in a graph-oriented knowledge model. | Threat Graph |
| [MISP](https://github.com/MISP/MISP) | Open-source threat intelligence platform for sharing and correlating indicators, threat information, and relationships. | Threat Intelligence Graph |
| [MITRE Caldera](https://github.com/mitre/caldera) | Automated adversary emulation platform useful for validating and exploring attack chains. | Attack Simulation |
| [Atomic Red Team](https://github.com/redcanaryco/atomic-red-team) | Library of focused adversary techniques for testing security controls and validating attack scenarios. | Attack Technique Validation |
| [Infection Monkey](https://github.com/guardicore/monkey) | Open-source breach-and-attack simulation platform capable of automatically exploring network attack paths. | Attack Path Simulation |
| [Prelude Operator](https://github.com/preludeorg) | Open-source adversary emulation framework for executing attack techniques and validating defensive controls. | Adversary Emulation |
| [Attack Graph Analysis](https://github.com/mmohamedkhaled/attack-graph-analysis) | Python security-analysis toolkit implementing graph algorithms for attack-path ranking, vulnerability analysis, and minimum-cut analysis. | Attack Graph Algorithms |
| [Cyber Threat Scenario Analyzer](https://github.com/ncr-no/cts-analyzer) | Research implementation combining evidence paths, attack graphs, and kill-chain analysis using MulVAL. | Threat Scenario Analysis |
| [OWASP Threat Dragon](https://github.com/OWASP/threat-dragon) | Open-source threat modeling tool useful for modeling system relationships and attack scenarios. | Threat Modeling |
| [OWASP pytm](https://github.com/OWASP/pytm) | Pythonic threat modeling framework for defining systems, data flows, threats, and mitigations programmatically. | Threat Modeling |
| [OWASP Threat Modeling Tool](https://github.com/OWASP/threat-dragon) | Visual threat modeling environment for mapping application architectures and security threats. | Threat Modeling |
| [Nmap](https://github.com/nmap/nmap) | Network discovery and security auditing tool that can supply network topology and reachability information for attack-path modeling. | Network Discovery |
| [Nuclei](https://github.com/projectdiscovery/nuclei) | Template-driven vulnerability and exposure scanner useful for enriching attack graphs with real findings. | Vulnerability Discovery |
| [OpenVAS / Greenbone Community Edition](https://github.com/greenbone/openvas-scanner) | Open-source vulnerability scanning engine that can provide vulnerability data for attack-graph analysis. | Vulnerability Intelligence |
| [Trivy](https://github.com/aquasecurity/trivy) | Open-source vulnerability and misconfiguration scanner for containers, cloud, Kubernetes, filesystems, and repositories. | Vulnerability Discovery |
| [Prowler](https://github.com/prowler-cloud/prowler) | Open-source cloud security assessment tool producing findings that can be incorporated into cloud attack-path models. | Cloud Security |
| [ScoutSuite](https://github.com/nccgroup/ScoutSuite) | Multi-cloud security auditing tool that maps cloud configurations and security risks. | Cloud Security |
| [CloudSploit](https://github.com/aquasecurity/cloudsploit) | Cloud security configuration scanner useful for identifying cloud exposures that contribute to attack paths. | Cloud Configuration |

BloodHound is particularly relevant because it explicitly uses graph theory to uncover hidden relationships and attack paths across identity systems, while MulVAL is designed specifically for multi-host, multi-stage vulnerability analysis and attack-graph generation. :contentReference[oaicite:0]{index=0}

---

## 🔥 Open-Source Alternatives by Use Case

### 🥇 Best Identity Attack Path Analysis — BloodHound

**BloodHound Community Edition** is arguably the strongest open-source option for identity-centric attack-path analysis.

It models relationships between users, groups, computers, permissions, sessions, cloud identities, and other entities to identify paths that can lead to privileged or sensitive assets.

**Best for:** Active Directory, Entra/Azure identity, privilege escalation, identity attack paths.

**Commercial alternatives:** XM Cyber, Tenable, Microsoft Security Exposure Management, Brinqa.

---

### 🥈 Best Traditional Attack-Graph Engine — MulVAL

**MulVAL** is one of the most directly relevant open-source projects for formal attack-graph analysis. It performs multi-host, multi-stage vulnerability analysis and can generate attack graphs from vulnerability and network information. :contentReference[oaicite:1]{index=1}

**Best for:** Research, vulnerability reasoning, enterprise network attack graphs, academic security analysis.

**Commercial alternatives:** XM Cyber, Tenable Exposure Management, Brinqa.

---

### 🥉 Best Cloud Relationship Mapping — Cartography

**Cartography** builds a graph representation of infrastructure and relationships and is particularly useful as a foundation for custom cloud security graph and attack-path systems.

**Best for:** AWS/cloud asset relationships, graph-based security analytics, custom exposure platforms.

---

### ⭐ Best AWS IAM Analysis — PMapper

**PMapper** focuses specifically on AWS IAM relationships and effective permissions.

**Best for:** IAM privilege escalation, AWS identity analysis, cloud attack paths.

---

### ⭐ Best AWS Visualization — CloudMapper

**CloudMapper** provides visualization and security analysis of AWS environments.

**Best for:** AWS topology, network relationships, security architecture analysis.

---

### ⭐ Best Attack-Path Simulation — Infection Monkey

**Infection Monkey** can simulate propagation through environments and is useful for discovering possible lateral movement and attack paths.

**Best for:** Breach simulation, lateral movement, network segmentation validation.

---

### ⭐ Best Cloud Security Data — Prowler / ScoutSuite

Cloud security scanners such as **Prowler** and **ScoutSuite** can provide the configuration, identity, and exposure findings required to build custom cloud attack-path analysis systems.

**Best for:** AWS, Azure, GCP security posture and exposure discovery.

---

## 🧩 Open-Source Attack Path Building Blocks

| Layer | Open-Source Projects |
|---|---|
| **Identity Graph** | BloodHound, SharpHound, AzureHound |
| **Attack Graph Reasoning** | MulVAL, Attack Graph Analysis |
| **Cloud Graph** | Cartography, CloudMapper, PMapper, CloudFox |
| **Cloud Security** | Prowler, ScoutSuite, Trivy |
| **Network Discovery** | Nmap, Masscan |
| **Vulnerability Discovery** | OpenVAS, Nuclei, Trivy |
| **Threat Intelligence** | MISP, OpenCTI |
| **Attack Simulation** | Infection Monkey, MITRE Caldera, Atomic Red Team |
| **Graph Database** | Neo4j |
| **Graph Analytics** | NetworkX, igraph, Graphistry |
| **Threat Modeling** | OWASP Threat Dragon, OWASP pytm |
| **Visualization** | Graphviz, Cytoscape |
| **Telemetry** | OpenTelemetry |
| **SIEM / Analytics** | OpenSearch, Wazuh |

---

## 🏗️ Typical Open-Source Attack Path Analysis Stack

```text
                         ┌──────────────────────────────┐
                         │       ENTERPRISE ENVIRONMENT │
                         │                              │
                         │ Users / Devices / Servers    │
                         │ Cloud / Applications         │
                         │ Networks / Data / Identities │
                         └──────────────┬───────────────┘
                                        │
                                        ▼
                     ┌──────────────────────────────────┐
                     │        DATA COLLECTION           │
                     │                                  │
                     │ BloodHound / SharpHound           │
                     │ AzureHound                         │
                     │ Cartography                        │
                     │ CloudMapper                        │
                     │ Prowler / ScoutSuite               │
                     │ Nmap / Nuclei / OpenVAS            │
                     └──────────────┬───────────────────┘
                                    │
                                    ▼
                     ┌──────────────────────────────────┐
                     │       SECURITY KNOWLEDGE GRAPH    │
                     │                                  │
                     │ Neo4j                             │
                     │ NetworkX                          │
                     │ igraph                            │
                     │ Graphistry                        │
                     └──────────────┬───────────────────┘
                                    │
                                    ▼
                     ┌──────────────────────────────────┐
                     │        ATTACK GRAPH ENGINE        │
                     │                                  │
                     │ BloodHound                         │
                     │ MulVAL                            │
                     │ Custom Graph Algorithms            │
                     │ Attack Graph Analysis              │
                     └──────────────┬───────────────────┘
                                    │
                                    ▼
               ┌────────────────────────────────────────────┐
               │             ATTACK PATH ANALYSIS            │
               │                                            │
               │ Initial Access                              │
               │        ↓                                   │
               │ Privilege Escalation                        │
               │        ↓                                   │
               │ Lateral Movement                            │
               │        ↓                                   │
               │ Credential / Identity Abuse                 │
               │        ↓                                   │
               │ Crown-Jewel Asset                            │
               └──────────────────────┬─────────────────────┘
                                      │
                                      ▼
                     ┌──────────────────────────────────┐
                     │        RISK PRIORITIZATION        │
                     │                                  │
                     │ CVSS                              │
                     │ Exploitability                     │
                     │ Asset Criticality                   │
                     │ Identity Privilege                 │
                     │ Business Impact                     │
                     │ Threat Intelligence                │
                     │ Path Length / Choke Points         │
                     └──────────────┬───────────────────┘
                                    │
                                    ▼
                     ┌──────────────────────────────────┐
                     │            REMEDIATION             │
                     │                                  │
                     │ Patch                              │
                     │ Remove Permission                  │
                     │ Disable Account                    │
                     │ Segment Network                    │
                     │ Fix Misconfiguration               │
                     │ Rotate Credential                  │
                     │ Remove Exposure                    │
                     └──────────────────────────────────┘
 ```
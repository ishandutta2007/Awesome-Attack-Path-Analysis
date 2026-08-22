# Awesome-Attack-Path-Analysis

Markdown




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
🔬 Key Attack Path Analysis Concepts
Concept	Description
Attack Graph	Graph representing possible sequences of actions an attacker can take.
Attack Path	A specific sequence of relationships or conditions leading from an entry point to a target.
Initial Access	The starting point from which an attacker enters an environment.
Lateral Movement	Movement from one compromised system or identity to another.
Privilege Escalation	Obtaining higher privileges through vulnerabilities, permissions, or identity relationships.
Privilege Path	A graph path through permissions that can result in elevated access.
Choke Point	A control or exposure whose remediation can eliminate multiple attack paths.
Blast Radius	The set of systems, identities, or data potentially affected after compromise.
Crown Jewel	A business-critical asset that an attacker ultimately wants to compromise.
Exploitability	Likelihood that a vulnerability or exposure can actually be leveraged.
Reachability	Whether an attacker can technically reach a resource through network or identity relationships.
Exposure	A condition that increases the probability or impact of compromise.
Security Graph	Graph representation connecting assets, identities, vulnerabilities, permissions, and controls.
Attack Surface	The collection of externally and internally exposed systems and resources.
Toxic Combination	Multiple individually acceptable permissions or conditions that create a dangerous combined risk.
Minimum Cut	Smallest set of graph nodes/edges whose removal breaks an attack path.
Path Centrality	Measurement of entities appearing frequently across important attack paths.
Blast-Radius Analysis	Analysis of what an attacker could access after compromising a particular entity.
Exposure Prioritization	Ranking exposures according to actual attack-path and business impact.
Continuous Exposure Management	Continuous discovery, validation, prioritization, and remediation of exploitable exposures.
🧪 Major Attack Path Analysis Use Cases
Use Case	Objective
Active Directory Attack Paths	Identify routes from ordinary users to privileged identities.
Cloud IAM Attack Paths	Identify excessive permissions and privilege escalation routes.
Vulnerability Attack Paths	Determine which vulnerabilities can actually contribute to compromise.
Network Attack Paths	Analyze reachable systems and segmentation weaknesses.
External-to-Internal Paths	Determine how Internet-facing exposures can lead to internal assets.
Identity Attack Paths	Connect users, groups, service accounts, applications, and privileges.
Ransomware Paths	Identify paths leading toward critical systems and data.
Crown-Jewel Protection	Work backward from critical assets to identify all viable compromise routes.
Cloud-to-On-Prem Paths	Analyze hybrid attack chains crossing cloud and enterprise environments.
Third-Party Exposure	Analyze how suppliers, integrations, and external identities can create paths.
Segmentation Validation	Determine whether network segmentation actually blocks attack paths.
Remediation Prioritization	Identify fixes that eliminate the greatest number of dangerous paths.
Breach Simulation	Validate whether theoretical attack paths are practically exploitable.
Threat-Informed Defense	Prioritize attack paths associated with relevant adversary techniques.
📊 Attack Path Risk Scoring

A practical attack-path scoring model can combine multiple dimensions:

Attack Path Risk
        │
        ├── Exploitability
        │
        ├── Asset Criticality
        │
        ├── Privilege Level
        │
        ├── Network Reachability
        │
        ├── Identity Exposure
        │
        ├── Vulnerability Severity
        │
        ├── Threat Intelligence
        │
        ├── Path Length
        │
        ├── Business Impact
        │
        └── Control Weakness
                │
                ▼
        ┌───────────────────┐
        │ Composite Risk    │
        │ Score              │
        └─────────┬─────────┘
                  │
                  ▼
          Remediation Priority
🏆 Quick Comparison
Platform / Project	Hosted	Open Source	Attack Graph	Identity	Cloud	Vulnerability	Attack Simulation
XM Cyber	✅	❌	✅	✅	✅	✅	⚪
Tenable Exposure Management	✅	❌	✅	✅	✅	✅	⚪
Microsoft Security Exposure Management	✅	❌	✅	✅	✅	✅	⚪
Brinqa	✅	❌	✅	✅	✅	✅	⚪
Balbix	✅	❌	✅	✅	✅	✅	⚪
FireMon	✅	❌	⚪	⚪	⚪	⚪	⚪
Pathlock	✅	❌	⚪	✅	✅	⚪	⚪
AlgoSec	✅	❌	⚪	⚪	⚪	⚪	⚪
Cymulate	✅	❌	⚪	⚪	✅	⚪	✅
BloodHound CE	❌	✅	✅	✅	✅	⚪	⚪
MulVAL	❌	✅	✅	⚪	⚪	✅	⚪
Cartography	❌	✅	⚪	✅	✅	⚪	⚪
CloudMapper	❌	✅	⚪	✅	✅	⚪	⚪
PMapper	❌	✅	✅	✅	✅	⚪	⚪
CloudFox	❌	✅	⚪	✅	✅	⚪	⚪
Infection Monkey	❌	✅	⚪	⚪	⚪	⚪	✅
MITRE Caldera	❌	✅	⚪	⚪	⚪	⚪	✅
Atomic Red Team	❌	✅	⚪	⚪	⚪	⚪	✅
Prowler	❌	✅	⚪	✅	✅	⚪	⚪
ScoutSuite	❌	✅	⚪	✅	✅	⚪	⚪
Attack Graph Analysis	❌	✅	✅	⚪	⚪	✅	⚪

Important: Not every open-source project above is a complete commercial-grade Attack Path Analysis platform. Some are attack-graph engines, identity graph tools, cloud graph builders, vulnerability scanners, simulation platforms, or graph-analysis libraries that can serve as components of an open-source APA stack.

🥇 Best Open-Source Alternatives
Commercial Platform	Strong Open-Source Alternatives
XM Cyber	BloodHound, MulVAL, Cartography, Neo4j, NetworkX
Tenable ExposureAI	MulVAL, BloodHound, Prowler, Nuclei, OpenVAS
Microsoft Security Exposure Management	BloodHound, Cartography, Prowler, ScoutSuite, MulVAL
Balbix	Cartography, Neo4j, NetworkX, MulVAL
Brinqa	Cartography + Neo4j + MulVAL + OpenCTI
FireMon	Nmap + NetworkX + Graphistry + Neo4j
Pathlock	BloodHound + PMapper + Neo4j
Cymulate	MITRE Caldera + Atomic Red Team + Infection Monkey
AlgoSec	Nmap + NetworkX + Graphviz + Neo4j
Cloud Attack Path Platforms	PMapper, CloudMapper, CloudFox, Cartography, Prowler
Identity Attack Path Platforms	BloodHound, SharpHound, AzureHound
Vulnerability Attack Graph Platforms	MulVAL, OpenVAS, Nuclei + custom graph engine
🗺️ Open-Source Attack Path Analysis Landscape
                         ATTACK PATH ANALYSIS
                                  │
          ┌───────────────────────┼────────────────────────┐
          │                       │                        │
          ▼                       ▼                        ▼
    IDENTITY GRAPHS         VULNERABILITY             CLOUD GRAPHS
          │                   ATTACK GRAPHS                 │
          │                       │                          │
     BloodHound               MulVAL                    Cartography
     SharpHound               OpenVAS                   CloudMapper
     AzureHound               Nuclei                    PMapper
                              Trivy                     CloudFox
                                  │                      Prowler
          │                       │                          │
          └───────────────────────┼──────────────────────────┘
                                  ▼
                         SECURITY KNOWLEDGE
                               GRAPH
                                  │
                    ┌─────────────┼─────────────┐
                    │             │             │
                    ▼             ▼             ▼
                  Neo4j       NetworkX       Graphistry
                    │             │             │
                    └─────────────┼─────────────┘
                                  ▼
                           ATTACK GRAPH ENGINE
                                  │
                    ┌─────────────┼─────────────┐
                    │             │             │
                    ▼             ▼             ▼
                 MulVAL      Custom Graph    BloodHound
                              Algorithms
                                  │
                                  ▼
                           ATTACK PATHS
                                  │
             ┌────────────────────┼─────────────────────┐
             │                    │                     │
             ▼                    ▼                     ▼
        Initial Access       Lateral Movement      Privilege Escalation
             │                    │                     │
             └────────────────────┼─────────────────────┘
                                  ▼
                           CROWN JEWEL ASSET
                                  │
                                  ▼
                          RISK PRIORITIZATION
                                  │
                    ┌─────────────┼─────────────┐
                    │             │             │
                    ▼             ▼             ▼
                Exploitability  Impact       Reachability
                    │             │             │
                    └─────────────┼─────────────┘
                                  ▼
                           REMEDIATION
                                  │
             ┌────────────────────┼─────────────────────┐
             │                    │                     │
             ▼                    ▼                     ▼
            Patch             Remove Access        Segment Network
             │                    │                     │
             └────────────────────┼─────────────────────┘
                                  ▼
                         PATH ELIMINATED
🔗 Related Categories

Attack Surface Management

Continuous Exposure Management

Vulnerability Management

Identity Threat Detection and Response

Cloud Security

Cyber Threat Intelligence

Breach and Attack Simulation

Threat Modeling

Graph Database

Network Security

Privilege Escalation

Attack Graph

📚 References

XM Cyber
 — Attack graph and continuous exposure management platform.

Tenable Attack Path Analysis
 — Overview of attack-path analysis and its role in exposure management.

BloodHound Community Edition
 — Graph-based identity and attack-path analysis.

MulVAL
 — Multi-host, multi-stage vulnerability analysis and attack-graph generation.

Cartography
 — Infrastructure and relationship graphing platform.

CloudMapper
 — AWS infrastructure visualization and security analysis.

PMapper
 — AWS IAM privilege-path analysis.

CloudFox
 — AWS cloud situational-awareness and privilege analysis.

Prowler
 — Open-source cloud security assessment platform.

ScoutSuite
 — Multi-cloud security auditing tool.

MITRE Caldera
 — Automated adversary emulation platform.

Atomic Red Team
 — Open-source library of security testing techniques.

Infection Monkey
 — Open-source breach and attack simulation platform.

OpenCTI
 — Open-source cyber threat intelligence knowledge graph.

MISP
 — Open-source threat intelligence sharing and correlation platform.

Neo4j
 — Graph database suitable for security relationship graphs.

NetworkX
 — Python graph-analysis library.

Graphistry
 — Graph visualization and analytics platform.

Attack Graph Analysis
 — Open-source graph-based security analysis toolkit.

Cyber Threat Scenario Analyzer
 — Research implementation combining evidence paths and attack graphs.

OWASP Threat Dragon
 — Open-source threat modeling tool.

🤝 Contributing

Contributions are welcome!

If you know of an Attack Path Analysis platform, attack graph engine, security graph, cloud attack-path analyzer, identity attack-path tool, exposure management platform, or open-source attack simulation project that should be included, please open a pull request.

Criteria

Primarily related to attack paths, attack graphs, exposure analysis, security graphs, or attack-chain analysis

Open-source projects should have publicly accessible source code

Commercial platforms should provide meaningful exposure, attack-path, security graph, or attack-chain capabilities

Components such as graph databases, vulnerability scanners, and attack simulators are welcome when they can meaningfully contribute to an APA stack

Prefer actively maintained projects

Avoid purely offensive tools unless they provide meaningful attack-path discovery or validation functionality

Include the official project URL whenever possible

⭐ If this list is useful, consider starring the repository and contributing additional open-source Attack Path Analysis projects.

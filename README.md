# Threat-Hunting-Framework-Mapping
MITRE ATT&amp;CK Hunt Sprint – ATT&amp;CK Navigator-driven queries and detections
Government/Public Sector APT Threat Hunting Project
🏛️ Project Overview
This repository contains a comprehensive threat hunting analysis focused on Advanced Persistent Threats (APTs) targeting the Government/Public Sector. The project follows a structured methodology using the MITRE ATT&CK framework to map adversary Tactics, Techniques, and Procedures (TTPs), visualize overlaps with ATT&CK Navigator, and translate findings into actionable detections and controls aligned with NIST CSF and ISO/IEC 27001 standards.

Project Type: Academic/Security Research
Industry Focus: Government/Public Sector
Framework: MITRE ATT&CK, NIST CSF, ISO/IEC 27001
Status: Completed (March 2025)

📊 Executive Summary
Government agencies face persistent targeting from sophisticated APT groups motivated by espionage, disruption, and financial gain. This project analyzes 5 key APT groups, maps their TTPs across the attack lifecycle, identifies common attack patterns, and provides actionable security controls to strengthen defensive postures.

Key Findings:
High-Value Targets: National security data, citizen records, critical infrastructure

Primary APTs Analyzed: APT29, APT28, APT10, Lazarus Group, APT41

Common TTPs: Phishing (T1566), Credential Dumping (T1003), Remote Services (T1021)

Critical Overlap: 70% of analyzed APTs use similar post-compromise techniques

Control Alignment: Mapped to NIST CSF and ISO 27001 for practical implementation

📁 Repository Structure
text
government-apt-threat-hunting/
│
├── README.md                          # This file
├── LICENSE                            # MIT License
│
├── reports/
│   ├── Threat_Hunting_Report.pdf      # Complete analysis report (PDF)
│   ├── Executive_Summary.md           # High-level findings
│   └── Methodology_Documentation.md   # Research approach
│
├── threat_intelligence/
│   ├── APT_Profiles/                  # Detailed APT group profiles
│   │   ├── APT29_Cozy_Bear.md
│   │   ├── APT28_Fancy_Bear.md
│   │   ├── APT10_MenuPass.md
│   │   ├── Lazarus_Group.md
│   │   └── APT41_Winnti.md
│   │
│   ├── Campaign_Analysis/             # Known campaign details
│   │   ├── SolarWinds_Analysis.md
│   │   ├── DNC_Hack_Overview.md
│   │   └── CloudHopper_Campaign.md
│   │
│   └── Industry_Analysis/
│       └── Government_Sector_Risk_Assessment.md
│
├── mitre_mappings/
│   ├── navigator_layers/              # ATT&CK Navigator JSON files
│   │   ├── APT29_layer.json
│   │   ├── APT28_layer.json
│   │   ├── APT10_layer.json
│   │   ├── combined_overlap_layer.json
│   │   └── custom_hunt_layer.json
│   │
│   ├── ttp_tables/                    # TTP mapping tables
│   │   ├── APT_TTP_Matrix.csv
│   │   ├── Technique_Frequency.csv
│   │   └── Lifecycle_Mapping.md
│   │
│   └── visualizations/
│       ├── TTP_Overlap_Heatmap.png
│       ├── Attack_Lifecycle_Flow.png
│       └── APT_Comparison_Chart.png
│
├── detections/
│   ├── sigma_rules/                   # Generic detection rules
│   ├── T1003_Lsass_Dump.yml
│   ├── T1059_Suspicious_PS.yml
│   ├── T1566_Phishing_Detect.yml
│   └── T1021_RDP_Anomaly.yml
│  
│ 
│
├── controls_framework/
│   ├── nist_csf_mapping/
│   │   ├── Function_Mapping.md
│   │   ├── Control_Recommendations.csv
│   │   └── Implementation_Guide.md
│   │
│   ├── iso27001_mapping/
│   │   ├── Annex_A_Alignment.md
│   │   ├── Control_Objectives.csv
│   │   └── Compliance_Checklist.md
│   │
│   └── governance/
│       ├── Policy_Templates/
│       ├── Procedure_Guides/
│       └── Risk_Assessment_Templates/
│
├── data/
   ├── sample_logs/                  # Sample data for testing
   ├── iocs/                         * Indicators of Compromise
   │   ├── APT29_IOCs.csv
   │   ├── APT28_IOCs.csv
   │   └── Shared_TTP_IOCs.csv
   └── references/                   # Research sources
       ├── OSINT_Sources.md
      └ Bibliography.md

├🎯 Project Objectives
Threat Landscape Analysis – Identify and profile APT groups targeting government sector

TTP Mapping – Map adversary behaviors to MITRE ATT&CK framework

Overlap Visualization – Identify common attack patterns using ATT&CK Navigator

Detection Engineering – Develop actionable detection logic for common TTPs

Control Alignment – Map findings to NIST CSF and ISO 27001 controls

Actionable Outputs – Create playbooks, policies, and implementation guides

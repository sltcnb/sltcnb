# sltcnb

Security engineer building open-source **DFIR** and **incident-response** tooling — from acquisition to a searchable, detection-rich case.

Most of my public work is a suite of standalone forensic tools that share contracts and normalize everything to **Elastic Common Schema (ECS) v8**, so they compose but also stand on their own.

---

### DFIR suite

| Project | What it does |
| --- | --- |
| **[citadel](https://github.com/sltcnb/citadel)** | DFIR platform composing the tools below — acquire, ingest, parse, normalize, detect, analyze, and report a case end to end. |
| **[cumulonimbus](https://github.com/sltcnb/cumulonimbus)** | Cloud forensics & IR toolkit — collects and normalizes AWS, Azure, GCP, and Kubernetes logs to ECS v8. |
| **[Madeleine](https://github.com/sltcnb/Madeleine)** | Memory forensics automation on top of Volatility3 — orchestration, malware detection, timeline, ECS/STIX export. |
| **[CherryPick](https://github.com/sltcnb/CherryPick)** | Cross-OS forensic acquisition agent — collects host/image/device artifacts into a signed, content-addressed bundle. |
| **[BreadCrumb](https://github.com/sltcnb/BreadCrumb)** | Signature-based file carver for disk images and block devices — recovers deleted files with no filesystem metadata. |
| **[HoneyJam](https://github.com/sltcnb/HoneyJam)** | Modern Windows Registry forensics analyzer — plugins, malware detection, timelines, and ECS export. |
| **[atktimeline](https://github.com/sltcnb/atktimeline)** | Self-hosted attack timeline builder mapping events to MITRE ATT&CK. |

### Other

| Project | What it does |
| --- | --- |
| **[planX](https://github.com/sltcnb/planX)** | Native macOS task manager — Kanban, dependency graph, and time tracking (SwiftUI / SwiftData). |

---

### Stack

Python · Elasticsearch · Sigma · ECS · STIX · MITRE ATT&CK · Docker · Kubernetes · React · SwiftUI

### Focus

Incident response · cloud & memory forensics · artifact acquisition · detection engineering

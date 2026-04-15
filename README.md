# Hey, I'm Preetam 👋

> *Infrastructure Architect → AI Solutions Architect*  
> 18 years building enterprise data centres. Now building the infrastructure that runs AI.

---

## What I'm Doing Right Now

I am on a deliberate, structured journey from **VMware/NSX infrastructure expertise** into **AI Infrastructure Solutions Architecture** — targeting the DACH industrial sector (automotive, manufacturing, energy).

Not passively watching videos. Systematically building knowledge: 4 hours daily, spaced repetition (Anki), scenario-based interview practice, and public documentation of everything I learn.

**Current focus (90-day gap-closing plan — April to July 2026):**
- DC power architecture for GPU clusters: power path, redundancy tiers, PUE optimisation
- Cooling systems: air cooling limits, direct liquid cooling (DLC), hot/cold aisle containment
- NVIDIA GPU hardware: DGX H100/H200/B200, InfiniBand NDR, MIG partitioning
- At-scale benchmarking: HPL, NCCL, cluster validation

---

## Certifications

| Certification | Score | Date | Status |
|---|---|---|---|
| NVIDIA NCA-AIIO (AI Infrastructure & Operations) | AI Infra: 72% · AI Ops: 90% · Intro AI: 83% | April 2026 | ✅ Certified |
| NCP-AII (AI Infrastructure Professional) | — | Target: Q3 2026 | 🔄 Planned |

---

## What I Know — Built, Not Claimed

**Data Centre Design for AI (actively building — Days 1–30)**
- DC power path: utility → UPS → PDU → rack → PSU → GPU (TUMRPG)
- DGX H100 power requirements: 10.2 kW/node, 40.8 kW/rack (4-node), Enhanced N+1 (3 discrete PDU feeds)
- Cooling: hot/cold aisle containment, ASHRAE 18–27°C, 157 CFM/kW airflow requirement
- PUE: formula, EU reporting mandate (2024), AI workload PUE counterintuitive advantage
- Tier III minimum for DGX SuperPOD, colocation options (Equinix Frankfurt, Digital Realty)

**AI Infrastructure**
- GPU architecture: H100/H200/B200, MIG partitioning, NVLink/NVSwitch, CUDA platform
- Generation awareness: H100 (air-cooled) vs B200/GB200 NVL72 (liquid mandatory)
- AI networking: InfiniBand NDR/XDR, RoCE, RDMA, BlueField DPU, lossless Ethernet
- AI storage: GPUDirect Storage, NVMe-oF, parallel file systems (VAST, WekaIO, GPFS)
- NVIDIA software stack: CUDA, cuDNN, NCCL, NGC containers, Triton Inference Server, DCGM
- Training vs inference infrastructure: GPU sizing, latency design, right-sizing for workload

**Enterprise Infrastructure (18 Years)**
- VMware vSphere / ESXi / vCenter at scale (2,000+ hosts)
- NSX-T network virtualisation, VMware Cloud Foundation (VCF)
- vSAN HCI, SAN/NAS storage architecture
- Automation: Ansible, Python, REST API
- Large-scale migrations: 800 VMs (ACI → NSX-T), 500 VMs / 20 TB storage
- Customer architecture: pre-sales, QBR, regulated industries (finance, energy)
- DACH enterprise customer engagement: automotive, manufacturing, industrial sector

---

## Public Repositories

| Repo | What it is | Status |
|---|---|---|
| [nvidia-ai-infrastructure-field-notes](https://github.com/pdotnext/nvidia-ai-infrastructure-field-notes) | Daily learning — DC power, cooling, GPU hardware. Sourced from official NVIDIA docs. | 🔄 Active |
| [dgx-deployment-scenarios](https://github.com/pdotnext/dgx-deployment-scenarios) | Worked customer scenarios: power constraints, colocation decisions, cooling design | ⏳ Coming May 2026 |
| AI Infrastructure Sizing Calculator | Python · Streamlit — GPU cluster sizing for DACH industrial customers | ⏳ Coming June 2026 |

---

## Current Stack

```
Certifications:  NVIDIA NCA-AIIO (April 2026) · NCP-AII (target Q3 2026)
Learning tools:  Anki (spaced repetition) · Obsidian (second brain)
Editor:          VSCode on Fedora
Automation:      Ansible · Python · Bash
Containers:      Podman · Docker
Version ctrl:    Git · GitHub
Languages:       English (fluent) · German (B1, actively improving) · Python · YAML · JSON
```

---

## Background

```
2024–now   Broadcom (VMware)    Senior Technical Account Manager    Stuttgart, DE
2022–2024  Broadcom (VMware)    Consulting Architect                Stuttgart, DE
2021–2022  Börse Stuttgart      Virtualisation Engineer             Stuttgart, DE
2019–2021  EMP                  Virtualisation Engineer
2017–2019  DarkMatter           Virtualisation Architect            Abu Dhabi, UAE
2015–2017  Injazat              Technical Architect                 Abu Dhabi, UAE
2014–2015  VMware India         Technical Account Manager
2007–2011  Credit Suisse        Technical Domain Expert             Singapore / India
```

---

## Connect

- LinkedIn: [linkedin.com/in/preetam-ai-dev](https://www.linkedin.com/in/preetam-ai-dev)
- Email: preetam.ai.pro@gmail.com
- Location: Stuttgart, Germany

---

*Building in public. Every file in this repo is a day of real learning.*  
*Watch this repo — active updates through July 2026.*

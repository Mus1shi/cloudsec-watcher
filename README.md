# CloudSec Watcher

**CloudSec Watcher** is a security auditing tool for Azure environments.  
It helps detect misconfigurations, identify risky deployments, and provide actionable insights to secure your cloud infrastructure.

---

## Objectives

- Automate Azure security audits
- Detect misconfigurations and policy violations
- Generate structured reports (Markdown/HTML)
- Integrate alerting logic for critical issues
- Lay the foundation for future DevSecOps automation

---

## Features (in progress)

- [x] CLI interface (Python)
- [ ] Environment scan using Azure CLI / SDK
- [ ] Misconfiguration detection (IAM, NSG, Storage, VM)
- [ ] Report generation with recommendations
- [ ] Alert tagging for critical findings
- [ ] Basic dashboard (optional)

---

## 🛠️ Technologies & Tools

- **Python 3** – scripting and logic  
- **Azure CLI** / **Azure SDK for Python** – cloud interaction  
- **Markdown / HTML** – report rendering  
- **Git** – version control  
- **Docker (planned)** – isolated execution  
- **Terraform (planned)** – validation of IaC files

---

## Roadmap

| Phase | Goal | Status |
|-------|------|--------|
| 1 | Azure resource scanner (CLI) |  Done |
| 2 | Misconfig detection engine |  In progress |
| 3 | Report rendering module |  Not started |
| 4 | Alerts + tagging logic |  Not started |
| 5 | Basic UI / dashboard (optional) | Optional |

---

## Structure (planned)

cloudsec-watcher/
├── scanner/ # Azure resource gathering
├── detectors/ # Misconfiguration detection logic
├── reports/ # Markdown/HTML generation
├── alerts/ # Alert tagging, severity logic
├── main.py # Entry point
└── README.md


---

## Notes

> This tool is educational, built during my Cloud Security training.  
> It will grow over time with more Azure-specific checks, hardening rules, and reporting enhancements.

---



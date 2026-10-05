<p align="center"><img src="assets/banner.svg" width="100%" alt="Shemar Marks — Freelance AWS, Linux and Terraform infrastructure services" /></p>

## Infrastructure, with a recovery plan

I'm **Shemar Marks**. I help small teams deploy and migrate workloads, harden Linux hosts, improve monitoring and test recovery. I verify what changed and leave the system operable with a usable handover.

**[Discuss your infrastructure](mailto:shemarmarks.tech@gmail.com?subject=Infrastructure%20project%20enquiry)** · **[Services & portfolio](https://shemarhn.github.io/)** · **[LinkedIn](https://www.linkedin.com/in/shemar-marks-11ba4820b/)**

### What you can hire me for

| Client need | Work and deliverables |
| --- | --- |
| **Deploy & migrate** | Linux/AWS deployment, Terraform or scripts where useful, migration and rollback steps, architecture notes and handover. |
| **Secure & operate** | Baseline assessment, Linux access/network/service hardening, verification results, change record and operations checklist. |
| **Monitor & maintain** | Health checks, logs and useful alerts, troubleshooting, validated monitoring configuration and response procedures. |
| **Back up & recover** | Backup configuration, restore workflow, integrity checks, recovery exercises and documented limits. |
| **Ongoing infrastructure care** | Agreed recurring monitoring/backup/patch reviews, resource health, configuration upkeep, troubleshooting and concise operational reporting. |

### How I work

Understand the workload and constraints, agree scope and acceptance checks, implement the change, verify the result, then hand over configuration and runbooks. One-off work can continue into an agreed monthly maintenance scope. Support hours, included tasks and response expectations are defined for each engagement; no 24/7 cover or production SLA is implied.

### Infrastructure proof

**[Northstar Repairs: migration & recovery](https://github.com/Shemarhn/northstar-aws-recovery)**

Executed synthetic engagement: migrated a Python/SQLite workload from Proxmox to AWS with Terraform, S3 backups and CloudWatch/SNS. A replacement server started with zero jobs and recovered all six, including `DR-TEST`, with integrity and health `ok`. One operator-observed recovery took **12 minutes exactly**, **2026-10-04 20:32:16–20:44:16 UTC**, including CloudShell recycling and Terraform reinstallation. AWS resources were destroyed after evidence preservation.

[Case study](https://github.com/Shemarhn/northstar-aws-recovery/blob/main/docs/CASE-STUDY.md) · [Recovery timeline](https://github.com/Shemarhn/northstar-aws-recovery/blob/main/evidence/disaster-recovery/recovery-timeline.md) · [Evidence](https://github.com/Shemarhn/northstar-aws-recovery/tree/main/evidence)

**[Cedarfield: Linux hardening & operations](https://github.com/Shemarhn/cedarfield-linux-operations)**

Executed synthetic Ubuntu/WSL2 engagement: assessed a working application host, reduced peer-visible tested ports from two to one, replaced root app execution with a dedicated service identity, restricted private configuration to `0600`, verified key-only SSH and firewall denial, and triggered a real Fail2ban ban with safe failed-key events. The three-record workload remained healthy. Backup integrity, rollback and final re-hardening checks passed.

[Case study](https://github.com/Shemarhn/cedarfield-linux-operations/blob/main/docs/CASE-STUDY.md) · [Evidence](https://github.com/Shemarhn/cedarfield-linux-operations/tree/main/evidence) · [Operations runbook](https://github.com/Shemarhn/cedarfield-linux-operations/blob/main/docs/RUNBOOK.md)

Both engagements use synthetic business data. They demonstrate executed lab work, not paid-client delivery or production uptime. Northstar's duration is one observation, not a repeatability guarantee or measured RPO. Cedarfield ran locally in isolated WSL2 namespaces, not on Proxmox; its local backup is not independent disaster recovery.

### Infrastructure tools

Linux, AWS, Terraform, Proxmox, Bash and Python. Practical work spans deployment, access controls, systemd services, monitoring, backup and recovery. The case studies identify which controls were designed, configured and actually observed.

### Supporting software work

- [GitHub Ranked](https://github.com/Shemarhn/Github_Ranked): Next.js/TypeScript contribution dashboard and embeddable badges with GitHub API integration and caching.
- [ClearLedger](https://github.com/Shemarhn/ClearLedger): Flutter personal-finance application project with a FastAPI backend and Supabase.

### Start a conversation

Tell me **what you're running**, **what is not working or needs to change**, and **the outcome you want**. We can define a practical scope, acceptance checks and the handover from there.

**[shemarmarks.tech@gmail.com](mailto:shemarmarks.tech@gmail.com?subject=Infrastructure%20project%20enquiry)** · **[Portfolio](https://shemarhn.github.io/)**

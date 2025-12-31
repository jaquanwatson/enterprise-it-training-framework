# Enterprise IT Staff Development Framework

**A comprehensive onboarding and technical training curriculum designed to standardize Tier 1/2 IT support operations.**

## Executive Summary
In high-velocity IT environments, the time-to-competency for new technicians is a critical metric. This repository contains the curriculum structure, lab configurations, and assessment standards for a **4-6 week intensive training program**.

This framework was designed to:
* **Reduce Onboarding Time:** Cut the time from "new hire" to "ticket closer" by ~40%.
* **Standardize Knowledge:** Ensure all staff adhere to the same troubleshooting methodologies and NIST-aligned security best practices.
* **Simulate Real Scenarios:** Utilizes a virtualized home lab environment to replicate common enterprise issues (Active Directory lockouts, DNS failures, Printer configs) without risking production assets.

## Lab Environment Architecture
This training program relies on a virtualized environment that mimics a small-to-medium business network.

* **Hypervisor:** VMware Workstation / vSphere
* **Domain Controller:** Windows Server 2022 (Active Directory DS, DNS, DHCP)
* **Endpoints:** Windows 10/11 Enterprise Clients
* **Ticket System:** osTicket (Self-hosted for ticket lifecycle simulation)

## Curriculum Modules

| Phase | Focus Area | Key Skills |
| :--- | :--- | :--- |
| **Phase 1** | **Core Infrastructure** | Active Directory Users & Computers, Group Policy, NTFS Permissions. |
| **Phase 2** | **Networking** | DNS/DHCP troubleshooting, IP addressing, VPN client configuration. |
| **Phase 3** | **Security & Ops** | Password hygiene, MFA troubleshooting, Incident Response basics. |

## Outcomes & KPI Impact
Implementing this structured approach typically yields the following operational improvements:
* **First Contact Resolution (FCR):** Increases as technicians understand root causes.
* **Escalation Rate:** Decreases for Tier 1 issues.
* **SLA Compliance:** Improved adherence to response/resolution time targets.

---
*Created by Jaquan Greene-Watson - IT Operations Manager*

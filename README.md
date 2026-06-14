# Enterprise Group Policy Hardening & Ransomware Mitigation Baselines
An automated security engineering workspace focused on deploying strict baseline defensive registries to a standalone Windows Server 2022 instance in Microsoft Azure.

## Project Architecture
This repository demonstrates corporate endpoint hardening principles by injecting security configuration values directly into the system registries through Infrastructure as Code (IaC).

## Core Policy Baselines Deployed
* **Ransomware Mitigation (`SEC-Ransomware-Mitigations`):** Programmatically disabled Windows Script Host (WSH) registry endpoints to block email-borne script payloads (.vbs, .js) from executing.
* **Data Privacy Protection (`SEC-System-Privacy-Hardening`):** Enforced enterprise-grade BitLocker volume encryption parameters utilizing advanced 256-bit AES algorithms.
* **Targeted Allocation:** Mapped security configurations directly to an isolated Organizational Unit (OU) layer hosting production production assets.

## Skills Demonstrated
* Security Configuration Management
* Windows Registry Hardening
* Group Policy Architecture & Policy Linking
* PowerShell Automation & Infrastructure as Code (IaC)

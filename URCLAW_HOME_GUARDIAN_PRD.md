# PRD: UrClaw Home Guardian (v1.0)
**Concept:** A local AI sentinel that monitors your smart home network and personal files for data leakage and privacy vulnerabilities.
**Positioning:** "Your Privacy shouldn't be a Part-Time Job."

## 1. Problem Statement
Smart homes are leaking data to manufacturers and data brokers 24/7. Monitoring this manually requires network engineering knowledge that 99% of people don't have.

## 2. Core Features

### A. The Network Sentry
- **DNS Monitoring:** Automatically detects when a Smart TV or appliance attempts to reach out to known data-broker domains.
- **Traffic Intercept:** Alerts the user (via local dashboard) if unencrypted PII is being sent over the network.

### B. The Forensic File Audit
- **Metadata Scrubbing:** Scans local documents and images for hidden GPS data, camera serial numbers, and creator IDs before they are uploaded anywhere.
- **Exposure Map:** A visual map showing which local folders have been "touched" by cloud-synced apps (Dropbox, iCloud, etc.).

### C. The "Kill-Switch" Command
- A single voice command ("Ezra, Go Dark") that disconnects all IoT devices from the internet while keeping the local AI agent functional.

## 3. Implementation
- **Hardware:** Runs on the UrClaw Appliance (Mac Mini/Studio).
- **Software:** Python-based network packet sniffer + local Llama-3.2-3B for threat classification.

## 4. Business Model
- Included in the **UrClaw Pro** ($4,999) package.
- $49/mo "Sovereignty Subscription" for continuous threat-domain updates.

---
**Prepared by:** Ezra (Chief of Staff)
**Date:** 2026-02-11

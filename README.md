# TRAFALGAR | Enterprise Defense Matrix

**TRAFALGAR v12.0** is an enterprise-grade security dashboard and simulation framework built with a modern **Claymorphic UI** design system, featuring a sophisticated beige and maroon color palette, real-time telemetry graphs, SCIM directory synchronization, and automated incident response (SOAR) playbooks.

---

## 🌟 Key Features & Architecture

- **Claymorphic Design System** (`--surface`, `--bg-main`): Soft, tactile UI components with multi-layered box shadows simulating 3D depth and physical materiality.
- **Real-Time Network Telemetry**: Dynamic live-updating bar chart visualization simulating network packet frequency and traffic spikes.
- **Employee Directory & SCIM Lifecycle Management**
  - Full employee roster management with role assignments (Admin, HR, Developer, Contractor).
  - Onboarding, suspension/offboarding workflows, and automated FIDO2 MFA enforcement.
- **Endpoint Telemetry & Posture Assessment**
  - Live monitoring of employee workstations (OS health, disk encryption via FileVault/BitLocker, and EDR status).
  - Interactive isolation and remote posture remediation (*Fix Posture* / *Isolate PC*).
- **Insider Threat & Data Exfiltration Defenses**
  - Dynamic user ID watermarking on document downloads.
  - Clipboard restrictions and high-risk country geofencing simulations.
- **Supply Chain & Automated Incident Response (SOAR)**
  - Content Disarm and Reconstruction (CDR) sandboxing simulation for malicious file uploads.
  - Deception technology featuring interactive Canary Tokens that trigger automated account lockouts and network isolation.
- **Key Governance & Advanced Cryptography**
  - Bring Your Own Key (BYOK) and Hold Your Own Key (HYOK) management modules.
  - Simulated Client-Side Sharding (scattering files across AWS, Azure, and GCP).
- **AI Governance & Immutable Audit Logging**
  - Automated PII data classification scanning (SSNs, credit cards, legal contracts).
  - Append-only cryptographic hash blockchain ledger for immutable audit trails.

---

## 📁 Project Structure

```plaintext
├── index.html       # Complete single-file application containing HTML, CSS, and JS
└── README.md        # Project documentation
```

---

## 🎨 Color Palette & Typography

| Token | Value | Description |
|---|---|---|
| Background Main | `#EAE3D9` | Soft Beige |
| Surface Cards | `#F4EFE6` | Raised Clay Surface |
| Primary Accent (Maroon) | `#6B1D2F` / `#9B334A` | Maroon |
| Text Main / Muted | `#2D1B1E` / `#7A686B` | Body & secondary text |
| `--warn` | `#B87D36` | Warning alert state |
| `--err` | `#A32A29` | Error alert state |

**Fonts:** [Inter](https://fonts.google.com/specimen/Inter) (UI text) & [JetBrains Mono](https://fonts.google.com/specimen/JetBrains+Mono) (terminal logs and telemetry)

---

## 🚀 Quick Start / Installation

Because TRAFALGAR is packaged as a high-performance single-file web application, **zero build steps or package installations are required!**

1. Clone or download the repository:

   ```bash
   git clone https://github.com/minaaalib/Security-App.git
   ```

2. Open the project folder:

   ```bash
   cd Security-App
   ```

3. Launch `index.html` directly in any modern web browser:
   - **macOS:** `open index.html`
   - **Linux:** `xdg-open index.html`
   - **Windows:** Double-click `index.html` or open it via your preferred browser.

---

## 🕹️ Interactive Modules Guide

| Module | What you can do |
|---|---|
| **Overview (Dashboard)** | Monitor cloud health metrics, view live network traffic tickers, execute global cloud audits, or engage emergency lockdowns. |
| **Identity (SCIM)** | Provision new employees, audit active roles and MFA statuses, or trigger offboarding workflows. |
| **Endpoints** | Inspect real-time CPU/RAM usage across workstations, fix non-compliant security postures, or isolate compromised hardware. |
| **Insider Threat** | Test geofence breach simulations and watermarking logic. |
| **Supply Chain** | Test malicious PDF uploads against the CDR sandbox or trigger canary files to watch automated SOAR playbooks execute in real time. |
| **Crypto & SOAR** | Simulate external HSM key revocations and multi-cloud file sharding. |
| **Governance** | Verify immutable cryptographic audit log integrity. |
| **Audit Logs** | Review real-time streaming logs with timestamp tracking and severity-based color coding. |

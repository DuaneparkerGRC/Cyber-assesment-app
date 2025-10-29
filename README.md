# Cybermachan - Baseline Cyber Assessment
**By Dulara Paranawidana - Professional GRC Specialist with Technical Depth**

---

## What this project is
A **fast, plain-language cybersecurity baseline** built for SMEs, startups, and consultants.  
Users complete a **<60-second questionnaire** and receive:
- A **0–100 security posture score**
- A **downloadable, step-by-step remediation plan** (Word/PDF)
- Clear priorities: **Today / This Week / Ongoing**

**Standards alignment:** Designed to align with **ACSC Essential Eight (baseline intent)** and to **support** **NIST CSF (Identify/Protect)** and **ISO/IEC 27001 Annex A** fundamentals.

---
<img width="1433" height="819" alt="Screenshot 2025-10-29 223643" src="https://github.com/user-attachments/assets/fd173565-4582-47ae-b753-0af552be47ab" />

## Why I built it (GRC value)
Most small teams ask, *“Where do we start?”*  
As a **GRC practitioner**, I needed a consistent, evidence-based **intake and triage** that:
- Translates frameworks into **business-ready controls**
- Produces **prioritized, actionable work** (not just policy text)
- Works for **non-technical stakeholders** while satisfying **assurance** needs

This project standardizes my consulting kickoff, reduces time-to-value, and makes a **baseline tool** freely available to the community.

---
<img width="1438" height="740" alt="Screenshot 2025-10-29 223713" src="https://github.com/user-attachments/assets/93d104dc-f655-4c9a-ac28-38e8589a1cec" />

## How I approached it (methods + technical leadership)
1. **Control Design & Mapping**  
   - Converted E8/NIST/ISO guidance into **plain questions** and **minimum viable controls** across devices, websites, and baseline operations.
2. **Rules Engine & Scoring**  
   - Built a **data-driven mapping** (answers → remediation bundles) and a transparent **0–100** scoring model with heavier weights on MFA, patching, backups+restore, admin separation, encryption, and website protections.
3. **Document Automation**  
   - Automated **.docx/PDF** plan generation: logo/brand, TOC, and **only relevant sections** based on responses.
4. **UX for Adoption**  
   - **Tick-through** form, non-technical language, and **priority buckets** so small teams can act immediately.
5. **Privacy by Design**  
   - Anonymous use by default; any optional gate (name/email/company) is **no-spam** and used only for impact metrics.

---
<img width="1432" height="1063" alt="Screenshot 2025-10-29 223828" src="https://github.com/user-attachments/assets/8f3bec2b-2257-4221-a457-684f55cfbd4d" />

## What I learned (and demonstrate as a GRC specialist)
- **Framework-to-Control Translation:** Turning E8/NIST/ISO into **concrete, verifiable steps** drives adoption and auditability.  
- **Risk-Weighted Scoring:** Transparent weights and clear priority bands accelerate stakeholder buy-in.  
- **Tech-Fluent GRC:** Building the **rules engine**, **export pipeline**, and **content store** (JSON) ensures the guidance is maintainable and versionable.  
- **Change Enablement:** Plain English, short cycles, and immediate “win” items increase completion rates and measurable uplift.  
- **Trust Engineering:** Anonymous flows and visible privacy posture increase honest responses and wider usage.

---
<img width="1433" height="294" alt="Screenshot 2025-10-29 223855" src="https://github.com/user-attachments/assets/73f452d6-2e8a-4271-b082-cf4fb40178a7" />

## Architecture at a glance

- **Questionnaire (3 sections):**
  - **Devices:** Windows/Mac/Linux, iOS/Android, Servers/VMs, Network gear, Printers, IoT/POS/Kiosks (+ simple context)
  - **Website:** Info-only / Logins / PII / Payments; protections (HTTPS, WAF/bot, updates, backups, health checks, payment fraud checks); privacy notice
  - **Baseline (14 items):** App allow-listing, app/OS patching cadence, macro policy, risky features off, admin separation & review, MFA coverage, backups & restore testing, asset inventory, top-risks plan, data location, encryption, endpoint protection, awareness training
- **Scoring:** Start 100 → subtract weighted gaps (treat **“Not sure”** as risky) → **Red/Amber/Green** band
- **Remediation Engine:** Answer → **bundle(s)** with **Why it matters** + **How to do it** (OS/browser click-paths)
- **Export:** Branded **.docx/PDF** with logo, title, attribution, TOC; **only relevant** guidance included

---

## Professional positioning
- **GRC & Assurance:** Control design, policy-to-practice mapping, measurable uplift  
- **Risk & Metrics:** Practical KRIs/KPIs (coverage, patch SLAs, backup restore success), posture scoring  
- **Technical Enablement:** Rules engines, document automation, content versioning, privacy-first flows  
- **Stakeholder Adoption:** Non-technical UX, prioritized remediation, fast time-to-value

---

## Using the app
1. Complete the **1-minute questionnaire** (Devices → Website → Baseline).  
2. Get your **0–100 score** and prioritized actions.  
3. Download the **step-by-step remediation plan** (Word/PDF).  
4. Share feedback to shape the next release.

## Click this link to try it yourself

👉 [cybermachan.online](https://cybermachan.online)


---

**Created by Dulara Paranawidana - _Cybermachan_**

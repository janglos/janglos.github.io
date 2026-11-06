---
layout: single
title: Experience
permalink: /experience/
author_profile: true
classes: wide
---

### Founder | zahod.it
**Jul 2026 – Present** · own side business, alongside NXP

Built and run [zahod.it](https://zahod.it) (site in Czech): a bot that reads photos and PDFs of Czech receipts and invoices with an AI vision model and writes them into the ABRA Flexi accounting system. Accountants use it daily for their client companies.

*   **Product:** Two ways in, a Telegram bot and shared Google Drive folders. Supplier matching against the company's address book, duplicate detection, and booking suggestions based on the supplier's history.
*   **Never guess:** Unreadable or ambiguous documents are flagged and skipped rather than written; the accountant always has the last word.
*   **Engineering:** Python, LLM vision extraction, the ABRA Flexi REST API, CI with test tiers against a local ABRA instance, writes blocked at the transport layer in dry runs, an external watchdog and encrypted off-site backups.
*   **Measured from day one:** Every processed document is logged, so the automation rate is known rather than guessed.

---

### Product Manager | NXP Semiconductors
**Sep 2025 – Present**

Promoted from Product Owner. I own strategy, budget and roadmap for a release train of 9 software components, mostly automotive networking, built by 6 teams (47 people). The software ships with NXP chips and is used across the automotive market by OEMs and Tier-1 suppliers. Co-led the SAFe transformation.

<div class="impact-card">
  <div class="impact-title">Key Strategic Impacts</div>
  <div class="impact-grid">
    <div class="impact-item"><span class="impact-icon">🎯</span><span class="impact-label">9 Components, 47 People</span></div>
    <div class="impact-item"><span class="impact-icon">⚡</span><span class="impact-label">New Product Co-funded by 3 PLs</span></div>
    <div class="impact-item"><span class="impact-icon">🤖</span><span class="impact-label">AI Planning Tools (0.5–1 FTE Saved)</span></div>
    <div class="impact-item"><span class="impact-icon">👥</span><span class="impact-label">Best of 20+ Trains (PMO)</span></div>
  </div>
</div>

*   **Funding and roadmap:** Agree with each funding product line what the train delivers for its budget, and prioritise features from OEM and Tier-1 use cases against technical debt.
*   **New product:** Made the case for a new integrated Ethernet networking product, now co-funded by three product lines.
*   **AI-assisted planning:** Built planning and reporting tools in Python, with an LLM layer for checks that fixed rules can't cover. They save an estimated 0.5–1 FTE of manual ticket work and are used by the release train engineer and all Product Owners. A second train is piloting them, and the PMO lead named the approach the best among 20+ trains at NXP.
*   **Monorepo:** Set the vision for moving hundreds of repositories into one Bazel monorepo and drove the proof of concept before handing execution to colleagues.
*   **People:** Mentor the 6 Product Owners and coordinate the train's architects and DevOps lead.

---

### Product Owner | NXP Semiconductors
**Feb 2023 – Aug 2025**

Grew the gPTP time-synchronisation stack, a building block of zonal vehicle architectures, into a multi-platform product line, growing support from 3 to 15+ microcontrollers.

<div class="impact-card">
  <div class="impact-title">Key Achievements & Business Impact</div>
  <div class="impact-grid">
    <div class="impact-item"><span class="impact-icon">⏱️</span><span class="impact-label">Lead Time Reduced to &lt;4 Weeks</span></div>
    <div class="impact-item"><span class="impact-icon">🔄</span><span class="impact-label">Automated CI/CD (5d to &lt;2h)</span></div>
    <div class="impact-item"><span class="impact-icon">🧩</span><span class="impact-label">3 → 15+ Supported MCUs</span></div>
    <div class="impact-item"><span class="impact-icon">🛡️</span><span class="impact-label">ASPICE Lvl 3 & IATF Compliant</span></div>
  </div>
</div>

*   **Time to market:** Cut software delivery after silicon availability from 3 months to under 4 weeks by running workstreams in parallel.
*   **CI/CD:** Brought full integration test campaigns down from 5 days to under 2 hours with automated pipelines and pull-request gating.
*   **R&D:** Led a project to improve the time-synchronisation precision of the stack.
*   **Quality:** Kept the product at ASPICE Level 3 and through two IATF audits.
*   **Budget and scope:** Negotiated budget and scope with several NXP product lines, balancing internal roadmaps with customer requests.

---

### Team Leader | Garrett - Advancing Motion
**Apr 2022 – Jan 2023**

Led a team of 6 data scientists, analysts and developers in Garrett's global intrusion detection (IDS) team. The team owned the core detection algorithms, the tuning tools and early prototypes; the product went into production with several customers.

*   **Data pipelines:** Tuning and verification ran as Apache Airflow pipelines over large CAN capture datasets in S3, and field engineers used the tools to tune detection for customers.
*   **Tooling:** Designed the move of the tooling from MATLAB to Python with a database and delivered the first prototypes.
*   **ML:** Supervised an ML prototype that traced engine fault codes back to the failing component using vehicle network data.
*   **Stakeholders:** Main link between data experts, embedded developers, QA and automotive customers.
*   **Talks:** Presented the IDS work at DefCamp 2021 and IAA 2022.

---

### Algorithm Development Engineer | Garrett - Advancing Motion
**Jul 2021 – Apr 2022**

Automotive cybersecurity in an international team, between embedded networks and data analysis.

*   **Algorithms:** Designed and refined anomaly-detection algorithms for CAN and Automotive Ethernet intrusion detection; the embedded team ported them to C for production ECUs.
*   **Tooling:** Worked on the team's MATLAB analysis tooling for network capture files (CAN, J1939, Ethernet), which I later led as team leader.
*   **Toolchain:** Maintained the CAN IDS ruleset generation toolchain and made it faster.

---

### Embedded Software Engineer & Researcher | CEITEC - Central European Institute of Technology
**Nov 2013 – Jun 2021** · part-time during MSc studies, full-time from 2015 alongside PhD and teaching

Embedded software, control algorithms and simulation tools for automotive systems in EU H2020 projects.

*   **EU projects:** Developed embedded software and control algorithms for automotive ECUs in OSEM-EV, 3Ccar, AutoDrive and 1000kmPLUS. (See [Publications](/publications/))
*   **Test bench team:** In OSEM-EV, led four engineers building the software for an EV thermal-management test bench. I designed the high-level control and split the component work among the team.
*   **Vehicle model:** Created a thermal and electrical model of a complete electric vehicle and ran simulations with AVL.
*   **FMUtoolbox:** Built the [FMUtoolbox](/publications/#fmutoolbox-for-matlabsimulink) from scratch: MATLAB/Simulink libraries, a GUI and low-level S-functions for multi-domain co-simulation.
*   **Test bench:** Built an automotive HVAC&R test bench from the mechanics up, programmed and ran it, including data acquisition for validation.
*   **Embedded control:** Wrote low-level communication stacks (CAN, LIN, SPI) and implemented model predictive control on automotive microcontrollers, validated processor-in-the-loop. Non-linear MPC of cabin climate saved 41 % energy in a cold-weather test case (IEEE TVT 2021).

---

### Building Management System (BMS) Architecture Specialist | Masaryk University
**Aug 2007 – Sep 2015** · part-time

Technical architecture of the university's BACnet building management system.

*   **Scaling:** Grew the network from 10 to 30+ buildings and more than 1,000 BACnet devices.
*   **Network Governance:** Designed the complete BACnet network topology (including BBMD, routing, and data archiving) and established standard testing procedures for hardware vendors.
*   **Performance:** Found and fixed communication bottlenecks, which improved data availability and alarm reliability.

---

## Skills

### Product Management & Leadership
<span class="badge badge-lead">Product Management</span>
<span class="badge badge-lead">Product Road Mapping</span>
<span class="badge badge-lead">Product Vision</span>
<span class="badge badge-lead">Prioritization</span>
<span class="badge badge-lead">Leadership</span>
<span class="badge badge-lead">Change Management</span>
<span class="badge badge-lead">Scaled Agile Framework (SAFe)</span>
<span class="badge badge-lead">Coaching & Mentorship</span>
<span class="badge badge-lead">Stakeholder Management</span>

### Technical & Analytical
<span class="badge badge-tech">Software Development</span>
<span class="badge badge-tech">DevOps (CI/CD)</span>
<span class="badge badge-tech">Bazel</span>
<span class="badge badge-tech">Monorepo</span>
<span class="badge badge-tech">Algorithms</span>
<span class="badge badge-tech">Cybernetics</span>
<span class="badge badge-tech">Embedded Systems (ECUs)</span>
<span class="badge badge-tech">Communication Networks (BACnet, CAN, Ethernet)</span>
<span class="badge badge-tech">Data Analysis</span>
<span class="badge badge-tech">Predictive Modeling</span>
<span class="badge badge-tech">MATLAB/Simulink</span>

---

## Education

*   **Brno University of Technology** – *Faculty of Electrical Engineering and Communication*
    *   🎓 **Ph.D. in Cybernetics, Automation and Measurement** *(2015 – 2020)*
        Thesis: *Modeling and Control of Electric and Thermal Flows in Fully Electric Vehicles*
    *   🎓 **Ing. (MSc) in Cybernetics, Automation and Measurement** *(2013 – 2015)*
    *   🎓 **Bc. in Automation and Measurement Technology** *(2009 – 2013)*

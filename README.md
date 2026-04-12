# 📋 PM Process Groups Study Guide

> An interactive study dashboard for PMI Project Management — covering all **5 process groups**, **49 processes**, and full **ITTO breakdowns** with exam tips.

---

## 🌐 Live Demo

**[👉 Open Study Guide](https://qminlim.github.io/pm-study-guide)**

---

## 📸 Preview

<!-- Light mode badge -->
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://img.shields.io/badge/Theme-Dark%20Mode%20Ready-1D9E75?style=for-the-badge&logo=github&logoColor=white">
  <img src="https://img.shields.io/badge/Theme-Light%20Mode%20Ready-1D9E75?style=for-the-badge&logo=github&logoColor=white" alt="Theme badge">
</picture>
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://img.shields.io/badge/Processes-49%20Total-185FA5?style=for-the-badge">
  <img src="https://img.shields.io/badge/Processes-49%20Total-185FA5?style=for-the-badge" alt="49 processes">
</picture>
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://img.shields.io/badge/Groups-5%20Phases-854F0B?style=for-the-badge">
  <img src="https://img.shields.io/badge/Groups-5%20Phases-854F0B?style=for-the-badge" alt="5 phases">
</picture>

---

## ✨ Features

| Feature | Description |
|---|---|
| 🗂 **By Process Group** | Navigate all 5 phases — click any card to reveal full ITTO breakdown |
| 🗺 **Full Overview** | See all 49 processes at a glance; click to jump to detail |
| 📄 **Contract Types** | Quick reference for Fixed-Price, Cost-Reimbursable, and T&M |
| 💡 **Exam Tips** | Key formulas and gotchas highlighted per process |
| 🌙 **Dark & Light Mode** | Automatically adapts to your system theme |
| 📱 **Responsive** | Works on desktop, tablet, and mobile |

---

## 🗂 The 5 Process Groups

### 🚀 Initiating
Formally authorize the project and identify key stakeholders.

| # | Process | Key Output |
|---|---|---|
| 1 | Develop Project Charter | Project Charter |
| 2 | Identify Stakeholders | Stakeholder Register |

---

### 📋 Planning
Define scope, schedule, cost, quality, resources, risk, procurement, and stakeholder engagement.

| # | Process | Key Output |
|---|---|---|
| 3 | Develop PM Plan | Project Management Plan |
| 4 | Plan Scope Management | Scope Management Plan |
| 5 | Collect Requirements | Requirements Traceability Matrix |
| 6 | Define Scope | Project Scope Statement |
| 7 | Create WBS | Scope Baseline |
| 8 | Plan Schedule Management | Schedule Management Plan |
| 9 | Define Activities | Activity List |
| 10 | Sequence Activities | Schedule Network Diagrams |
| 11 | Estimate Activity Durations | Duration Estimates |
| 12 | Develop Schedule | Schedule Baseline |
| 13 | Plan Cost Management | Cost Management Plan |
| 14 | Estimate Costs | Cost Estimates |
| 15 | Determine Budget | Cost Baseline |
| 16 | Plan Quality Management | Quality Management Plan |
| 17 | Plan Resource Management | Resource Management Plan |
| 18 | Estimate Activity Resources | Resource Requirements |
| 19 | Plan Communications Management | Communications Management Plan |
| 20 | Plan Risk Management | Risk Management Plan |
| 21 | Identify Risks | Risk Register |
| 22 | Perform Qualitative Risk Analysis | Updated Risk Register |
| 23 | Perform Quantitative Risk Analysis | Updated Risk Register |
| 24 | Plan Risk Responses | Change Requests |
| 25 | Plan Procurement Management | Procurement Management Plan |
| 26 | Plan Stakeholder Engagement | Stakeholder Engagement Plan |

---

### ⚙️ Executing
Perform the work defined in the PM plan; manage people, quality, knowledge, and procurement.

| # | Process | Key Output |
|---|---|---|
| 27 | Direct & Manage Project Work | Deliverables, Work Performance Data |
| 28 | Manage Project Knowledge | Lessons Learned Register |
| 29 | Manage Quality | Quality Reports |
| 30 | Acquire Resources | Project Team Assignments |
| 31 | Develop Team | Team Performance Assessments |
| 32 | Manage Team | Change Requests |
| 33 | Manage Communications | Project Communications |
| 34 | Implement Risk Responses | Change Requests |
| 35 | Conduct Procurements | Selected Sellers, Agreements |
| 36 | Manage Stakeholder Engagement | Change Requests |

---

### 👁 Monitoring & Controlling
Track, review, and regulate project progress; manage changes.

| # | Process | Key Output |
|---|---|---|
| 37 | Monitor & Control Project Work | Work Performance Reports |
| 38 | Perform Integrated Change Control | Approved Change Requests |
| 39 | Validate Scope | Accepted Deliverables |
| 40 | Control Scope | Work Performance Information |
| 41 | Control Schedule | Schedule Forecasts |
| 42 | Control Costs | Cost Forecasts |
| 43 | Control Quality | Verified Deliverables |
| 44 | Control Resources | Work Performance Information |
| 45 | Monitor Communications | Work Performance Information |
| 46 | Monitor Risks | Work Performance Information |
| 47 | Control Procurements | Closed Procurements |
| 48 | Monitor Stakeholder Engagement | Work Performance Information |

---

### ✅ Closing
Finalize all activities, obtain formal acceptance, archive information, release team.

| # | Process | Key Output |
|---|---|---|
| 49 | Close Project or Phase | Final Report, Final Product Transition |

---

## 🧠 Key Formulas to Remember

```
PERT (Beta Distribution)   →  (O + 4M + P) / 6
Standard Deviation         →  (P − O) / 6
Triangle Distribution      →  (O + M + P) / 3
Communication Channels     →  n(n − 1) / 2
EMV (Decision Tree)        →  Probability × Impact Cost
```

---

## ⚖️ Contract Types at a Glance

```
Fixed-Price       →  Seller bears risk  |  Use when scope is well-defined
Cost-Reimbursable →  Buyer bears risk   |  Use when scope is unclear
Time & Material   →  Buyer bears risk   |  Use when scope is high-level only
```

**Fixed-Price subtypes:** FFP · FPIF · FP-EPA  
**Cost-Reimbursable subtypes:** CPFF · CPIF · CPAF

---

## ⚡ Exam Tips

- **Validate Scope** = customer accepts deliverables (effectiveness)  
- **Control Quality** = team verifies correctness (correctness)  
- Data flow: **Work Performance Data → Information → Reports**  
- Conflict resolution best-to-worst: **Problem Solving → Compromising → Forcing → Smoothing → Withdrawal**  
- **Scope Baseline** = Scope Statement + WBS + WBS Dictionary  
- **Cost Baseline** = all activity costs + contingency reserves  
- **Project Budget** = Cost Baseline + Management Reserves  
- If it's **not in the WBS**, it's **not in the project**

---

## 🛠 Built With

- **Vanilla HTML/CSS/JS** — zero dependencies, runs in any browser
- **CSS custom properties** — automatic dark/light mode via `prefers-color-scheme`
- **No frameworks** — fully self-contained single file

---

## 🚀 Run Locally

```bash
# Clone the repo
git clone https://github.com/qminlim/pm-study-guide.git

# Open in browser — no server needed
open index.html
```

Or install the **Live Server** VS Code extension and click **Go Live**.

---

## 📁 File Structure

```
pm-study-guide/
└── index.html        # Entire app — self-contained
└── README.md         # This file
```

---

## 📖 Source Material

Based on the **PMI Process Groups: A Practice Guide** — covers all knowledge areas and process groups aligned with the PMBOK framework.

---

<div align="center">

Made for PM students who learn better by doing 📚

</div>
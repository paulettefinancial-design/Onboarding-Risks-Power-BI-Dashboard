Project Overview

This project analyzes the schedule impact of onboarding risks within a fictional but realistic enterprise onboarding process. Using a Tornado‑style sensitivity chart and a volatility comparison, the dashboard identifies which risks contribute most to schedule overruns and which risks fluctuate the most across onboarding cycles.

The goal is to demonstrate project‑management analytics skills using Power BI, including risk quantification, sensitivity modeling, and operational insight generation.Dataset

The dataset contains 10 onboarding risks with the following fields:

Risk – Name of the onboarding risk

LowImpact – Best‑case schedule impact (days)

HighImpact – Worst‑case schedule impact (days)

Range – Volatility (HighImpact – LowImpact)

Category – Operational grouping (Planning, Resourcing, Client, Vendor, etc.)

Description – Short explanation of the risk

File: data/onboarding_risks.csv

Dashboard Visuals

1. Sensitivity Analysis (Schedule Overrun)

Shows the worst‑case impact of each risk on onboarding duration.

Scope creep is the top risk (up to 105 days)

Internal resource constraints and data quality issues follow closely

Client‑related delays also contribute significantly

2. Risk Volatility (Day Range)

Shows how much each risk fluctuates across onboarding cycles.

Scope creep is the most volatile (27‑day range)

Internal resource constraints and data quality issues also show high variability

Vendor dependencies and late sign‑offs show lower volatility

Summary Metrics

Top risk: Scope creep (105 days worst‑case)

Total risks: 10

Average range: 11.7 days

Most volatile risk: Scope creep

Max high impact: 105 days

Screenshots are located in the screenshots/ folder.

Key Insights

Scope creep is both the highest‑impact and most volatile risk, making it the top priority for mitigation.

Internal resource constraints significantly affect onboarding timelines and fluctuate widely depending on staffing availability.

Data quality issues create hidden delays due to cleanup and rework.

Client‑related delays (initial data + sign‑offs) consistently push timelines and should be addressed through expectation‑setting and communication.

Vendor dependencies have lower volatility but still introduce meaningful delays.

Tools & Techniques

Power BI – Data modeling, DAX measures, sensitivity analysis visuals

Risk Quantification – Low/High impact modeling

Volatility Analysis – Range calculations

Project Management Concepts – Risk prioritization, onboarding workflow analysis

What I Learned

How to translate project‑management risks into quantifiable metrics

How to build Tornado‑style sensitivity visuals in Power BI

How volatility analysis helps prioritize mitigation strategies

How to structure a professional analytics project for GitHub

How to communicate PM insights visually and clearly

Repository Structure

Project_OnboardingRisks/
│
├── README.md
├── data/
│   └── onboarding_risks.csv
├── pbix/
│   └── Project2_OnboardingRisks.pbix
└── screenshots/
    ├── sensitivity_chart.png
    ├── volatility_chart.png
    └── summary_metrics.png

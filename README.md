# IPH Dip Tracker – Reassignment Lag Analysis

This project addresses misattributed productivity issues in internal audit dashboards. Specifically, it investigates cases where KYC tasks were reassigned to new investigators but still counted toward the IPH (Investigations Per Hour) of the original assignee. This lag in attribution led to inaccurate performance metrics.

---

## Project Overview

- Use Case: Analyze reassigned tasks to determine resolution lag and IPH dip attribution issues.
- Dataset: 1000+ simulated KYC tasks across BOV and IDV queues.
- Objective: Identify delay (in hours) between reassignment and resolution.
- Outcome: Built a dynamic Excel tracker to visualize lag %, SLA breach, and investigator-level misattributions.

---

## Key Features

| Feature                    | Description |
|----------------------------|-------------|
| Lag Analysis               | Calculated actual SLA lag using timestamp differences |
| VLOOKUP + Config Sheet     | Dynamically pulled SLA hours from queue mapping |
| Conditional Formatting     | Applied color logic: Green (<0.7), Amber (0.7–1), Red (>1) |
| KPI Summary                | Metrics like % SLA breached, Avg Lag %, Max Lag, Investigator count |
| Pivot Table Dashboard      | Weekly view of task lag by investigator and queue |
| Sparklines & Visuals       | Mini trendlines showing SLA lag patterns |
| Audit Log Table            | Tabular log with queue, SLA %, breach status, timestamps |

---

## Tools & Techniques Used

- Microsoft Excel 365
- Pivot Tables & Charts
- VLOOKUP
- Conditional Formatting
- KPI Calculations
- Sparklines
- Dashboard Layout & Freeze Panes

---

## File Structure

├── IPH Dip Tracker – Reassignment Lag Analysis.xlsx  # Main Excel workbook with all features  
├── README.md                                         # This file  

---

## Learning Outcomes

- Identified and corrected performance metric blind spots in audit flows
- Learned to apply dynamic lookups and SLA logic using VLOOKUP
- Designed visual performance dashboards with conditional formatting and pivot charts
- Created a reusable template for lag tracking in audit workflows

---

> Created by Akshaya  
> IPH Dip Tracker – July 2025

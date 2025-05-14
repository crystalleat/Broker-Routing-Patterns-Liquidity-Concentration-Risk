# Broker-Routing-Patterns-Liquidity-Concentration-Risk (Rule 606) Project - IN PROGRESS

This project analyzes broker-dealer order routing behavior using publicly available Rule 606 disclosures.  
It creates a structured data pipeline to standardize, clean, and analyze venue routing patterns across brokers.

---

## Objectives

- Automatically pull & parse XML Rule 606 reports (Fidelity, Schwab)
- Clean and normalize venue names
- Calculate estimated shares routed (based on USD payments + CPH)
- Compute broker routing concentration metrics (Herfindahl-Hirschman Index, CR3)
- Generate clear broker routing dashboards including: (multi-chart PDF style reports)
  - Routing concentration over time (HHI trends)
  - Venue-level routing heatmaps
  - Payment vs. no payment vs. routing cost analysis
  - Estimated shares routed per venue

## Project Status

This project is currently **in progress** as part of a larger multi-part broker routing transparency study.

**Completed so far:**
- Data ingestion + cleaning
- Venue name standardization
- Estimated shares calculation
- HHI routing concentration analysis

**Currently working on:**
- CR3 (top 3 venue concentration) analysis
- Broker-level automated dashboard buildout 

Future parts will continue expanding analysis depth and reporting automation.

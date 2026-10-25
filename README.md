# GDPR Data Governance & Classification Audit: ShopNest (E-Commerce)

A GDPR audit of **ShopNest**, a fictional EU-facing online retailer with about 2 million customers. The project maps the company's personal data, traces where it flows, checks lawful basis, access, retention and data subject rights, and ends with a risk-rated findings report.

> All companies, people and data in this project are fictional and illustrative.

## What's in this repository

| File | What it contains |
|---|---|
| `ShopNest_GDPR_Audit_Report.pdf` | Audit report: summary, lineage map, findings, recommendations, roadmap |
| `ShopNest_GDPR_Audit.xlsx` | Full working papers (12 tabs, listed below) |
| `ShopNest_Data_Lineage.png` | Personal data lineage map (source → systems → external parties) |

**Workbook tabs:** Scope · Findings register · Personal data inventory · Data flows · Article 30 register (ROPA) · Lawful basis reference · RBAC design · Access review · Retention schedule · Data subject rights workflow · Breach notification workflow

## Method

1. **Scope:** systems, teams and audit objectives
2. **Personal data inventory:** 13 elements, direct vs indirect identifiers, special category check
3. **Data lineage:** 9 flows, internal vs external, transfers outside the EU
4. **Records of Processing (Art. 30):** 10 activities with purpose and lawful basis (Art. 6)
5. **RBAC & access review:** least-privilege model for 8 roles; 6 access findings
6. **Retention schedule:** periods, triggers and end actions for 10 data types
7. **Data subject rights & breach process:** Articles 15–21 and the 72-hour notification rule (Art. 33)
8. **Findings & recommendations:** risk-rated with owners and target dates

## Key findings

| Risk | Count | Examples |
|---|---|---|
| High | 4 | Manual customer exports shared by link; orphaned and over-privileged accounts; data kept forever; admin account used daily |
| Medium | 4 | Erasure requests not reaching processors; unconfirmed EU–US transfer safeguards; full date of birth collected; health data in free-text notes |
| Low | 1 | No documented Legitimate Interest Assessment |

## Skills demonstrated

GDPR (Articles 5, 6, 9, 15–21, 30, 32–34) · data mapping & lineage · data classification · data minimisation · RBAC & least privilege · access reviews (joiner–mover–leaver) · retention & storage limitation · processor management (DPAs, international transfers) · risk-based reporting

## Background

This project builds on my experience in data quality and governance for e-commerce, where tracing data from source → transformation → export is daily work. Here the same thinking is applied to **customer personal data** and GDPR.

**Author:** Priti More · [LinkedIn](https://www.linkedin.com/in/er-priti-more-2209bb27b/)

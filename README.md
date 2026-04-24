# IT-Helpdesk-Customer-Support-Ticket-Analysis-Dashboard

## Project Overview
A 3-page end-to-end Power BI report analyzing 8,469 IT helpdesk tickets. Built on a real Kaggle dataset, this report covers SLA compliance, resolution efficiency, CSAT trends, and root cause analysis across ticket types, priorities, and channels.

## Dataset
- Source: Kaggle — Customer Support Ticket Dataset by suraj520
- Rows: 8,469 | Columns: 18 (after transformation)
- Date Range: 2020-2021

## Tech Stack
- Power BI Desktop (Report + DAX + Power Query)
- Excel (.xlsx) as data source

## Key Features
- 18 DAX measures covering SLA, CSAT, MoM trend, and dynamic titles
- Star schema data model with CALENDARAUTO() Date table
- Data Quality Flagging in Power Query (Clean / Valid Open / Bad Timestamp)
- GDPR-compliant: PII columns removed in Power Query
- 3-page report: Command Center, SLA Analysis, Drill-Through Detail
- Decomposition Tree for interactive SLA root cause analysis
- Drill-through navigation from Page 1 to ticket-level detail
- Dark executive theme with semantic color system

## Report Pages
| Page | Name | Key Visuals |
| 1 | Ticket Command Center | 6 KPIs, Line, Donut, Bar, Matrix, 4 Slicers |
| 2 | SLA & Resolution Analysis | 4 KPIs, Decomposition Tree, Gauge, Scatter, Line |
| 3 | Ticket Detail Drillthrough | 3 KPIs, Detail Table (8 columns), Back Navigation |

## SLA Thresholds Used
| Priority | Max Resolution Time |
| Critical | 4 hours |
| High     | 8 hours |
| Medium   | 24 hours |
| Low      | 48 hours |

## Author
Lavanya | Data Analyst | Bengaluru, India

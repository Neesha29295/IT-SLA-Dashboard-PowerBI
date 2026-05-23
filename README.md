# IT Service Delivery — SLA Dashboard (Power BI)

## About
A live, production-grade IT Service Delivery dashboard built using Power BI Pro, tracking 120,000+ service tickets across Incidents, Tasks, Changes, and CSAT/DSAT metrics for an enterprise organisation. This dashboard is actively used by IT service delivery teams to monitor SLA compliance, resolution trends, and customer satisfaction in real time with live data refresh.

## Tools & Technologies Used

| Tool | Usage |
|---|---|
| Power BI Pro | Dashboard design, DAX measures, real-time refresh |
| ServiceNow | Primary data source (tickets, SLA data) |
| Power Automate | Automated data pipeline (ServiceNow → SharePoint) |
| SharePoint | Data storage and refresh layer |
| Microsoft Outlook | Scheduled report distribution |

---

## Dashboard Tabs

| Tab | Description |
|---|---|
| Home | Overview of all ticket volumes — Incidents, ITask, SCTask, Change |
| Incidents | SLA %, resolution time, aging, priority breakdown, location analysis |
| ITask | Task-level SLA tracking by priority, week, and assignment group |
| SCTask | Service catalogue task analysis by location and configuration item |
| Change | Change success %, emergency changes, risk analysis, region view |
| CSAT-DSAT | Customer satisfaction vs dissatisfaction trends by month and category |

---

## Key Features Built

- **Real-time data refresh** using Power BI Pro license
- **Automated data pipeline** — ServiceNow → Power Automate → SharePoint → Power BI
- **Multi-tab navigation** with button-based drill-through between dashboards
- **Dynamic slicers** for Week, Month, Quarter, Year, Tower, Priority, Location, Assignment Group
- **SLA compliance tracking** by priority (Critical, High, Moderate, Low)
- **Aging analysis** — tickets categorised as <3 days, <7 days, >7 days
- **CSAT vs DSAT trend** — monthly comparison with improvement area analysis
- **Region-wise analysis** — EMEA, APAC, Americas, Global breakdowns
- **Running weekly trends** — week-over-week SLA % and resolution time charts

---

## Data Pipeline Architecture

```
ServiceNow (Live Source)
        ↓
Power Automate (Automated extraction)
        ↓
SharePoint (Data storage)
        ↓
Power BI Pro (Real-time Dashboard)
        ↓
Outlook (Scheduled distribution)
```


## Key Insights

**Insight 1 — SLA Compliance:**
> Incident SLA compliance maintained at 91-92% consistently — indicating stable service delivery performance.

**Insight 2 — Change Success Rate:**
> Change success rate maintained at 99-100% across all months — reflecting strong change management processes.

**Insight 3 — CSAT Performance:**
> 87.39% of incidents received "Great" CSAT rating with only 4.15% receiving "Poor" — indicating high customer satisfaction.

**Insight 4 — SCTask CSAT:**
> SCTask CSAT showed 83.24% "Great" ratings — slightly lower than incidents, highlighting an opportunity to improve service catalogue delivery.

**Insight 5 — Aging Analysis:**
> 67% of incidents resolved within 3 days, 22% within 7 days, with only 11% exceeding 7-day resolution — flagged for process improvement.

**Insight 6 — ITask Performance:**
> ITask SLA compliance consistently above 99% across all priorities and weeks — demonstrating excellent task management.

---

## Business Value
- Eliminated manual SLA reporting — saving hours of weekly effort
- Enabled real-time visibility into IT service delivery performance
- Supported data-driven decisions for IT service improvement
- Provided management with instant access to CSAT trends and SLA compliance
- Automated end-to-end data pipeline reducing manual intervention to zero

---

## Future Enhancements
- Add predictive SLA breach alerts
- Include FCR (First Call Resolution) and Problem Management tabs
- Add drill-through to individual ticket level analysis
- Build mobile-optimised view for on-the-go monitoring

---

## Files in this Repository

| File | Description |
|---|---|
| screenshot|
| README.md | Project documentation and insights |

---

## Author
**Neesha Pramod**
[LinkedIn](https://linkedin.com/in/neesha-p-231746244/) | [GitHub](https://github.com/Neesha29295/my_projects)

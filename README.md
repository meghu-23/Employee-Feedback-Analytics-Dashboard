# 📊 Employee Feedback Analytics Dashboard

## 🔍 Project Overview
A live end-to-end HR analytics solution that collects, processes and visualizes employee feedback data in real time using completely free tools. The dashboard enables HR teams and leadership to monitor employee satisfaction, work preferences and manager effectiveness instantly.

## 🛠️ Tools Used
| Tool | Purpose |
|------|---------|
| Google Forms | Live feedback data collection |
| Google Sheets | Automatic data storage |
| Power BI Desktop | Interactive dashboard |

## 📐 Architecture
Employee fills Google Form → Response stored in Google Sheets → Sheet published as CSV endpoint → Power BI connects via Web CSV → Dashboard updates on refresh

## 📊 Dashboard Visuals
| Visual | Chart Type | Insight |
|--------|-----------|---------|
| Total Responses | KPI Card | Live response count (42) |
| Satisfaction by Department | Clustered Bar Chart | Avg satisfaction per dept broken down by job role |
| Work Mode Analysis | Pie Chart | WFH vs Hybrid vs Office distribution |
| Company Rating | Gauge Chart | Overall avg rating (3.86/5) |
| Recommendation Rating | Donut Chart | Employee NPS breakdown |
| Manager Support by Job Role | Column Chart | Support levels across job levels |

## 🎛️ Interactive Filters
- Department filter
- Job Role filter
- Years of Experience filter
- Date range filter (Timestamp)

## 💡 Key Insights
- Overall company rating: 3.86/5
- 33% of employees Definitely recommend the company
- Managers receive highest support score (4.89/5)
- Interns receive lowest support score (2.57/5)
- Sales department shows highest work satisfaction
- Finance department needs immediate attention
- Work mode split: 35% WFO | 33% WFH | 31% Hybrid

## 🚀 How to Use
1. Open Google Form link to submit feedback
2. Data automatically flows into Google Sheets
3. Open Power BI Desktop file
4. Click Refresh to pull latest responses
5. Use slicers to filter by Department, Job Role, Experience or Date

## 🔗 Live Form Link
[Click here to submit employee feedback](YOUR_GOOGLE_FORM_LINK_HERE)

## 📸 Dashboard Preview
![Dashboard](screenshot.png)

## 🔮 Future Scope
- Deploy on Power BI Service for auto refresh
- Connect to SQL database for enterprise scale
- Build mobile app for managers
- Add predictive attrition analytics using Python
- Integrate with HR systems like Workday or SAP

## 🧰 Technical Highlights
- Zero infrastructure cost — built entirely on free tools
- Scalable to 10 million+ responses via Google Sheets
- Real time refresh with single click
- Interactive cross filtering across all visuals
- Responsive layout with 4 dynamic slicers

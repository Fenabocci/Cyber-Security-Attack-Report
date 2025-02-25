# Cybersecurity Attack Analysis (2020-2023)  

**Tool**: Microsoft Power BI  


## Overview  
This Power BI project analyzes cybersecurity attack trends from 2020 to 2023, focusing on:  
- Yearly attack volumes and severity levels.  
- Protocol distribution (TCP, ICMP, UDP).  
- Operating System (OS) vulnerabilities.  
- Attack sources (Firewall, Servers, Mozilla, Opera).  
- Monthly attack patterns.  



## Features  
- **Interactive Dashboards**: Filter by year, severity, and OS.  
- **Key Visualizations**:  
  - Line charts for yearly trends.  
  - Pie/bar charts for protocol and OS analysis.  
  - Heatmaps for monthly patterns.  
- **Drill-Down Capability**: Explore granular details (e.g., OS-specific attacks).  


## Installation  
1. **Prerequisites**:  
   - Microsoft Power BI Desktop (free download [here](https://powerbi.microsoft.com/desktop/)).  
2. **Open Project**:  
   - Open it to view dashboards ([Cybersecurity_Analysis]([Cybersecurity_Analysis.pbix](https://app.powerbi.com/view?r=eyJrIjoiZTk3ODZmZTYtZDc1Yy00OTI4LWI1YjYtMGEwNWI1OGI2OTRhIiwidCI6IjYwOGNmNDk1LTMwNmItNDJiYS1iMmNhLTJkZTBlYjIwOWQ4YSIsImMiOjl9))).  
     


## Data Sources  
### Raw Data  
- **Years**: 2020–2023.  
- **Metrics**:  
  - Total attacks (e.g., 10,573 in 2020).  
  - Severity levels (Low/Medium/High).  
  - Protocol usage (TCP, ICMP, UDP).  
  - OS attack counts (Windows, Linux, mobile devices).  
  - Attack sources (Firewall, Servers, Mozilla, Opera).  

### Adjustments  
- Standardized labels (e.g., "KMP" → "ICMP").  
- Partial 2023 monthly data (Jan–Oct).  


## Key Visualizations  
| Visualization          | Insights                                                                 |  
|------------------------|--------------------------------------------------------------------------|  
| **Yearly Trends**       | Attacks decreased by 20% from 2020 to 2023.                              |  
| **Protocol Analysis**   | ICMP attacks dominate (~34-35% across years).                            |  
| **OS Vulnerabilities**  | Windows is the most targeted OS (4,649 attacks in 2020).                 |  
| **Attack Sources**      | Mozilla-based attacks are highest (8,619 in 2022).                       |  
| **Monthly Heatmap**     | Peaks in Q1 (Jan–Mar) across all years.                                  |  


## Insights & Recommendations  
### Findings  
- **ICMP Risks**: Increased by 0.71% (2020–2023).  
- **Windows Vulnerabilities**: 32% of all OS attacks.  
- **Mozilla Threats**: 2.16% rise in attacks (2020–2022).  

### Actions  
1. Patch ICMP protocol vulnerabilities.  
2. Strengthen Windows OS security.  
3. Audit Mozilla integrations for loopholes.  


## Challenges & Solutions  
| Challenge               | Solution                                  |  
|-------------------------|-------------------------------------------|  
| Inconsistent labels     | Standardized terms (e.g., "Protoed" → "Protocol"). |  
| Missing severity data   | Used year-over-year averages to infer gaps. |  


## Future Enhancements  
- Integrate real-time threat data feeds.  
- Expand OS and protocol coverage.  
- Add geolocation analysis (data permitting).  


  
**Note**: For DAX formulas or visualization help, reach out! 😊  



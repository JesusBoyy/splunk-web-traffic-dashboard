splunk-web-traffic-dashboard
Splunk Enterprise Web Traffic Monitoring Dashboard, Alert and Reports
Splunk Web Traffic Monitoring Project

This project demonstrates practical use of **Splunk Enterprise** for monitoring and analyzing web traffic data using the official Splunk tutorial dataset.

Project Overview

I built a complete monitoring solution that includes:

- A professional dashboard for visualizing web traffic
- An alert for detecting high error rates
- Multiple saved reports for deeper analysis

Features

1. Web Traffic Overview Dashboard
A multi-panel dashboard that shows:
- Traffic volume over time
- Distribution of HTTP status codes
- Top client IP addresses
- Most requested pages

2. High Error Rate Alert
An alert that triggers when the number of 4xx/5xx errors exceeds a defined threshold. This helps in quickly detecting potential issues on a web server.

3. Saved Reports
- Top User Agents
- Failed Requests Detail
- Traffic by Hour

Tools & Technologies
- Splunk Enterprise
- Splunk Search Processing Language (SPL)
- Official Splunk Tutorial Dataset

Screenshots

Dashboard
![Web Traffic Overview Dashboard](screenshots/dashboard.png)

Alert
![High Error Rate Alert](screenshots/alert.png)

Reports
![Top User Agents Report](screenshots/report-useragents.png)
![Failed Requests Report](screenshots/report-failed.png)
![Traffic by Hour Report](screenshots/report-hourly.png)

Key Skills Demonstrated
- Data onboarding in Splunk
- Creating dashboards and visualizations
- Building alerts
- Writing efficient SPL searches
- Creating and organizing reports

How to Use
1. Install Splunk Enterprise
2. Upload the `tutorialdata.zip` dataset
3. Import the dashboard XML (if provided)
4. The searches and reports can be recreated using the SPL queries shown in the project


Author: AJAYI AYOMIDE EMMANUEL
Project Type: Splunk Portfolio Project
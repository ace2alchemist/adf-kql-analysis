# KQL Query to find API Call Failures via Web Activity or REST/HTTP Dataset inside Copy Activity

This KQL-based code accelerator is designed to monitor and analyze failures in Azure Data Factory (ADF) activities over a specified time range. By leveraging historical data, it helps in identifying abnormal failure patterns and provides alerts when the failure rate exceeds a predefined threshold. The solution enables proactive monitoring and data-driven decision-making for optimizing ADF performance and reducing disruptions in data pipelines. 

The provided Kusto Query Language (KQL) script is designed to monitor Azure Data Factory (ADF) failed activities specifically any API calls from the ADF via Web Activity or a Copy Activity using a REST/HTTP dataset by comparing failure trends between a baseline period (historical data) and a current period (recent data). It identifies anomalies where the failure rate has significantly increased and generates an alert if necessary.

Organizations using Azure Data Factory often encounter failed activities within their data pipelines. Without an automated approach to detect trends and anomalies, troubleshooting failures can be reactive, time-consuming, and costly. This accelerator provides a systematic way to:

Track failure trends over a baseline period and compare them with the current period.

Identify significant deviations in failure rates and flag potential issues.

Generate alerts when failure counts exceed a predefined threshold, enabling quick intervention.


Use Cases:

1. Proactive Monitoring: Identifies increasing failure trends before they become critical.

2. Anomaly Detection: Highlights activities with an abnormal rise in failures.

3. Operational Efficiency: Reduces time spent manually reviewing failed activity logs.

4. Data Pipeline Health Tracking: Provides insights into the reliability of ADF pipelines.

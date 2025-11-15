# Netskope-Advanced-Analytics-Templates
Importable templates for [Netskope Advanced Analytics](https://www.netskope.com/products/advanced-analytics).

| Template | Description | Files
|----------|----------|----------|
|**User Activity Comparison**<br/><a href="https://github.com/user-attachments/assets/b660b464-ca60-4ff4-89e3-8a2940e85980" />Screenshot</a>|Compare specific user Secure Web Gateway activity to either a security group (e.g., peers) or the organization.<br><br>Utilizes Transaction Events for data.|[Download](./User%20Activity%20Comparison%20Report.json)|
| **Netskope Data Center Usage**<br/><a href="https://github.com/user-attachments/assets/09376ccf-8062-4ba5-8315-745df3fd514f" />Screenshot</a> | Individual Netskope Data Center utilization statistics for Secure Web Gateway and Private Access traffic. <br><br>Utilizes Transaction Events and Network Events for data. | [Download](./Netskope%20Data%20Center%20Usage.json)|
| **User Search Engine Queries** | User search queries sent to most websites in the Search Engine category, with separate result tables for Google, Bing, Ask.com, Yahoo Search, Yandex, and DuckDuckGo.|[Download](./User%20Search%20Engine%20Queries.json)|
## Prerequisites
- Netskope Advanced Analytics
- Netskope [data retention duration/licensing](https://docs.netskope.com/en/data-retention) for desired reporting timeframe.

## Usage
1. Login to your Netskope Administrator Portal.
2. Open **Advanced Analytics**.
3. In the left navigation, select **Personal** if the report is just for you, or **Group** if you want to share it with other administrators.
4. Select **IMPORT FROM FILE** in the top right and upload the downloaded template.
5. After the import completes, select the new report that appears in the list.

## License
Licensed under MIT — free to use, modify, and share, with no warranty.

## Disclaimer
This project is **not affiliated with or supported by Netskope**. It may be incomplete, outdated, or inaccurate. Use at your own risk. 

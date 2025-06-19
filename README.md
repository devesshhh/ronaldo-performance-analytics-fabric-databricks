# Ronaldo Performance Analytics (Fabric + Databricks)

🎯 A mini-project analyzing Cristiano Ronaldo’s football career using Microsoft Fabric, Databricks, and Power BI.

## 🔧 Tech Stack
- Databricks (PySpark)
- Microsoft Fabric (Lakehouse, Dataflow Gen2, Pipeline)
- Power BI (Service + Report PDF)

## 📊 What I Did
- Cleaned and analyzed football data from Kaggle (appearances, games, players)
- Filtered Ronaldo's data using player ID `8198`
- Created custom PySpark notebooks with joins, aggregations, and visuals
- Exported analysis into 5 CSV tables for BI reporting
- Created 3-page Power BI report showing:
  - Goals by year
  - Cards per year
  - Match breakdown
  - Career summary (cards)
- Designed & ran a 4-stage Microsoft Fabric pipeline with Gmail notification
- Used Dataflow Gen2 to simulate transformations in Fabric

## 📁 Project Structure
- `notebooks/`: PySpark notebooks used in Fabric
- `screenshots/`: Proof of pipeline run success
- `exported_data/`: 5 clean Delta tables exported as CSV
- `powerbi_report/`: Final report PDF (for resume/github)

## 📷 Sample Output

### 🟢 Power BI Report Overview
![Power BI Report](screenshots/ronaldo_report_screenshot.png)

### 🛠️ Fabric Pipeline - Stage 4 Success
![Pipeline Stage 4](screenshots/pipeline_stage4_run.png)

### 📬 Gmail Notification Triggered
![Gmail Screenshot](screenshots/gmail_notification_success.png)

<p float="left">
  <img src="screenshots/pipeline_stage4_run.png" width="350"/>
  <img src="screenshots/gmail_notification_success.png" width="350"/>
</p>


⚠️ Note: The `.pbix` file is included for transparency and learning purposes. Please do not reuse or republish without permission.

## 📬 Contact
Feel free to reach out for collaboration or feedback: `deveshrai162@gmail.com`

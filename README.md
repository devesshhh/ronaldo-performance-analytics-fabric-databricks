# Ronaldo Performance Analytics (Fabric + Databricks)

🎯 A mini-project analyzing Cristiano Ronaldo’s football career using Microsoft Fabric, Databricks, and Power BI.

## 🔧 Tech Stack
- Databricks (PySpark)
- Microsoft Fabric (Lakehouse, Dataflow Gen2, Pipeline, Notebook)
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

## 📸 Project Snapshots

### ✅ Fabric Pipeline Stage 2  
![Stage 2](https://github.com/devesshhh/ronaldo-performance-analytics-fabric-databricks/blob/main/ronaldo-performance-analytics-fabric-databricks/Screenshots/pipeline_stage2_run.jpg)

### ✅ Fabric Pipeline Stage 3  
![Stage 3](https://githubusercontent.com/devesshhh/ronaldo-performance-analytics-fabric-databricks/blob/main/ronaldo-performance-analytics-fabric-databricks/Screenshots/pipeline_stage3_run.jpg)

### ✅ Fabric Pipeline Stage 4  
![Stage 4](https://githubusercontent.com/devesshhh/ronaldo-performance-analytics-fabric-databricks/blob/main/ronaldo-performance-analytics-fabric-databricks/Screenshots/pipeline_stage4_run.jpg)

### 📉 Fabric Pipeline Below Stage 2  
![Below Stage 2](https://githubusercontent.com/devesshhh/ronaldo-performance-analytics-fabric-databricks/blob/main/ronaldo-performance-analytics-fabric-databricks/Screenshots/pipeline_below_stage2_run.jpg)

### 📬 Gmail Notification  
![Gmail](https://githubusercontent.com/devesshhh/ronaldo-performance-analytics-fabric-databricks/blob/main/ronaldo-performance-analytics-fabric-databricks/Screenshots/gmail_notification_success.jpg)

### 📊 Power BI Report Preview  
![Power BI](https://githubusercontent.com/devesshhh/ronaldo-performance-analytics-fabric-databricks/blob/main/ronaldo-performance-analytics-fabric-databricks/Screenshots/ronaldo_report_preview.png)

⚠️ Note: The `.pbix` file is included for transparency and learning purposes. Please do not reuse or republish without permission.

## 📬 Contact
Feel free to reach out for collaboration or feedback: `deveshrai162@gmail.com`

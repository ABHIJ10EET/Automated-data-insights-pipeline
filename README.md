# AI-Powered Automated Supply chain analytics

 End-to-end data analysis solution using **n8n**, **Supabase**, and **Quadratic AI**. This project automates data collection, processing, storage, and analysis to generate real-time business insights 

##  Tech Stack
- [n8n](https://n8n.io) – Workflow automation
- [Supabase](https://supabase.com) – Realtime PostgreSQL database
- [Quadratic](https://www.quadratic.to) – AI spreadsheet & data analysis
- SQL, REST APIs

 Live Project Links

| Tool        | Access Link |
|-------------|-------------|
| 🔁 n8n Workflow | [Open n8n Workflow](https://abhi00314.app.n8n.cloud/workflow/6EIxFBVEL8AdJsZe) |
| 🗄️ Supabase Dashboard | [Open Supabase Project](https://supabase.com/dashboard/project/tmfimjfwchetiiwnmkog/editor/17268?sort=order_placement_date:desc&showConnect=true) |
| 📈 Quadratic Spreadsheet | [Open Quadratic Analysis](https://app.quadratichq.com/file/f71d268c-7d93-4ccc-b8a6-a2f5d1bc0baa?sheet=d4026455-cda3-4b00-9009-65f6672508f5) |

  
## Project Highlights

✅ **Fully automated ETL workflow** (Extract-Transform-Load)  
✅ **Real-time exchange rate conversion** using [Open Exchange Rates API](https://openexchangerates.org)  
✅ **Secure PostgreSQL storage** with Supabase  
✅ **Interactive AI spreadsheet** with Quadratic  

##  Workflow Overview

![n8n Workflow]
![image alt](https://github.com/ABHIJ10EET/Automated-data-insights-pipeline/blob/main/Screenshot%202025-06-04%20234736.png?raw=true)



##  Workflow Architecture

###  Tools in Action:

1. ** Gmail Trigger** (n8n)  
   Triggers the workflow when an email with a CSV file arrives.

2. ** CSV Parsing**  
   Extracts and splits CSV data into structured records.

3. ** Currency Conversion**  
   Uses Open Exchange Rates API to convert USD to INR dynamically.

4. ** Data Storage**  
   Inserts the enriched data into a PostgreSQL table via Supabase.

5. ** AI Analysis in Quadratic**  [Quadratic](https://app.quadratichq.com/file/f71d268c-7d93-4ccc-b8a6-a2f5d1bc0baa?sheet=d4026455-cda3-4b00-9009-65f6672508f5)
   - Imports the Supabase data into a smart spreadsheet  
   - Uses AI formulas to summarize, visualize, and interpret results


# Logistics Dashboard

## 📖 Overview
The **Logistics Dashboard** is a real-world data project built to address a company's need for general metrics such as order volume, pallet utilization, inbound performance, and API bandwidth usage.  

On the technical side, this project required significant data cleaning, dealing with incomplete/multi-source datasets, merging data, gathering information from APIs, and implementing incremental calls for automation. It also included building new metrics with integrity, sometimes deploying small apps to support reporting.

---

## 🚚 Inbound Shipments (Example Tab)

![Inbound Shipments Screenshot](Dashboard%20Screenshots/ReadmeGIF.gif)

---

## 💡 Business Value
This dashboard provided **tangible impact** to logistics operations:

- 📦 **SLA Control** → Identified containers out of SLA, enabling root-cause analysis and achieving revenue.  
- ⚡ **Operational Efficiency** → Reduced inbound processing times, increasing container throughput.  
- 🗂️ **Pallet Utilization Trends** → Anticipated customer volume changes for proactive adjustments.  
- 📊 **Order & Inbound Forecasting** → Visualized activity by weekday to improve staffing and resource allocation.  
- 🗺️ **Geographic Insights** → Displayed order distribution by state to optimize carrier selection and route planning.  

---

## 🛠️ Tech Stack

<p align="center">
  <img src="https://cdn.jsdelivr.net/gh/simple-icons/simple-icons/icons/powerbi.svg" width="40" title="Power BI"/>
  <img src="https://cdn.jsdelivr.net/gh/simple-icons/simple-icons/icons/microsoftexcel.svg" width="40" title="Excel"/>
  <img src="https://cdn.jsdelivr.net/gh/simple-icons/simple-icons/icons/microsoftsharepoint.svg" width="40" title="SharePoint"/>
  <img src="https://cdn.jsdelivr.net/gh/simple-icons/simple-icons/icons/powerapps.svg" width="40" title="Power Apps"/>
  <img src="https://cdn.jsdelivr.net/gh/simple-icons/simple-icons/icons/powerautomate.svg" width="40" title="Power Automate"/>
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg" width="40" title="Python"/>
</p>

---

## 📑 Tabs Documented

| Tab | Screenshot | Documentation |
|-----|------------|---------------|
| Geographic Distribution of Orders | <img src="Dashboard%20Screenshots/Map%20Orders%20Tab%20Screenshot.png" width="200"/> | [View Doc](Dashboard%20Tabs/Geographic%20Distribution%20of%20Orders%20Tab.md) |
| Inbound Shipments | <img src="Dashboard%20Screenshots/Inbound%20Shipments%20Tab%20Screenshot.png" width="200"/> | [View Doc](Dashboard%20Tabs/Inbound%20Shipments%20Tab.md) |
| Shipped Orders Processed | <img src="Dashboard%20Screenshots/Orders%20Shipped%20Tab%20Screenshot.png" width="200"/> | [View Doc](Dashboard%20Tabs/Shipped%20Orders%20Processed%20Tab.md) |
| Pallet Usage | <img src="Dashboard%20Screenshots/Pallet%20Usage%20Tab%20Screenshot.png" width="200"/> | [View Doc](Dashboard%20Tabs/Pallet%20Usage%20Tab.md) |
| Business KPIs | <img src="Dashboard%20Screenshots/Business%20KPIs%20Tab%20Screenshot.png" width="200"/> | [View Doc](Dashboard%20Tabs/Business%20KPIs.md) |
| API Bandwidth Consumption | <img src="Dashboard%20Screenshots/API%20Bandwidth%20Tab%20Screenshot.png" width="200"/> | [View Doc](Dashboard%20Tabs/API%20Bandwidth%20Consumption%20Tab.md) |

---

## ⚙️ How to Use
1. Download the PBIX file in Power BI Desktop (pbix/Logistics Dashboard.pbix)
2. Open the PBIX file in Power BI Desktop:
3. Load dummy data located in (Dummy Data/)
4. Create your own data source with the dummy data you downloaded 
5. It should be fine, you can now see the dashboard or USE the dashboard template to make it better 

## 📂 Folder Structure

```text
Logistics-Dashboard/
├─ README.md                   # Main documentation
├─ pbix/                       # Power BI file
│  └─ Logistics Dashboard.pbix
├─ Dashboard Screenshots/      # Screenshots for each tab
│  ├─ API Bandwidth Tab Screenshot.png
│  ├─ Business KPIs Tab Screenshot.png
│  ├─ Inbound Shipments Tab Screenshot.png
│  ├─ Map Orders Tab Screenshot.png
│  ├─ Orders Shipped Tab Screenshot.png
│  └─ Pallet Usage Tab Screenshot.png
├─ Dashboard Tabs/             # Detailed docs for each tab
│  ├─ API Bandwidth Consumption Tab.md
│  ├─ Business KPIs.md
│  ├─ Geographic Distribution of Orders Tab.md
│  ├─ Inbound Shipments Tab.md
│  ├─ Pallet Usage Tab.md
│  └─ Shipped Orders Processed Tab.md
└─ Dummy Data/                 # Sample dataset
   ├─ BandwidthData.xlsx
   ├─ Customers.xlsx
   ├─ InboundData.xlsx
   ├─ OrdersData.xlsx
   └─ PalletUsage.xlsx
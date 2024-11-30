# **Behind the Shots: Exploring Vaccine Adverse Events with Data**

Ever wonder what vaccine adverse event data can tell us about safety trends and outcomes? Using the CDC WONDER database, I built a Power BI dashboard to break down years of vaccine-related reports into clear, actionable insights.  

This README takes you behind the scenes to show how it all came together—from raw data to polished visuals—and what the numbers are saying.  


## **Vaccine Adverse Events Power BI Dashboard**
![](https://github.com/guilzee/PowerBIMagic/blob/main/VaccineAdverseEvents/images.videos/VAERSdashboard.png)

## **The Big Picture**

The goal of this project was simple: **make sense of vaccine adverse event data from 2019 to 2024**. I wanted to uncover patterns across:  
- **Demographics**: Age and gender.  
- **Manufacturers**: Which companies had the most reports.  
- **Event Categories**: Hospitalizations, deaths, emergency visits, etc.  

### **Highlights of the Dashboard**  
1. **Top states** with the highest number of adverse events.  
2. **Manufacturers** with the most reported events.  
3. **Year-over-year trends** across event categories.  

These insights can help public health experts and vaccine makers improve safety and communication efforts.  


## **How I Made It Happen**

### 1. **Starting with the Data**  
I pulled data from the **CDC WONDER database**, which is an incredible (and free!) resource for public health info. Here’s what I did:  
- Filtered the dataset by gender:  
  - One for **male reports**.  
  - Another for **female reports**.  
- Downloaded each dataset as a text file.

### 2. **Prepping the Data**  
Next, I turned to Excel’s **Power Query** tool to clean and combine the data:  
- Imported the male and female datasets into separate tables.  
- Added a column to label gender in each table.  
- Created a static column for the country (all reports are from the U.S.).  
- Appended the male and female datasets into a single table.  
- Saved the final dataset as an [Excel file](https://github.com/guilzee/PowerBIMagic/blob/main/VaccineAdverseEvents/VAERS%20Data.xlsx) for use in Power BI.  

### 3. **Building the Dashboard**  
With the data ready, I used Power BI to create the visuals:  
- **Map Visualization**: Highlighted the top 10 states with the highest adverse event counts.  
- **Bar and Column Charts**:  
  - Event counts by year (2019–2024).  
  - Event counts by manufacturer.  
- **Data Table**: A detailed breakdown of event categories and their counts.  

The dashboard is fully **interactive**—users can filter by demographics, years, and event types to explore the data from multiple angles.  


## **What the Numbers Are Saying**

1. **Emergency Care Dominates**  
Most reports (513!) were about **emergency room or office visits**. These events were urgent but not always life-threatening, making this category the largest.  

2. **Merck & Co., Inc. Leads the Manufacturer List**  
With **157 adverse events reported**, Merck had the highest count. This might reflect their vaccine usage volume rather than higher risk.  

3. **2019 Stands Out**  
Over half (**52.57%**) of all reports came from **2019**. This could indicate a major vaccination campaign or changes in reporting practices.  

4. **California Leads the States**  
Among the top 10 states, **California** had the highest number of adverse events (**37**), followed by **Florida (33)** and **Ohio (30)**.  


## **Why This Matters**

Projects like this are about more than just numbers—they’re about making smarter, data-driven decisions.  

### Public health experts can use this dashboard to:  
- **Investigate trends** in high-reporting states.  
- **Analyze manufacturers** with higher report counts.  
- **Reassure the public** by showing that most events are non-severe.  


## **The Takeaway**

This project turns complex vaccine data into clear, actionable insights. Whether you’re tracking trends, identifying areas for improvement, or communicating findings to stakeholders, this dashboard bridges the gap between raw data and meaningful stories.  

Let me know what you think—or let’s chat if you’re interested in collaborating! 🚀  

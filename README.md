🎯 Purpose
"To visualize and analyze Azure cloud spending by service, region, and project scope using exported cost data."


⚙️ Tools Used
- Azure Portal: Cost Management + Billing
- Excel (with PivotTables and Charts)
- Azure Exports via Blob Storage

🔄 Workflow
- Accessed Azure Cost Management
→ Explored cost trends in the portal with daily breakdowns and grouping filters
- Created a Detailed Cost Export
→ Set up a one-time .csv export with service, location, and resource group-level detail
- Opened and Transformed the CSV in Excel
→ Cleaned the data and inserted a PivotTable for visual slicing
- Analyzed Costs by Multiple Dimensions
→ Grouped spend by:
- meterCategory (e.g. Storage, Compute, CDN)
- resourceLocation (e.g. eastus, global)
- resourceGroupName (project-specific cost tracking)
- Designed an Interactive Dashboard
→ Added stacked bar charts, filters, and clean formatting for insight-ready visuals

💡 What It Shows
- Which services are costing the most
- Where (regionally) costs are occurring
- Which projects/resource groups are burning cloud spend
- Day-by-day cloud usage patterns with actual costs

🚀 Bonus Statement (If You’re Pitching This)
“This dashboard gives stakeholders quick, data-driven visibility into our Azure usage and spending behavior. It’s scalable, shareable, and lays the foundation for automated reporting or Power BI integration.”

Example:
![image](https://github.com/user-attachments/assets/4f9c79e5-7e60-4e86-b64c-bb90f19f4fb7)


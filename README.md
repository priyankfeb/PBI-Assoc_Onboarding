# PBI-Assoc_Onboarding
# 🏘️ Association Onboarding Tracker - Power BI Report

## 📌 Overview

This Power BI report tracks the **onboarding process of associations** into the system, comprising a series of crucial steps like data imports, calendar setups, folder creation, configuration, and documentation uploads.

Each onboarding step is meticulously monitored using:

- **Start Date and Due Date**
- **Current Status**: `On-Time`, `Pending`, or `Overdue`
- **Visual Timeline**: A graphical progress indicator
- **Days On-Time Calculation**: Showing how early or late a step is

The report provides a **clear and dynamic view** of progress, bottlenecks, and overdue tasks—helping stakeholders drive timely completion of the onboarding pipeline.

🔗 **Live Report Link**: [View Report on Power BI Service](https://app.powerbi.com/view?r=eyJrIjoiYjA2ZjI1ZjctZjg3Ni00MzZkLWIzNzgtMWVkZGI2YzgwYTRkIiwidCI6IjdiOGQ3YzQzLTZjMzAtNDJkOS04YzI2LTg4NWIxZWRmZDdkZSJ9)

---


### Key Technical Highlights:

- 🎨 **SVG Visuals & Custom Design**:  
  Utilized Figma to create visual timeline indicators and converted them into SVG for Power BI rendering.

- 🧮 **DAX-Driven Custom Visuals**:  
  The `Timeline` and `Days On-Time` columns are built entirely using **DAX and SVG**, allowing for precise dynamic formatting and color changes based on status.

- 🔄 **Dynamic Measure Formatting**:  
  The `Days On-Time` measure intelligently displays **"X Days Early"** or **"X Days Late"**, with colors (red/blue) based on the result.

- ⚙️ **Enhanced UX**:  
  The layout is designed to keep onboarding progress at a glance, with filters by association and visually intuitive step indicators.

---

## 📷 Screenshot Preview

![Association Onboarding Tracker Screenshot](https://github.com/priyankfeb/PBI-Assoc_Onboarding/blob/e8ba944ec4f8899433fc0dac355f7ff7dc0baf1c/image.jpg)

---

## 🔧 Tools & Tech Stack

- **Power BI Desktop & Service**
- **DAX (Data Analysis Expressions)**
- **SVG for Custom Visuals**
- **Figma for UI Design Elements**
- **Power BI Service (for publishing)**

---

## 💬 Conclusion

This project helped me push the boundaries of native Power BI visuals using DAX and SVG. It reinforced the power of **custom visuals** and **data storytelling** in business-critical dashboards. 

Looking forward to applying these learnings in more advanced and scalable reporting solutions!

---

📩 Feel free to connect or drop feedback. Always happy to learn and collaborate!


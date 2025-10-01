# Power-BI-Credit-and-Vendor-Invoice-Management-App  

[View on Microsoft AppSource](https://appsource.microsoft.com/en-us/product/power-bi/dhyeyconsultingservicespvtltd1584430919382.credit-and-vendor-invoice-management?tab=Overview)  

[![Watch the Demo](https://img.youtube.com/vi/8jh7EHEbN8c/0.jpg)](https://youtu.be/8jh7EHEbN8c?si=VYP1PaS0kfkiAMqu)  

---

## Overview  

Efficient credit management is essential for maintaining healthy cash flow and vendor relationships. This Power BI dashboard offers a centralized view of outstanding balances, invoice statuses, and payment risks, allowing finance and procurement teams to take timely, informed action.  

By consolidating vendor and customer credit activity, the dashboard enhances visibility into unpaid invoices, overdue payments, and remaining balances—empowering teams to follow up, prioritize collections, and mitigate financial risk.  

---

## Technical Framework  

The dashboard is built on a structured dataset of invoices and payments linked to vendors and customers.  

**Key components:**  
- **Data Source:** Excel/ERP export with invoice records, payment statuses, due dates, and transaction amounts  
- **Data Preparation:** Cleaned and merged using Power Query for consistent formatting, date calculations, and status tagging  
- **Data Model Dimensions:**  
  - Vendor & Customer  
  - Invoice Amount & Paid Amount  
  - Due Date & Due Status  
  - Payment Status (Can be Paid / Cannot be Paid)  
  - Remaining Balance  

---

## Interactive Filters  

The dashboard includes filters to support real-time financial insights and segmentation:  
- **Due Date Status:** Identify which invoices are past due, on time, or upcoming  
- **Vendor:** Focus on specific supplier relationships to assess payment behavior  
- **Customer:** Drill into customer-wise receivables and risks  
- **Vendor Payment Status:** Highlight vendors with blocked payments or pending approvals  

These filters allow financial controllers to quickly isolate problematic accounts and ensure timely follow-up.  

---

## Dashboard Highlights  

**Bar Chart – Remaining Balance by Vendor**  
Ranks vendors by the value of outstanding payments, providing a clear picture of payment exposure by supplier.  

**Bar Chart – Remaining Balance by Customer**  
Highlights customers with the largest unpaid balances—useful for collections and account prioritization.  

**Invoice Table – Status Overview**  
Lists each invoice with:  
- Vendor Name  
- Invoice Amount  
- Payment Status  
- Due Date Condition (Past Due / To Be Paid / Paid On Time)  
- Color-coded icons for fast interpretation  

**Customer Order Table – Payment Breakdown**  
Displays individual orders with:  
- Amount Paid  
- Remaining Balance  
- Total Order Value  
- Year of Transaction  

Supports a granular view of customer payment history and credit standing.  

This dashboard transforms invoice records into a powerful credit monitoring tool—enabling faster collections, reduced payment delays, and smarter financial planning.  

---

## Screenshots  

### Dashboard Overview 
![Dashboard Overview](https://github.com/SuperfiedStudd/Power-BI-Credit-and-Vendor-Invoice-Management-App/blob/main/docs/dashboard_overview.png?raw=true)  

### Invoice Report
![Invoice Report](https://github.com/SuperfiedStudd/Power-BI-Credit-and-Vendor-Invoice-Management-App/blob/main/docs/invoicereport.png?raw=true)  

### Credit Table  
![Invoice Table](https://github.com/SuperfiedStudd/Power-BI-Credit-and-Vendor-Invoice-Management-App/blob/main/docs/credit.png?raw=true)  

### Vendor Balance  
![Customer Orders](https://github.com/SuperfiedStudd/Power-BI-Credit-and-Vendor-Invoice-Management-App/blob/main/docs/balance.png?raw=true)  

### Customer Balance 
![Credit Risk](https://github.com/SuperfiedStudd/Power-BI-Credit-and-Vendor-Invoice-Management-App/blob/main/docs/balance2.png?raw=true)  

---

## How to Use  

This repository is intended as a showcase:  
1. Watch the demo video above for a walkthrough.  
2. Explore the screenshots for dashboard views.  
3. Try the published app directly on [Microsoft AppSource](https://appsource.microsoft.com/en-us/product/power-bi/dhyeyconsultingservicespvtltd1584430919382.credit-and-vendor-invoice-management?tab=Overview).  
   - You can download and play around with the app if you have a school or work account that supports Microsoft apps.  

---

## Why It Matters  

Late or unmanaged payments can strain both supplier relationships and working capital. This dashboard enables proactive credit and invoice management—reducing payment risk, improving vendor trust, and optimizing cash flow.  

---

## Author  

Developed by **Jasjyot Singh**  
Contact: jasjyotsingh.work@gmail.com  

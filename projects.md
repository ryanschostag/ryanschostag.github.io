---
layout: default
title: Case Studies
---
[Home](./) | [About](about.md) | [Case Studies](projects.md)

# Case Studies & Examples

Below are examples of the types of automation and data engineering outcomes I deliver.

---

## 🔧 Excel Reporting → Automated Pipeline
**Before:**  
Team spent 8–12 hours weekly merging CSVs and updating spreadsheets manually.

**After:**  
Python + SQL pipeline refreshes data daily and updates dashboards automatically.  
**Result:** Saved 30–50 hours per month.

---

## 🔧 Broken SQL Pipeline → Clean, Scalable ETL
**Before:**  
Frequent failures, inconsistent tables, unreliable analytics.

**After:**  
Rebuilt ETL in Azure + Databricks, added monitoring and alerting.  
**Result:** 99% pipeline reliability and faster insights.

---

## 🔧 Cloud Cost Optimization
**Before:**  
Azure workloads running inefficiently and overspending.

**After:**  
Optimized clusters, queries, and storage layers.  
**Result:** 20–40% savings.

---

## 🔧 Internal API for Operations
**Before:**  
Employees manually downloaded and cleaned data from multiple third-party systems.

**After:**  
FastAPI service fetches, merges, and cleans data automatically.  
**Result:** Eliminated 100+ manual tasks each month.

---

## 🔧 FastAPI Microservice for Automated Data Integration

**Before:**  
A client relied on manually downloading CSV exports from three different SaaS platforms (CRM, billing, and support tools). Staff spent 1–2 hours daily downloading files, normalizing columns, merging datasets, and emailing spreadsheets to leadership teams. This created delays, inconsistent data, and human error.

**Challenges:**
- Data arrived in different formats  
- Manual workflows caused reporting delays  
- No centralized API to fetch, clean, or validate data  
- No automated delivery mechanism for stakeholders  

---

**After:**  
I built a production-ready FastAPI microservice that automated all data retrieval, cleaning, merging, and publishing steps.

### Key Features Delivered
- **Automated API ingestion** from all third-party systems  
- **Data normalization** filters and schema mapping  
- **Automated cleaning & validation** using Pydantic models  
- **Integrated SQL write-back** for analytics & BI dashboards  
- **Scheduled batch processing** via background tasks  
- **Authentication and role-based access controls**  
- **Logging + monitoring** delivered through structured logs  

---

### Result
- Eliminated **100+ manual tasks per month**  
- Reduced delivery time from **hours to seconds**  
- Provided a **single, stable API endpoint** for all integrated datasets  
- Improved data consistency and reduced operational overhead  
- Enabled real-time dashboard refreshes using the API as a data source  

---

### Tech Stack
**FastAPI • Python • Pydantic • SQLAlchemy • Azure SQL • GitHub Actions • Docker • OAuth2 Auth**


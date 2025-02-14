
# Dashboard Development & Source Identification Framework

This repository contains a structured approach for **Dashboard Development**, **Data Source Identification**, and **ETA Estimation**. It combines several frameworks and best practices to ensure alignment between **Product Teams** and **Data Teams**, facilitating the process of delivering a business-relevant and technically scalable dashboard.

### 📋 **Form for Dashboard Development & Source Identification**

This form will help structure the dashboard requirements, classify data sources, and estimate the **ETA** based on complexity.

---

## 1️⃣ **General Information**  
| Question | Response |
|----------|---------|
| **Dashboard Name** | *[Enter dashboard name]* |
| **Business Owner** | *[Who requested it?]* |
| **Main Objective** | *[What is the goal?]* |
| **Primary Users** | *[Who will use it?]* |
| **Frequency of Updates** | ☐ Real-time ☐ Daily ☐ Weekly ☐ Monthly |

---

## 2️⃣ **Data Source Identification**  
| Data Source | Type | Existing or New? | Owner | Complexity | Notes |
|------------|------|----------------|-------|------------|------|
| **Source 1** | ☐ API ☐ Database ☐ File | ☐ Existing ☐ New | *[Who manages it?]* | ☐ Low ☐ Medium ☐ High | *[Extra details]* |
| **Source 2** | ☐ API ☐ Database ☐ File | ☐ Existing ☐ New | *[Who manages it?]* | ☐ Low ☐ Medium ☐ High | *[Extra details]* |
| **Source 3** | ☐ API ☐ Database ☐ File | ☐ Existing ☐ New | *[Who manages it?]* | ☐ Low ☐ Medium ☐ High | *[Extra details]* |

---

## 3️⃣ **Key Metrics & KPI Definition (MECE & KPI Tree)**  
| Metric Name | Business Owner | Calculation | Source | ETA |
|------------|---------------|-------------|--------|-----|
| **Metric 1** | *[Who defines it?]* | *[Formula]* | *[Source]* | *[ETA]* |
| **Metric 2** | *[Who defines it?]* | *[Formula]* | *[Source]* | *[ETA]* |
| **Metric 3** | *[Who defines it?]* | *[Formula]* | *[Source]* | *[ETA]* |

---

## 4️⃣ **ETA Estimation Based on Data Source & Complexity**

### 📌 **Estimated Time for Each Phase**  
| Task | Existing Source (Low) | Existing Source (Medium) | New Source (High) |
|------|--------------------|----------------------|----------------|
| **Data Access & Extraction** | 2 days | 5 days | 10+ days |
| **Data Cleaning & Transformation** | 3 days | 7 days | 14+ days |
| **Metric Implementation** | 2 days | 4 days | 8+ days |
| **Dashboard Development** | 3 days | 5 days | 10+ days |
| **Testing & Validation** | 2 days | 4 days | 6+ days |
| **Total Estimated Time** | **12 days** | **25 days** | **48+ days** |

**ETA Formula:**  
\[	ext{ETA} = (	ext{Source Complexity}) + (	ext{Metric Calculation Complexity}) + (	ext{Testing & Validation})\]

---

## 5️⃣ **Final Approvals & Next Steps**  
| Step | Responsible | Status |
|------|------------|--------|
| **Business Approval** | *[Product Owner]* | ☐ Pending ☐ Approved |
| **Data Team Validation** | *[Data Engineer]* | ☐ Pending ☐ Approved |
| **Final ETA Confirmation** | *[Project Manager]* | ☐ Pending ☐ Approved |

---

### 🎯 **How This Helps**
✅ **Clearer requirements** – Ensures both business & data teams align from the start.  
✅ **Source classification** – Helps estimate complexity based on whether a source is new or existing.  
✅ **Data-driven ETAs** – Uses complexity factors to predict realistic timelines.  
✅ **Reduces misalignment** – Avoids delays caused by missing data or unclear metrics.

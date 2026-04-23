# Marico Customer Reconciliation System

### Intelligent Claims Resolution for OT / MT / D2C Channels

---

## 📌 Overview

This project addresses a critical FMCG challenge: **customer reconciliation and claims resolution** across Organised Trade (OT), Modern Trade (MT), and Direct-to-Consumer (D2C) channels.

Traditional reconciliation processes are manual, time-consuming, and prone to mismatches between company records and customer data. This leads to delayed financial closure, blocked working capital, and prolonged dispute cycles.

This solution leverages **n8n automation + AI-driven analysis** to enable faster, scalable, and intelligent reconciliation.

---

## 🎯 Objectives

* Provide near real-time visibility of customer ledger and claims
* Automatically detect and classify reconciliation mismatches
* Reduce manual effort and reconciliation cycle time
* Improve working capital efficiency
* Enable faster dispute resolution

---

## ⚙️ Solution Architecture

The system is built using **n8n workflow automation** with the following components:

### 🔹 Data Ingestion

* Invoice data
* Payment records
* Claims and returns
* Customer ledger inputs

### 🔹 Processing Layer

* Data transformation using Code nodes
* Matching invoices vs payments
* Identifying mismatches:

  * Overpayments
  * Underpayments
  * Missing payments
  * Claims & returns
  * Logistics damages
  * Data quality issues

### 🔹 AI Analysis

* Automatic issue classification
* Root cause identification
* Suggested resolution actions
* Risk prioritization (High / Medium / Low)

### 🔹 Output & Reporting

* Structured reconciliation report
* Executive summary (CFO-level)
* Google Sheets logging
* Automated insights generation

---

## 🧠 Key Features

* ✅ End-to-end automated reconciliation workflow
* ✅ AI-powered mismatch detection and classification
* ✅ SAP-aligned financial logic (AR / SD / FI concepts)
* ✅ Claims and dispute resolution recommendations
* ✅ Data quality validation checks
* ✅ Scalable design for FMCG use cases

---

## 🔗 Integration Readiness

Designed to integrate with:

* ERP Systems (SAP – AR, SD, FI modules)
* Customer data sources
* Document repositories (Invoices, PODs, Credit Notes)

---

## 📊 Business Impact

* 📉 Reduction in receivable ageing
* 💰 Improved working capital utilization
* ⚡ Faster reconciliation cycles
* 🤝 Improved customer trust and transparency
* 📅 Faster month-end and year-end closures

---

## ▶️ How to Use

1. Import the provided `workflow.json` into n8n
2. Open the workflow in the editor
3. Execute using **“Execute Workflow”** (manual trigger for demo)
4. View output in execution logs or connected services

> Note: Webhook trigger is included for real-time use. Due to environment limitations, the workflow can be executed manually for testing.

---

## ⚠️ Constraints & Assumptions

* Tested in a local/demo environment with execution limits
* Uses sample data for simulation
* Designed to scale in production with real ERP integrations

---

## 🚀 Future Enhancements

* Live SAP API integration
* Real-time webhook deployment
* Dashboard visualization (Power BI / Streamlit)
* Predictive dispute detection using ML models

---

## 👩‍💻 Author

**Bhavana Setty**
B.Tech – Information Technology
AI & Data Science Enthusiast

---

## 🏁 Conclusion

This project demonstrates how **automation + AI** can transform traditional reconciliation processes into a **scalable, intelligent, and efficient system**, aligned with real-world FMCG business requirements.

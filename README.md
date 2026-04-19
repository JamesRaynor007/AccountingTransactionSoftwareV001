# 📊 SoftwareContableV001
A small creation to manage transactions and record events with visualization capabilities.

---

## 🚀 User Guide

### 1️⃣ Transaction Upload
- **Download template (XLSX):** allows uploading transactions with 5 columns (base version).  
- **Choose file (XLSX):** select the downloaded template file.  
- **Import:** transactions will be displayed.  

🔧 Features:
- Delete / Add / Filter transactions  
- Export consolidated (XLSX)

---

### 2️⃣ Incremental Update
- **Incremental File:** upload exported template.  
- **Update Consolidated:** generate transaction records and action log.  
- **Download Consolidated:** download JSON with loaded transactions.  
- **Download Log:** download actions performed in the JSON of loaded transactions (prevents duplication).  

📌 Note:  
If you already downloaded a consolidated file, start by loading it in **Base File (JSON)** to avoid duplicates.

---

### 3️⃣ Visualization
- **Load Transactions:** JSON of transactions.  
- **Load Actions:** JSON of log.  

🔍 Visualization options:
- Filter by: date range, amounts, ID, account, description.  
- Sort by: amount (highest to lowest) or by oldest.  

---

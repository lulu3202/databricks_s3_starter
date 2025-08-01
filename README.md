# 🔍 Smart Customer Support Knowledge Base (Notebook 1 & 2)

This repository contains the first two notebooks and sample unstructured files for the **Smart Customer Support Analytics** project using **Databricks** and **AWS**.

---

## 📓 Notebook 1 – Structured Data ETL & Analysis

**Goal**: Prepare structured customer support data for analytics and downstream tasks like summarization or KPI tracking.

**Data Sources**: Structured logs or ticket data - 'support_ticket.csv' under sample file

### ✅ Steps:
- Read structured data from S3  
- Perform basic ETL (filtering, cleaning)  
- Store as Delta tables  


---

## 📓 Notebook 2 – Unstructured Text Processing

**Goal**: Prepare unstructured knowledge base for semantic search and RAG (Retrieval-Augmented Generation)

**Data Sources**: Text documents (FAQs, guides, troubleshooting docs)

### ✅ Steps:
- Load `.txt` files from S3  
- Split long documents into manageable chunks  
- Tag each chunk with metadata like source  
- Store processed chunks in Delta tables  

### 📁 Output Delta Tables:
- `workspace.smart_support.bronze_billing_faq`  
- `workspace.smart_support.bronze_product_guide`  
- `workspace.smart_support.bronze_technical_faq`

---

## 🧪 Sample Files (for Notebook 2)
You’ll find the following unstructured sample files under the `sample_docs/` folder:
- `billing_faq.txt`
- `product_guide.txt`
- `technical_faq.txt`

---

## 🛠️ Requirements

- ✅ Databricks Runtime **14.3+** (with Unity Catalog enabled)  
- ✅ AWS **S3 bucket** (configured with IAM access for Delta external tables)  
- ✅ Python SDK for Databricks (`databricks-sdk` if extended)


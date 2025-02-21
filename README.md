# 🚀 AI-Powered Automation Agent

This project is an **Automation Agent** designed for **DataWorks Solutions**, enabling the execution of plain-English tasks through an **LLM-powered API**. It integrates seamlessly with **Continuous Integration (CI) pipelines** to process logs, reports, and other artifacts efficiently.

## 📌 Project Overview
The agent:
- Accepts **plain-English tasks** via an API.
- Parses the task description using an **LLM (GPT-4o-Mini)**.
- Executes multi-step operations such as data extraction, transformation, and verification.
- Ensures all processed artifacts are **exactly verifiable**.

## 🛠️ Features
✅ **Run Tasks**: Execute automated processes via `/run?task=<task description>`.  
✅ **Read Outputs**: Verify execution results with `/read?path=<file path>`.  
✅ **LLM Integration**: Uses AI to interpret and execute tasks.  
✅ **Security & Compliance**: Ensures no unauthorized file access or deletion.  
✅ **Dockerized Deployment**: Ready-to-run using Docker or Podman.  

---

## 📡 API Endpoints

### 🔹 **Execute a Task**
```http
POST /run?task=<task description>

# Lead Enricher Pro 🚀  
**Automated Lead Research & Contact Discovery with n8n**

---

## 📌 Overview  
**Lead Enricher Pro** is an n8n automation workflow designed to supercharge lead research by automatically enriching company data with verified social links and executive emails. It reads business details from a Google Sheet, performs targeted web searches, cleans and validates results, and appends the enriched data back to the sheet — all without manual effort.

---

## ✨ Features  
- 🔎 **Smart Search** — Uses Google Search API to find company websites and social media pages.  
- 📬 **Email Discovery** — Fetches executive and generic emails using Hunter.io.  
- 🧹 **Clean & Validate** — Filters out irrelevant links and ensures accuracy.  
- 📊 **Google Sheets Integration** — Automatically updates rows with enriched lead data.  
- ⚡ **End-to-End Automation** — Fully managed inside **n8n** with no coding required.  

---

## 🛠️ Tech Stack  
- **n8n** (workflow automation)  
- **Google Sheets API**  
- **Google Custom Search API**  
- **Hunter.io API**  
- **JavaScript (n8n Code Nodes)**  

---

## 📂 Repository Structure  
- `Lead-Enricher-Pro.json` → The n8n workflow export file.  
- `README.md` → Project documentation.  

---

## 🚀 Getting Started  

1. Clone this repo or download the workflow JSON.  
2. Import the workflow into your **n8n** instance.  
3. Add your own credentials for:  
   - Google Sheets  
   - Google Custom Search API  
   - Hunter.io API  
4. Run the workflow and watch your leads get enriched automatically.  

---

## ⚠️ Important Notes  
- API keys and sensitive credentials **are not included** in this repo.  
- You must configure your own credentials in n8n before using the workflow.  
- Do not share your private API keys publicly.  

---

## 📜 License  
MIT License — Feel free to use, modify, and share.  

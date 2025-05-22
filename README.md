# 🤖 Case Study: Building My First AI Agent for Job Search Automation with n8n (Free Tier)

Welcome to my **first hands-on project using [n8n](https://n8n.io/)** — a no-code/low-code workflow automation platform. In this case study, I created an **AI-powered job search agent** that monitors job postings from RSS feeds, extracts useful metadata using a **free LLM (Groq API)**, and updates a **Google Sheet** with enriched insights — all automatically.

> 🆓 This project is entirely built on free tools: n8n (trial), Groq LLM (via LangChain), and Google Sheets.

---

## 💡 Project Summary

🔍 **Objective:** Automate the process of fetching, organizing, and enriching job listings using AI.  
⚙️ **Workflow Tool:** [n8n.io](https://n8n.io/)  
🧠 **AI Model:** Groq Chat (connected via LangChain)  
📋 **Storage:** Google Sheets

---

## 🔧 Tech Stack & Tools

- **n8n:** Automation and flow orchestration
- **Groq LLM (via LangChain):** Natural language information extraction
- **Google Sheets API:** Storing and updating job listings
- **RSS Feed:** Source of job posts (e.g., LinkedIn, remote job boards)

---

## 🔁 Workflow Architecture

### 🖼 Main Flow
![n8n Workflow](https://github.com/HEMAL60/LinkdinJobSheetAIAgent/blob/main/n8n%20workflow.png)

### 🧠 AI Extraction Subflow
![LLM Extraction](.https://github.com/HEMAL60/LinkdinJobSheetAIAgent/blob/main/n8n%20workflow%202.png)

---

## 📂 Project Files

| File | Description |
|------|-------------|
| `workflow/My_workflow.json` | The complete n8n workflow file |
| `assets/*.png` | Workflow UI screenshots |
| `data/linkdin_job_listing.xlsx` | Example data output in Excel format |
| `README.md` | This case study |

---

## 🛠 Setup Instructions

1. **Clone or download this repo.**
2. **Import `My_workflow.json` into your n8n instance.**
3. Configure:
   - Your own **RSS Feed URL**
   - A **Google Sheet** with appropriate headers
   - Add your **Groq API key** to LangChain credentials in n8n
4. **Activate** the workflow and schedule the trigger.

> ✅ The entire workflow can run using n8n’s free-tier (up to 1,000 executions on trial) and free LLM usage via Groq.

---

## 🚀 Future Enhancements (With Paid or Custom LLM API Access)

Once upgraded to access more powerful or personalized LLMs (e.g., OpenAI, Claude, Mistral), you can enhance the agent by:

- 🎯 **ATS Score Matching** – Compare your resume with each job post and generate a match percentage.
- 📝 **Custom Cover Letter Generation** – Automatically generate tailored cover letters for each job based on the job description.
- 📬 **Auto Email or LinkedIn Message Drafting** – Send personalized job inquiry emails or messages to recruiters.
- 🔔 **Real-time Notifications** – Slack/Discord/Email alerts for high-match jobs.

---

## 🧠 My Learnings

This was my **first project using n8n** and **my first time building an AI agent** from scratch. Through this workflow:

- I understood how to orchestrate automation using visual no-code tools.
- I explored integrating AI (Groq LLM) with practical use-cases.
- I learned to structure job data for better analysis and action.

---

## 📚 Author Profile

👤 **Hemal Nakrani**  
🎓 MSc in Artificial Intelligence (Distinction) – Birmingham City University  
📄 Published Research: *Advanced Diagnosis of Cardiac and Respiratory Diseases using Deep Learning Ensembles* — [Read in MDPI](https://www.mdpi.com/2224-2708/14/2/44)

---

## 📃 License

MIT License

---

### 💬 Want to Collaborate?

Feel free to connect with me on [LinkedIn](https://www.linkedin.com/in/hemal-nakrani) or explore this repo and share feedback!

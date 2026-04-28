# 🚀 AI Automation Workflows using n8n

> Developed during my **AI Strategy & Business Intelligence Internship** at **IBM SkillsBuild** in collaboration with **CSRBOX**.

This repository contains two AI-powered workflow automation projects built using **n8n**, integrating AI models, Google Sheets, Gmail APIs, and rule-based decision systems to solve real-world operational challenges in healthcare and food management.

---

# 📌 Project Overview

The goal of these projects was to design intelligent automation systems capable of:
- Reducing manual effort
- Improving operational efficiency
- Automating decision-making
- Enabling real-time notifications
- Managing data workflows effectively

Both workflows demonstrate practical applications of:
- Artificial Intelligence
- Workflow Automation
- Business Intelligence
- Low-Code/No-Code Development
- API Integrations

---

# 🏥 Workflow 1: AI-Powered Hospital Reception & Ward Allocation System

## 📖 Problem Statement

Hospitals often face delays in manually identifying the correct department or ward for incoming patients. Reception management becomes difficult during high patient traffic, especially in emergency situations.

This workflow automates the patient intake and ward allocation process using AI-based query classification.

---

## 🎯 Objective

To automate:
- Patient registration
- AI-based symptom analysis
- Ward allocation
- Doctor assignment
- Email notifications
- Hospital database updates

---

# ⚙️ Technologies Used

| Technology | Purpose |
|---|---|
| `n8n` | Workflow automation |
| `OpenAI GPT-4o-mini` | AI-based patient query classification |
| `Google Sheets API` | Patient & doctor database management |
| `Gmail API` | Automated email notifications |
| `Prompt Engineering` | AI instruction handling |

---

# 🔄 Workflow Architecture

## 1️⃣ Patient Form Submission

Patients submit details through an automated receptionist form including:
- Name
- Age
- Email
- Phone Number
- Health Query

---

## 2️⃣ AI-Based Query Classification

The workflow uses an OpenAI model to analyze patient symptoms and classify them into:

- **General Ward**
- **Emergency Ward**
- **Mental Health Ward**

### 🧠 Example Logic
- Fever, cough, headache → General Ward
- Heart attack, accident → Emergency Ward
- Depression, anxiety → Mental Health Ward

---

## 3️⃣ Conditional Routing

Using IF conditions in n8n:
- Patients are routed to the appropriate ward
- Available doctors are fetched from Google Sheets

---

## 4️⃣ Automated Doctor Notification

Doctors receive automated Gmail notifications containing:
- Patient name
- Patient symptoms
- Consultation request

---

## 5️⃣ Real-Time Database Update

Google Sheets is automatically updated with:
- Patient details
- Assigned ward
- Doctor status
- Consultation summary

---

# ✨ Key Features

✅ AI-driven patient triage system  
✅ Automated doctor allocation  
✅ Real-time hospital workflow management  
✅ Email automation system  
✅ Centralized patient tracking  
✅ Reduced manual intervention  

---

# 📈 Business Impact

- Faster patient handling
- Improved emergency response
- Reduced receptionist workload
- Better hospital resource management
- Streamlined consultation process

---

# 🍱 Workflow 2: Smart Food Management & Redistribution System

## 📖 Problem Statement

Large quantities of edible food are wasted daily due to inefficient redistribution systems. Many organizations struggle to identify whether surplus food is suitable for:
- Human consumption
- Animal feeding
- Composting

This workflow automates food classification and redistribution.

---

## 🎯 Objective

To automate:
- Food data collection
- Food condition analysis
- Smart food categorization
- Automated notifications
- Waste management tracking

---

# ⚙️ Technologies Used

| Technology | Purpose |
|---|---|
| `n8n` | Workflow automation |
| `Google Sheets Trigger` | Real-time data monitoring |
| `JavaScript` | Rule-based food classification |
| `Gmail API` | Automated alert system |
| `Google Sheets API` | Logging & reporting |

---

# 🔄 Workflow Architecture

## 1️⃣ Google Sheets Trigger

The workflow starts automatically whenever a new food entry is added.

### 📋 Input Data Includes
- Food type
- Quantity
- Food age
- Storage condition
- Pickup availability
- Location

---

## 2️⃣ Data Structuring

Incoming form data is cleaned and standardized using Set nodes in n8n.

---

## 3️⃣ Intelligent Food Classification

A JavaScript rule engine categorizes food into:

| Category | Action |
|---|---|
| Human Consumption | Donate |
| Animal Feed | Feed Farm Animals |
| Waste | Compost |

---

## 🧠 Example Classification Rules

### ✅ Human Consumption
Fresh cooked food within safe hours:
- Cooked rice
- Dal
- Chapati

### 🐄 Animal Feed
Moderately old:
- Vegetables
- Fruits

### ♻️ Compost/Waste
Expired or unsafe food:
- Sent for composting

---

## 4️⃣ Smart Routing using Switch Node

Based on food category:
- NGOs receive donation alerts
- Farms receive animal feed alerts
- Composting units receive waste alerts

---

## 5️⃣ Automated Email Notifications

Automated Gmail alerts are sent with:
- Food quantity
- Food type
- Pickup location
- Recommended action

---

## 6️⃣ Data Logging & Monitoring

All activities are recorded in Google Sheets for:
- Reporting
- Analytics
- Sustainability tracking
- Monitoring food redistribution

---

# ✨ Key Features

✅ Smart food redistribution  
✅ Automated waste reduction  
✅ Rule-based decision system  
✅ Real-time notifications  
✅ Sustainability-focused automation  
✅ Food lifecycle tracking  

---

# 📈 Business Impact

- Reduced food wastage
- Improved resource utilization
- Faster redistribution process
- Enhanced sustainability efforts
- Better food management tracking

---

# 🛠 Skills Demonstrated

Through these projects, I gained hands-on experience in:

- Workflow Automation
- AI Integration
- Prompt Engineering
- Business Intelligence
- API Integration
- Process Automation
- Real-Time Notifications
- Rule-Based Systems
- Data Management
- Low-Code/No-Code Development

---

# 📊 Tools & Platforms

| Tool | Usage |
|---|---|
| `n8n` | Workflow orchestration |
| `OpenAI API` | AI-based decision making |
| `Google Sheets` | Database & tracking |
| `Gmail API` | Automated communication |
| `JavaScript` | Logic implementation |

---

# 🚀 Future Improvements

## Hospital Workflow
- WhatsApp/SMS notifications
- Appointment scheduling
- Multi-language support
- Power BI dashboard integration
- Real-time doctor availability system

---

## Food Management Workflow
- AI-based food quality prediction
- NGO database integration
- IoT sensor integration
- Live analytics dashboard
- Mobile application integration

---

# 📌 Learning Outcomes

Through these projects, I learned:
- Practical AI workflow development
- Business automation strategies
- Real-world API integrations
- Automation architecture design
- Intelligent decision-making systems
- End-to-end workflow orchestration

---

# 🤝 Acknowledgements

Special thanks to:
- **IBM SkillsBuild**
- **CSRBOX**

for providing the opportunity to work on real-world AI and Business Intelligence projects.

---


# ⭐ Conclusion

These projects demonstrate how AI and automation can optimize operational workflows in healthcare and sustainability domains. By combining AI-driven decision-making with workflow automation, the systems improve efficiency, reduce manual effort, and enable scalable real-world solutions.

---

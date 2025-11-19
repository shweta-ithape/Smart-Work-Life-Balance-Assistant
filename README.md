## 🧠 Smart Work–Life Balance Assistant

An AI-powered assistant that helps users maintain a healthy work–life balance by intelligently managing tasks, analyzing priorities, and scheduling work sessions using autonomous agents.

---

## 🌟 Overview
Modern life is busy—deadlines, meetings, and personal commitments create daily chaos. Most productivity tools require manual entry and decision-making, which leads to stress and overload.

The **Smart Work–Life Balance Assistant** solves this problem using intelligent agents that:
- Understand natural language commands  
- Create and manage tasks  
- Analyze urgency automatically  
- Schedule work sessions for you  
- Reduce cognitive load  
- Improve productivity and well-being  

---

## 🚨 Problem Statement
Work–life imbalance causes stress, burnout, and reduced productivity.  
People juggle:
- Professional tasks  
- Deadlines  
- Meetings  
- Personal commitments  

But existing tools require too much manual work.

This project aims to create an **intelligent, automated, natural-language–based productivity assistant** that organizes your day without micromanagement.

---

## 🤖 Why Agents?
Agents are the ideal solution because they enable:

### **✔ Natural Language Understanding**
Users simply say:
- “Create a task due tomorrow”
- “Analyze priority”
- “Schedule a 2-hour session tomorrow afternoon”

### ✔ **Autonomous Decision-Making**
The agent automatically:
- Determines priority  
- Suggests schedules  
- Manages workload  

### ✔ **Modularity & Scalability**
New agents can be added later:
- Wellness Agent  
- Break Reminder Agent  
- Health Tracking Agent  

### ✔ **Reduced Cognitive Load**
No manual scheduling or priority thinking—the agent handles everything.

---

## 🏗️ Architecture Overview

### **System Workflow**
![Workflow](https://www.googleapis.com/download/storage/v1/b/kaggle-user-content/o/inbox%2F25268808%2Fada29d6deedd4583cc7ef16a2e5f2289%2FWorkflow.png?generation=1763553579023802&alt=media)

### **Core Components**

#### **1. Task Management Module**
- Creates tasks  
- Assigns priority  
- Tracks status  
- Handles due dates  

#### **2. Event Scheduling Module**
- Auto-schedules work sessions  
- Suggests next-day afternoon slot  
- Connects tasks to events  

#### **3. Priority Analysis Engine**
Priority based on time left:
- < 24 hours - **High**  
- 24–72 hours - **Medium**  
- > 72 hours - **Low**  

#### **4. Metrics & Logging System**
Tracks:
- Response time  
- Total requests  
- Tool usage  
- Quality scoring  

#### **5. Productivity Runner (Main Agent)**
- Understands user intent  
- Extracts parameters  
- Calls modules  
- Generates clean output  

---

## 🎬 Demo

### **User Input**
Create a high-priority task to review project reports due in 2 days and analyze its priority.

### **Agent Output**

Task created: Review project reports (Priority 1, Due: 2025-11-22)
Priority: Medium
Event scheduled from 2025-11-20T15:00 to 2025-11-20T17:00

### **Supported Commands**
- “List my tasks”  
- “Mark assignment as completed”  
- “Create a task due in 3 days”  
- “Schedule 2 hours tomorrow afternoon”  
- “Analyze this task’s priority”  

---

## 🛠️ Build – Tools & Technologies

- **Python** for backend logic  
- **In-memory storage** for tasks/events  
- **UUID** for unique task/event IDs  
- **datetime** for deadline + scheduling logic  
- **Rule-based NLP** for lightweight intent understanding  
- **Metrics monitoring** for performance  

---

## ✨ Key Features
- Natural-language task creation  
- Automatic priority analysis  
- Auto-scheduling of work sessions  
- Task tracking  
- Event creation  
- Clean structured output  
- Agent-driven logic  

---

## 🔮 Future Enhancements

### With more time, I would add:
- Machine learning–based scheduling  
- Google/Outlook calendar sync  
- Push notifications  
- Daily wellness suggestions  
- Productivity dashboard (charts, analytics)  
- Multi-agent collaboration  
  - Task Agent  
  - Scheduling Agent  
  - Wellness Agent  

---

## 🧩 Conclusion
The **Smart Work–Life Balance Assistant** demonstrates how intelligent agents can simplify daily planning by automating key decisions about tasks, deadlines, and schedules.

It reduces stress, improves productivity, and helps maintain a healthier work–life balance—all through simple natural-language interaction.

---

## 📄 Author
**Shweta Ithape**  
Smart Work–Life Balance Assistant — AI Agent Project  

---


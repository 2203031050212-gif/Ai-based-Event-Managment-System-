# 🚀 EventAI (Orchestron) - AI-Driven Event Management System

**EventAI** (also referred to as **Orchestron**) is a web-based workspace designed to automate, streamline, and optimize the entire lifecycle of event planning and execution. By unifying calendar scheduling, financial budget analytics, attendee lifecycle tracking, task coordination, and a conversational AI copilot into a single dashboard, EventAI eliminates the fragmentation of traditional spreadsheets and disconnected planning tools.

---

## 🌟 Key Features

* **🤖 Conversational AI Copilot:** Grounded directly in live workspace data to answer questions regarding budget status, attendee confirmations, schedule conflicts, and task completion.
* **📊 Financial Analytics & Budget Tracking:** Real-time calculation of expense allocations, total spend, remaining budget, and dynamic visual progress indicators.
* **📅 Event Lifecycle & Calendar Scheduling:** Integrated monthly calendar view supporting event creation, revenue projections, and attendee forecasting.
* **👥 Attendee Management:** Full lifecycle tracking (`Pending`, `Confirmed`, `Attended`) with instant filtering and search capability.
* **⚡ Task & Timeline Manager:** Priority-based task assignment (`Low`, `Medium`, `High`) with aggregate task-completion percentages.
* **💡 Rule-Based Insight Engine:** Automated real-time alerts for budget utilization (>80%), attendance engagement, and task lags without requiring external LLM API calls.

---

## 🛠️ Technology Stack

* **Frontend:** React.js, Tailwind CSS, Lucide Icons, Recharts
* **Backend:** Node.js, Express.js
* **Database:** MongoDB / Mongoose ODM
* **AI Engine:** Large Language Model (LLM) Integration API
* **Architecture:** RESTful Web Architecture

---

## 🏗️ Project Architecture

```text
EventAI Workspace
├── Frontend (React.js)
│   ├── Dashboard & Analytics Visuals
│   ├── Event Creation & Calendar
│   ├── Budget & Expense Management
│   ├── Attendee & Task Trackers
│   └── AI Copilot Interface
│
├── Backend (Node.js / Express)
│   ├── Authentication Middleware
│   ├── REST API Endpoints
│   ├── Derived Metrics Calculation Engine
│   └── Rule-Based Insight Engine
│
└── Database & External APIs
    ├── Persistent Store (User, Event, Budget, Attendee, Task)
    └── AI Model Service (Context-grounded prompt handling)
```

---

## 🚀 Quick Start & Installation

### Prerequisites
* [Node.js](https://nodejs.org/) (v16.x or higher)
* [npm](https://www.npmjs.com/) or [yarn](https://yarnpkg.com/)
* [MongoDB](https://www.mongodb.com/) (Local or Cloud Instance)

### 1. Clone the Repository
```bash
git clone https://github.com/your-username/ai-event-management-system.git
cd ai-event-management-system
```

### 2. Environment Setup
Create a `.env` file in the root directory and add the following configuration:
```env
PORT=5000
MONGO_URI=mongodb+srv://your_username:your_password@cluster.mongodb.net/eventai
JWT_SECRET=your_jwt_secret_key
AI_API_KEY=your_ai_llm_api_key
```

### 3. Install Dependencies
```bash
npm install
```

### 4. Run the Application
```bash
# Run both frontend and backend concurrently
npm run dev
```
Open [http://localhost:3000](http://localhost:3000) in your browser to view the application.

---

## 📄 License
This project is developed for academic and portfolio demonstration purposes.
# 🎫 Ticket Analysis Dashboard – Power BI

## 📌 Project Overview
This project is an end-to-end Power BI dashboard designed to analyze customer support tickets across queues, categories, priorities, and request types.

The dashboard helps stakeholders:
- Identify the busiest queues
- Understand ticket priority distribution
- Detect top issue categories
- Drill down into detailed category-level insights

---

## 🛠️ Tools & Technologies
- Power BI
- DAX
- Data Modeling
- Drill-through & Bookmarks
- Custom Power BI Theme (JSON)

---

## 📊 Dashboard Pages

### 1️⃣ Executive Overview
- Total tickets
- % high-priority tickets
- Average priority score
- Top category and most common queue
- Key insights summary

### 2️⃣ Queue Breakdown
- Ticket volume by queue
- Priority distribution per queue
- Request type distribution
- Top issue categories per queue

### 3️⃣ Queue Details (Drill-through)
- Queue-specific KPIs
- Priority, type, and category breakdowns
- Context-aware navigation

### 4️⃣ Category Analysis
- Category hierarchy (Primary / Secondary / Tertiary)
- Cost and priority impact by category
- Category type distribution

### 5️⃣ Category Details (Drill-through)
- Deep dive into selected category
- Queue distribution
- Priority and request type breakdown

---

## 💡 Key Insights
- Technical Support is the busiest queue
- Performance-related issues dominate ticket volume
- ~39% of tickets are high priority, indicating escalation risk
- Requests and Incidents account for most tickets

---

## 📁 Repository Structure
├── Ticket_Analysis_Dashboard.pbix
├── README.md
├── screenshots/
│ ├── overview.png
│ ├── queue_breakdown.png
│ ├── category_analysis.png
│ └── category_details.png
└── theme/
└── powerbi_theme.json

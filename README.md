# 🛠️ ServiceNow Team Productivity Dashboard

This repository contains a fully working **ServiceNow Update Set** implementing a **Team Productivity Dashboard** inside the **Service Portal Designer**.  
It includes custom widgets, charts, and dynamic real-time data rendering, designed to help teams monitor performance, track KPIs, and analyze article metrics efficiently.

---

## 📦 Contents

- `team_productivity_dashboard_update_set.xml` – Exported update set file including:
  - Custom Widgets
  - Portal Page Layouts
  - GlideRecord scripts
  - Chart.js implementation
  - UI Configurations (columns, instance mappings, etc.)

---

## 🚀 Features Implemented

### 🔹 Dashboard Components
- **Landing Banner Widget** – HTML-based intro with styled layout
- **KPI Summary** – Custom widget showing real-time knowledge base metrics
- **Performance Trend Graph** – Chart.js graph showing average age of open incidents
- **Team Contributions List** – Interactive list linking to filtered article views
- **Top 10 Agents Table** – Resolved incidents by agent (ranked)

### 🔹 Dynamic Integration
- Server-side data binding using **Script Includes** and `GlideRecord`
- Filter-based navigation to tables like `kb_knowledge_list.do`
- Real-time record fetch and display without manual refresh

---

## 🛠️ Technologies Used

| Layer             | Tools/Tech Used              |
|-------------------|------------------------------|
| Frontend          | Service Portal Designer, AngularJS, HTML, CSS, Chart.js |
| Backend           | GlideRecord, Server Script, Client Script|
| Platform          | ServiceNow (Global Scope)    |
| Export Mechanism  | Update Set (XML format)      |

---

## 📥 Installation & Import

### 📌 Pre-requisite
Ensure you're logged into a **ServiceNow instance** with an admin role.

### 📦 Steps:
1. Navigate to: `System Update Sets > Retrieved Update Sets`
2. Click on **Import Update Set from XML**
3. Choose the file:  
4. After import completes:
- Click **Preview Update Set**
- Click **Commit Update Set** if no errors

---

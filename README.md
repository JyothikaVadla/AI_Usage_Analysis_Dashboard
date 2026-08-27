# 📊 AI Usage Analysis Dashboard

## 📌 Project Overview

The **AI Usage Analysis Dashboard** is an interactive Business Intelligence project developed using **Microsoft Power BI**, with data preparation and analysis supported by **Excel and SQL/MySQL**.

The dashboard analyzes how users interact with different AI tools by examining **user activity, AI tool usage, subscription plans, usage hours, cities, and usage trends over time**.

The objective of this project is to transform raw AI usage data into meaningful business insights through interactive dashboards and data visualization.

---

## 🎯 Business Objective

The main objective of this project is to understand:

- 👥 How many users are using AI tools?
- 🤖 Which AI tools receive the highest usage?
- ⏱️ How many hours are users spending on AI tools?
- 📈 How does AI usage change over time?
- 🌍 How are users distributed across different cities?
- 💳 How are users distributed across subscription plans?
- 🔍 Which AI tools contribute most to overall usage?

These insights can help businesses understand **user engagement, tool popularity, and subscription behavior**.

---

## 🛠️ Tools & Technologies

| Tool | Purpose |
|------|---------|
| 🟨 Excel | Data preparation and initial data cleaning |
| 🗄️ MySQL | Data storage and SQL-based analysis |
| 📊 Power BI | Data modeling, visualization and dashboard development |
| 📐 DAX | KPI calculations and analytical measures |
| 📝 GitHub | Project documentation and portfolio |

---

## 📂 Dataset

The dataset contains user-level AI usage information.

### Main Fields

- `user_id` – Unique identifier for each user
- `name` – User name
- `city` – User location
- `profession` – User profession
- `tool_id` – AI tool identifier
- `tool_name` – Name of the AI tool
- `usage_date` – Date of AI tool usage
- `hours_used` – Number of hours spent using the AI tool
- `plan_name` – User subscription plan

---

## 📊 Dashboard Overview

The Power BI dashboard provides an interactive view of AI usage patterns.

### 🔹 KPI Cards

The dashboard includes the following key performance indicators:

- **Total Users:** 5
- **Total AI Tools:** 5
- **Total Hours Used:** 26.60
- **Average Hours Used:** 2.66

These KPIs provide a quick overview of the overall dataset.

---

## 📈 Dashboard Visualizations

### 1. 🤖 AI Tool Usage by Hours

A bar chart compares the total usage hours across different AI tools.

**Purpose:**
- Identify the most frequently used AI tools
- Compare tool-level engagement
- Identify tools with relatively low usage

---

### 2. 📅 Daily AI Usage Trend

A line chart shows how AI usage changes over time.

**Purpose:**
- Identify usage fluctuations
- Understand daily engagement patterns
- Detect high and low usage periods

---

### 3. 💳 Subscription Plan Distribution

A donut chart displays the distribution of users across subscription plans such as:

- Free
- Plus
- Pro

**Purpose:**
- Understand subscription behavior
- Compare different customer segments
- Identify the overall plan distribution

---

### 4. 🌍 Users by City

A column chart shows the number of users across different cities.

**Purpose:**
- Compare geographic user distribution
- Identify cities with higher user representation
- Understand the geographic spread of AI adoption

---

### 5. 👤 User Usage Details

A detailed table provides user-level information including:

- Name
- City
- Profession
- AI Tool
- Usage Date
- Hours Used
- Subscription Plan

This allows users to drill into individual usage records.

---

### 6. 🎛️ Interactive Filters

The dashboard includes interactive slicers for:

- AI Tool
- City

Users can select specific categories to dynamically filter the dashboard visuals.

---

# 💡 Key Insights

Based on the dashboard analysis:

### 1. 📈 AI usage varies across dates

The daily usage trend shows noticeable fluctuations in engagement over time, indicating that AI usage is not consistent across all days.

### 2. 🤖 Usage is concentrated among selected AI tools

A small number of AI tools account for a larger share of total usage hours, suggesting that certain tools have stronger user engagement.

### 3. 🌍 User distribution is relatively balanced across cities

The dashboard shows a similar number of users across the analyzed cities, indicating that AI usage is geographically distributed rather than concentrated in one location.

---

# 🧮 Key Metrics

The project uses analytical calculations to derive important metrics such as:

### Total Users

```text
COUNT(User_ID)

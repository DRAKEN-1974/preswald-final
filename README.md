# 📊 Indian Startup Funding Dashboard

**A data-driven dashboard providing real-time insights into India's startup funding ecosystem.**  
Built using Python and the Preswald framework, this tool visualizes funding trends, key metrics, and top sectors.

---

## 🚀 Features

- 📅 Recent Funding Deals: View the latest startup deals with date, amount, and sector.
- 🧮 Key Metrics: Total funding raised, average deal size, total startups, and active cities.
- 🏙️ Top Cities: Bar chart showing cities with the highest funding received.
- 💸 Investment Rounds: Pie chart distribution of top investment rounds.
- 🏢 Industry Verticals: Sector-wise breakdown of top-funded domains.
- 🎛️ Interactive Filter: Slider to filter data based on minimum funding amount.
- 📈 Visuals: Beautiful charts powered by Plotly Express.

---

## 📦 Technologies Used

- Python 3
- Pandas
- Plotly Express
- Preswald (for text, connect, get_df, UI components)

---

## 📁 Data Source

The dashboard fetches data using:

```python
from preswald import connect, get_df
connect()
df = get_df("startup_funding")
---

he dataset is expected to contain the following key columns:

Date

Startup

City

Vertical

Investment Round

Amount in INR(cr)

🧪 How It Works
Cleans and parses funding data

Converts amount strings to numeric values

Drops rows with missing or invalid entries

Applies interactive filters

Generates dynamic charts and tables for visual insights

📷 Sample Screenshots
Add screenshots or a screen recording of your dashboard UI here (if required by the internship submission).

🧠 Insights Captured
💡 Top performing cities, sectors, and investment rounds

📊 Real-time deal distribution with filtering capability

🏆 Easy-to-interpret data for stakeholders and analysts

📅 Last Updated
Automatically shown at the bottom of the dashboard.
Format: YYYY-MM-DD HH:MM:SS UTC

🛠️ Setup Instructions
This app runs inside the Preswald environment.

Clone the repo or open the .py file

Ensure preswald, pandas, and plotly are available

Run the script in the Preswald environment

🙌 Author
Gudhal Chauhan
Full Stack Developer Intern @ Preswald
LinkedIn: [Add your link here]
GitHub: [Add your link here]

📢 Powered By
Preswald – Transforming data into dynamic dashboards.

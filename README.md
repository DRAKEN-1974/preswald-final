Indian Startup Funding Dashboard
🚀 Structured Labs Coding Assessment Submission
An interactive dashboard built using the Preswald framework that visualizes key insights from the Indian startup ecosystem — including funding trends, top cities, investment rounds, and sectors.

📦 Project Setup
Requirements
Python 3.8+

Google Chrome

Preswald (install via pip)

Setup Instructions
Install Preswald:
pip install preswald

Initialize project:
preswald init my_assessment_app

Navigate to the project folder:
cd my_assessment_app

Start the development server:
preswald run

Open in browser:
http://localhost:8000

📁 Dataset
The dataset used is a public Indian startup funding dataset, which includes columns like:

Startup

City

Vertical

Investment Round

Amount in INR (Cr)

Date

It was placed inside the data/ folder and referenced in the preswald.toml file.

🚀 Features
Key Metrics: Total funding, average deal size, number of startups, and cities

Dynamic Table: View recent startup funding deals

Filter Slider: Adjust minimum funding amount dynamically

Top Cities Chart: Bar chart showing top 10 cities by total funding

Investment Round Distribution: Pie chart showing funding share by round

Top Sectors: Bar chart for top-funded sectors

Summary Insights: Auto-calculated insights (top city, round, sector)

Last Updated Timestamp: UTC timestamp showing data freshness

🧠 How the App Works
Load dataset using Preswald’s connect() and get_df()

Clean data and convert types (e.g., dates, currency)

Apply interactive filters via slider and inputs

Visualize data using Plotly Express

Render components with Preswald widgets (text, table, plotly, etc.)

🔁 Export Instructions
To export the project as a static HTML version, run:

bash
Copy
Edit
preswald export --format html
This will create a folder named dist/ that contains the complete HTML version of your dashboard, ready to be zipped or submitted.

🙋 Author
Gudhal Chauhan
Full Stack Developer | Internship Candidate
GitHub: https://github.com/DRAKEN-1974
LinkedIn: (Add your LinkedIn profile URL here)

🧠 Powered By
Preswald – Build powerful data apps in minutes
GitHub: https://github.com/StructuredLabs/preswald


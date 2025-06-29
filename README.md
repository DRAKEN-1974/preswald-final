Indian Startup Funding Dashboard
Structured Labs Coding Assessment Submission
An interactive dashboard built using the Preswald framework that visualizes key insights from the Indian startup ecosystem, including funding trends, top cities, investment rounds, and sectors.


📦 Project Setup
Requirements

Python 3.8 or higher

Google Chrome

preswald installed via pip

Setup Instructions

Install Preswald using: pip install preswald

Create project using: preswald init my_assessment_app

Navigate to the folder: cd my_assessment_app

Start server: preswald run

Open browser at: http://localhost:8000

📁 Dataset
The dataset used is a public dataset containing Indian startup funding data.
It includes columns like:

Startup

City

Vertical

Investment Round

Amount in INR (Cr)

Date

The dataset was placed inside the data/ folder and referenced in preswald.toml.

🚀 Features
Key Metrics: Total funding, average deal size, number of startups, and cities

Dynamic Table: Shows recent startup funding deals

Filter Slider: Set a minimum funding threshold interactively

Top Cities Chart: Bar chart showing top 10 cities by funding

Investment Round Distribution: Pie chart showing share by round

Top Sectors: Bar chart of sectors receiving the most funding

Summary Insight Section: Auto-calculated top city, round, and sector

Last Updated Timestamp: UTC time for dashboard update

🧠 How the App Works
Load dataset using Preswald’s connect and get_df

Clean and convert data types (dates, numeric values)

Apply filters dynamically based on user input

Generate visualizations using Plotly Express

Render UI using Preswald widgets like text, table, slider, and plotly

🔁 Export Instructions
To export the final version of the app as a static site, run:

preswald export --format html

It generates a folder called dist/ containing a complete HTML version of the app, ready to be zipped or deployed.

🙋 Author
Gudhal Chauhan
Full Stack Developer | Internship Candidate
GitHub: https://github.com/DRAKEN-1974
LinkedIn: (Add your LinkedIn profile)

🧠 Powered By
Preswald – Build powerful data apps in minutes
https://github.com/StructuredLabs/preswald


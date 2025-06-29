#  Indian Startup Funding Dashboard  
###  Structured Labs Coding Assessment Submission

An interactive dashboard built using the **Preswald** framework that visualizes key insights from the Indian startup ecosystem — including funding trends, top cities, investment rounds, and sectors.

---

##  Project Setup

### Requirements
- Python 3.8 or higher  
- Google Chrome  
- preswald installed via pip

### Setup Instructions
1. Install Preswald  
   `pip install preswald`

2. Create project  
   `preswald init my_assessment_app`

3. Navigate to the project directory  
   `cd my_assessment_app`

4. Start development server  
   `preswald run`

5. Open browser at  
   `http://localhost:8000`

---

## 📁 Dataset

The dataset used is a public dataset containing Indian startup funding data.

### Columns Included:
- Startup  
- City  
- Vertical  
- Investment Round  
- Amount in INR (Cr)  
- Date  

The dataset is placed in the `data/` folder and referenced in the `preswald.toml` configuration file.

---

##  Features

- **Key Metrics**: Total funding, average deal size, number of startups, and cities  
- **Dynamic Table**: Shows recent startup funding deals  
- **Filter Slider**: Set a minimum funding threshold interactively  
- **Top Cities Chart**: Bar chart showing top 10 cities by funding  
- **Investment Round Distribution**: Pie chart showing share by round  
- **Top Sectors**: Bar chart of sectors receiving the most funding  
- **Summary Insight Section**: Auto-calculated top city, round, and sector  
- **Last Updated Timestamp**: UTC time for dashboard update  

---

## How the App Works

- Load dataset using `connect()` and `get_df()` from Preswald  
- Clean and convert data types (dates, numeric values)  
- Apply filters dynamically based on user input  
- Generate visualizations using Plotly Express  
- Render UI using Preswald widgets like `text`, `table`, `slider`, and `plotly`  

---

##  Export Instructions

To export the final version of the app as a static site, run:  
`preswald export --format html`

This generates a folder called `dist/` containing a complete HTML version of the app, ready to be zipped or deployed.

---

##  Author

**Gudhal Chauhan**  
Full Stack Developer | Internship Candidate  
GitHub: [https://github.com/DRAKEN-1974](https://github.com/DRAKEN-1974)  


---

##  Powered By

**Preswald** – Build powerful data apps in minutes  
GitHub: [https://github.com/StructuredLabs/preswald](https://github.com/StructuredLabs/preswald)

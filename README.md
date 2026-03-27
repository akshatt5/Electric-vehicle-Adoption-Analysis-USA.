⚡ EV Insights USA – Electric Vehicle Adoption & Market Analysis
An end-to-end data analytics project focused on analyzing Electric Vehicle (EV) adoption trends across the United States using Python, SQL, and Power BI. This project uncovers key insights into EV growth, regional distribution, and market patterns.
________________________________________
🔍 About This Project
With the rapid rise of electric vehicles, understanding adoption trends, state-wise performance, and market growth is critical.
However, raw EV data alone does not provide clear insights into:
•	Which states are leading EV adoption
•	How EV growth is evolving over time
•	Which vehicle types dominate the market
EV Insights USA bridges this gap by transforming raw EV data into actionable insights for decision-making.
________________________________________
📁 Raw Data Sources
The project uses EV registration datasets:
1.	EV_Registrations.csv
o	State-wise EV registration data
2.	Vehicle_Details.csv
o	Vehicle type, model, and category
3.	Energy_Consumption.csv (if applicable)
o	Energy usage and efficiency metrics
These datasets are cleaned and processed before analysis.
________________________________________
⚙️ Project Workflow (Step-by-Step)
1️⃣ Data Cleaning (Python – Jupyter Notebooks)
Each dataset is cleaned separately to ensure accuracy:
•	Handling missing values
•	Removing duplicates
•	Standardizing state names
•	Fixing data types
•	Feature engineering (year, category)
📌 Notebooks:
•	01_ev_data_cleaning.ipynb
•	02_vehicle_data_cleaning.ipynb
•	03_energy_data_cleaning.ipynb
📂 Outputs:
•	ev_cleaned.csv
•	vehicle_cleaned.csv
•	energy_cleaned.csv
________________________________________
2️⃣ Data Integration
Cleaned datasets are merged to create a unified dataset:
•	EV registrations + vehicle details
•	Combined dataset for analysis
📌 Notebook:
•	04_data_integration.ipynb
📂 Output:
•	ev_full_dataset.csv
________________________________________
3️⃣ Exploratory Data Analysis (EDA)
EDA was performed to uncover patterns such as:
•	Year-wise EV growth
•	State-wise adoption trends
•	Vehicle type distribution
•	Top-performing states
________________________________________
4️⃣ SQL Analysis
SQL was used to:
•	Calculate total EV registrations
•	Identify top states
•	Analyze yearly growth
•	Segment data by vehicle type
📂 Location:
•	/sql
________________________________________
5️⃣ Power BI Dashboard
An interactive dashboard was built to visualize:
•	Total EV registrations
•	Growth trends over time
•	State-wise distribution
•	Vehicle category analysis
📌 Report available in:
•	/reports
________________________________________
📊 Dashboard Preview
________________________________________
💡 Key Insights
•	EV adoption is rapidly increasing year over year
•	Certain states dominate EV adoption (e.g., California)
•	Passenger vehicles contribute the majority of EV sales
•	Growth is uneven across regions
________________________________________
🛠 Tools & Technologies
•	Python (Pandas, NumPy)
•	SQL
•	Power BI
•	Jupyter Notebook
•	Git & GitHub
________________________________________
📂 Repository Structure
ev-analysis-usa/
│
├── assets/
├── cleaned_data/
├── notebooks/
├── sql/
├── reports/
│
├── EV_Registrations.csv
├── Vehicle_Details.csv
├── README.md
________________________________________
🚀 Future Enhancements
•	EV demand forecasting
•	Charging infrastructure analysis
•	Cost vs adoption analysis
•	State-wise policy impact study
________________________________________
👨‍💻 Author
Akshat Maheshwari
Aspiring Data Analyst | Python | SQL | Power BI





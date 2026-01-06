🏙️ Rent Price Analysis – Istanbul

📌 Project Overview

This project analyzes rental apartment prices in Istanbul using a small, manually collected dataset sourced from sahibinden. The goal is to demonstrate a clean, end-to-end data analysis pipeline using Python — from raw data handling to statistical insights, visualization, and outlier detection.

The project is intentionally designed as a baseline analytical study, focusing on clarity, structure, and correct methodology rather than large-scale machine learning.

⸻

🎯 Objectives
	•	Clean and structure messy real-world rental data
	•	Perform descriptive and statistical analysis
	•	Engineer meaningful features (e.g. price per m²)
	•	Detect price outliers using a statistical method (IQR)
	•	Visualize rental trends using Matplotlib
	•	Export a clean dataset for further analysis

⸻

🗂️ Dataset Information
	•	Source: sahibinden (manual collection)
	•	City: Istanbul
	•	Total Apartments: 30
	•	Granularity: Apartment-level data
	•	Format: Python dictionaries → Pandas DataFrame

Key Features
	•	Price (TL)
	•	District & neighborhood
	•	Net & gross area (m²)
	•	Room count
	•	Building age
	•	Floor information
	•	Heating type
	•	Amenities (balcony, elevator, parking, site)

⚠️ Note: The dataset is intentionally small and partially expanded using controlled random variation for academic demonstration purposes.

⸻

🧰 Technologies & Libraries
	•	Python 3
	•	Pandas – data manipulation
	•	NumPy – numerical operations
	•	Matplotlib – visualization

⸻

🧼 Data Cleaning Steps
	•	Removed unrealistic values using lower bounds
	•	Normalized numerical fields (price, size, age)
	•	Converted room format (e.g. 2+1 → 3 total rooms)
	•	Ensured consistency across duplicated samples

⸻

🧠 Feature Engineering
	•	Price per m² calculation using net area
	•	Total room count derived from string format

These engineered features allow more meaningful comparisons between apartments.

⸻

📊 Analysis Performed

Descriptive Statistics
	•	Mean, minimum, maximum, and total prices
	•	Full statistical summary using describe()

Group Analysis
	•	Average rental prices by district

Outlier Detection
	•	Method: Interquartile Range (IQR)
	•	Identifies unusually low or high rental prices

⸻

📈 Visualizations
	•	Histogram: Rental price distribution
	•	Scatter Plot: Price vs net apartment area

All visualizations are created using Matplotlib for maximum transparency and control.

⸻

📁 Output
	•	Cleaned dataset exported as:

istanbul_rent_analysis.csv



This file is ready for further analysis, modeling, or reporting.

⸻

▶️ How to Run
	1.	Clone the repository
	2.	Ensure Python 3 is installed
	3.	Install required libraries:

pip install pandas numpy matplotlib


	4.	Run the script:

python rent_price_analysis.py



⸻

🚀 Future Improvements
	•	Expand dataset with real listings (1000+ rows)
	•	Add regression modeling for price prediction
	•	Encode categorical features
	•	Improve visual styling and dashboards
	•	Integrate geospatial analysis

⸻

👤 Author
Codecrafters 2nd
Programing with advanced python
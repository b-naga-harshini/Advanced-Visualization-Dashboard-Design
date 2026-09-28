# Advanced-Visualization-Dashboard-Design
Interactive Supply Chain Performance Dashboard developed using Python, Pandas, Plotly, and Streamlit. The dashboard provides interactive filters, KPI metrics, supply chain visualizations, filtered data analysis, and CSV download functionality to support data-driven supply chain analysis and decision-making.



# Week 5 – Interactive Supply Chain Performance Dashboard

## Project Overview

This project presents an interactive Supply Chain Performance Dashboard developed using Python, Pandas, Plotly, and Streamlit. The dashboard transforms supply chain data into interactive visualizations and key performance indicators for easier analysis.

## Objectives

* Develop an interactive supply chain dashboard.
* Display important supply chain KPIs.
* Provide interactive filtering capabilities.
* Visualize revenue, sales, inventory, shipping, manufacturing, transportation, and quality information.
* Allow users to view and download filtered data.

## Technologies Used

* Python
* Pandas
* Plotly
* Streamlit

## Dashboard Features

* Interactive Product Type filter
* Interactive Transportation Mode filter
* Interactive Inspection Result filter
* Interactive Supplier filter
* Total Revenue KPI
* Products Sold KPI
* Average Price KPI
* Average Defect Rate KPI
* Revenue by Product Type visualization
* Transportation Mode analysis
* Inspection Results analysis
* Price vs Revenue scatter plot
* Stock Levels vs Products Sold scatter plot
* Manufacturing Cost analysis
* Shipping Cost analysis
* Correlation Heatmap
* Filtered data table
* CSV download functionality



## Dataset

The project uses a cleaned Supply Chain dataset containing information related to products, sales, revenue, inventory, suppliers, transportation, shipping, manufacturing, inspection results, and costs.

## Project Files

```text
Week5-Interactive-Supply-Chain-Dashboard/
│
├── app.py
├── requirements.txt
├── supply_chain_data.csv
```

## How to Run the Dashboard

STEP 1 — Create one new folder

Go to:

Desktop → Right click → New → Folder

Name it:

Week5_Interactive_Dashboard

STEP 2 — Put your cleaned dataset in the folder

Find your cleaned dataset file:

supply_chain_data.csv

Copy it.

Paste it inside:

Desktop
└── Week5_Interactive_Dashboard
    └── supply_chain_data.csv

STEP 3 — Create app.py
1.Open Notepad.
2.wrie the code.
3.Notepad lo File → Save As click cheyyandi.
4.Location select cheyyandi:
Desktop → Week5_Interactive_Dashboard
5.File name:
app.py
6.Save as type: All Files (*.*)
7.Encoding: UTF-8
8.Click Save.

VERY IMPORTANT:

Week5_Interactive_Dashboard
│
├── app.py
└── supply_chain_data.csv


STEP 4 — Create requirements.txt

This file tells Python which packages your dashboard needs.

1. Open Notepad

Create a new Notepad file.

2. Paste exactly this:
streamlit
pandas
plotly
3. Save it

Go to:

File → Save As

Select:

Desktop → Week5_Interactive_Dashboard

File name:

requirements.txt

Save as type:

All Files (*.*)

Encoding:

UTF-8

Click Save.

4. Check your folder

It should now look exactly like this:

Week5_Interactive_Dashboard
│
├── app.py
├── requirements.txt
└── supply_chain_data.csv

STEP 5 — Open CMD in the correct folder

1. Type:
cmd

Then press Enter.

A CMD window will open.

2. Check the CMD path

It should end with:

cd C:\Users\VSS\Desktop\Week5_Interactive_Dashboard>

3. Check the files

4.In CMD type:

dir

Press Enter.

You should see:

app.py
requirements.txt
supply_chain_data.csv


Install the required Python packages:

```bash
python -m pip install -r requirements.txt
```

Run the Streamlit application:

```bash
python -m streamlit run app.py
```

The dashboard will open in a web browser at the local Streamlit address.

## Interactive Workflow

The dashboard follows this workflow:

**Supply Chain Dataset → Data Loading → Interactive Filters → KPI Calculation → Visualizations → Filtered Data → CSV Download**

## Project Outcome

The project demonstrates how static supply chain analysis can be transformed into an interactive dashboard using Python and Streamlit. The dashboard enables users to explore different supply chain dimensions dynamically and supports clearer data communication.

## Internship Task

**Week 5: Advanced Visualization and Interactive Dashboard Design**

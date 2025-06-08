# Electric Vehicle Data Analysis Project

## Overview

This project involves the analysis of a dataset related to electric vehicles (EVs) using Python. The dataset includes various specifications such as price, engine power, battery capacity, energy consumption, range, and other performance-related attributes. The goal is to derive meaningful insights, conduct hypothesis testing, and provide actionable recommendations for consumers and stakeholders in the EV market.

## Objectives

* Filter EVs based on user-defined conditions like budget and range.
* Group and compare manufacturers based on performance metrics.
* Detect outliers in energy consumption patterns.
* Explore the relationship between battery capacity and electric range.
* Build an EV recommendation engine using object-oriented programming.
* Perform hypothesis testing to compare manufacturers based on engine power.
* Present findings in both code and written analysis format.
* Deliver a short video explanation of the project methodology and outcomes.

## Dataset

**File:** `FEV-data-Excel.xlsx`
**Features include:**

* Car full name, Make, Model
* Price in PLN
* Engine power, Torque
* Brakes type, Drive type
* Battery capacity, Range (WLTP)
* Dimensions (length, width, height, wheelbase)
* Weight metrics (empty, gross, load capacity)
* Number of seats and doors
* Tire size, Maximum speed
* Boot capacity, Acceleration
* Maximum DC charging power
* Mean energy consumption

## Tasks

| Task No. | Description                                                                                                                  |
| -------- | ---------------------------------------------------------------------------------------------------------------------------- |
| Task 1   | Filter EVs based on budget (350,000 PLN) and range (≥ 400 km), group by manufacturer, and calculate average battery capacity |
| Task 2   | Detect outliers in energy consumption (`Mean - Energy consumption [kWh/100 km]`)                                             |
| Task 3   | Analyze the relationship between battery capacity and range using visualizations                                             |
| Task 4   | Create an EV Recommendation class to return the top 3 EVs based on user preferences                                          |
| Task 5   | Conduct a two-sample t-test to compare average engine power of Tesla and Audi vehicles                                       |
| Task 6   | Record and share a 5-minute video explaining the project, approach, and findings                                             |

## Tools Used

* Python
* Pandas, NumPy, SciPy
* Matplotlib, Seaborn
* Jupyter Notebook

## Project Structure

```
EV_Data_Analysis_Project/
├── EV_Analysis.ipynb              # Main Jupyter Notebook with analysis and explanations
├── FEV-data-Excel.xlsx            # Raw dataset
├── Project_Video_Link.md          # Markdown with Google Drive link to video explanation
└── README.md                      # Project overview and documentation
```

## Submission Guidelines

* Export the Jupyter Notebook as a PDF after completing all tasks.
* Add the video link to the notebook in a markdown cell.
* Compress the notebook file, dataset, and README into a `.zip` folder before submission.

## Evaluation Criteria

* Accuracy and clarity of the code and explanations
* Depth of statistical analysis and insights
* Structure and professionalism of the notebook and documentation
* Clarity and delivery of the video presentation

## Disclaimer

This project was completed individually, following all academic honesty and originality standards. All analysis, code, and visualizations are based solely on the given dataset and publicly available Python libraries.

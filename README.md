# Python Programming – Assignment 05 (CO5)

## Data Acquisition, Cleaning, Analysis and AI Applications

This repository contains my **Python Programming Assignment 05 – CO5**, completed as part of the B.Tech CSE (AI) course at SIMATS Engineering.

The assignment focuses on data acquisition, data cleaning, data normalisation, database management, data analysis, visualisation, debugging, performance profiling, and AI applications using Python.

---

## Student Details

| Field | Details |
|---|---|
| Name | W. Mohammed Fardeem |
| Register Number | 1972260009 |
| Course Code | CSA0824 |
| Course Name | Python Programming |
| Class Slot | D |
| Assignment | Assignment 05 – CO5 |
| Institution | SIMATS Engineering |

---

## Assignment Overview

**Topic:** Data Acquisition, Cleaning, Analysis and AI Applications.

This assignment consists of two parts:

- **Part A:** Design and planning tasks (A1–A5)
- **Part B:** Implementation and engineering tasks (B1–B4)

A total of nine tasks demonstrate practical Python programming techniques for analysing air-quality monitoring data and developing citizen complaint analysis applications.

## Tasks Included

### Part A – Design and Planning

#### Task A1 – Design the Data Acquisition
- Inspect and organise air-quality monitoring data.
- Design a relational SQLite database schema.
- Create station and readings tables.
- Understand CSV scanning versus SQL querying.
- Use primary keys, foreign keys, constraints, and indexes.

#### Task A2 – Design the Cleaning and Normalisation
- Remove duplicate records.
- Handle missing and invalid sensor readings.
- Convert Fahrenheit temperatures into Celsius.
- Replace missing values using median imputation.
- Apply Min-Max normalisation and Z-Score standardisation.

#### Task A3 – Design the Analysis and Visualisation
- Select suitable charts for air-quality analysis.
- Use line charts, bar charts, scatter plots, and box plots.
- Generate daily summary tables using SQL aggregation.
- Analyse minimum, maximum, and average PM2.5 values.

#### Task A4 – Plan Debugging and Profiling
- Implement structured logging.
- Use assertions to validate data.
- Measure execution time using `perf_counter`.
- Perform micro-benchmarking with `timeit`.
- Analyse program performance using `cProfile`.

#### Task A5 – Design an AI Application for Citizen Complaints
- Develop a basic sentiment analysis system.
- Handle positive and negative words using a lexicon.
- Apply negation handling.
- Generate extractive text summaries.
- Create a rule-based air-quality chatbot.

### Part B – Implementation and Engineering

#### Task B1 – Implement and Validate the Cleaning Pipeline
- Read CSV data using `csv.DictReader`.
- Remove empty, missing, and invalid readings.
- Apply Min-Max scaling.
- Store cleaned records in SQLite.
- Verify station averages using SQL queries.

#### Task B2 – Engineer Adversarial Data
- Insert records using parameterised SQL queries.
- Use `executemany()` for bulk insertion.
- Protect database queries against SQL injection.
- Validate empty CSV files.
- Detect incorrect delimiters and missing columns.

#### Task B3 – Loops vs Libraries vs SQL
- Compare Python loops, running dictionaries, and SQL aggregation.
- Check the correctness of all three approaches.
- Benchmark different dataset sizes.
- Measure execution time using `perf_counter`.
- Investigate performance using `cProfile`.

#### Task B4 – Final Engineering Decision
- Implement a sentiment scoring system.
- Classify citizen complaints as positive, negative, or neutral.
- Handle negation in sentiment analysis.
- Benchmark indexed and non-indexed SQL queries.
- Evaluate query performance using a composite index.

---

## Technologies Used

| Technology | Purpose |
|---|---|
| Python | Main programming language |
| SQLite3 | Database creation and querying |
| CSV | Reading and processing structured data |
| Statistics | Median, mean, and standard deviation |
| Collections | Data organisation and frequency analysis |
| Logging | Error tracking and debugging |
| Time / Timeit | Performance measurement |
| cProfile | Performance profiling |
| Regular Expressions | Text processing |

## Key Concepts Covered

- Data acquisition and inspection
- Data cleaning and preprocessing
- Missing-value handling
- Data normalisation and standardisation
- SQLite database management
- SQL queries and indexing
- Data aggregation and analysis
- Data visualisation planning
- Logging and debugging
- Performance benchmarking
- Sentiment analysis
- Text summarisation
- Rule-based chatbot development
- SQL injection protection

## Learning Outcomes

Through this assignment, I learned how to:

1. Acquire and inspect structured datasets.
2. Clean and normalise real-world data.
3. Handle missing, duplicate, and invalid records.
4. Create and manage SQLite databases.
5. Perform analytical queries using SQL.
6. Compare different data-processing approaches.
7. Debug and profile Python applications.
8. Develop basic AI-based text analysis applications.
9. Build reliable and efficient data-processing solutions.

---

## How to Run

**Requirements:**
- Python 3.x
- Visual Studio Code or any Python IDE
- SQLite3 (included with standard Python installations)

**Steps:**

1. Clone the repository:

```bash
git clone https://github.com/mohammedfardeem2532-tech/CSA0824_1972260009_ASSIGNMENT5.git
```

2. Open the downloaded folder in Visual Studio Code.

3. Open the required Python task file.

4. Run the program using:

```bash
python main.py
```

**Note:** Each task can be executed separately. Run the corresponding code for the task you want to test.

---

## GitHub Repository

**Repository:** [Python Programming – Assignment 05 (CO5)](https://github.com/mohammedfardeem2532-tech/CSA0824_1972260009_ASSIGNMENT5.git)

---

## Conclusion

This assignment provided practical experience in data acquisition, cleaning, analysis, database management, performance optimisation, and basic AI application development using Python. It helped strengthen my understanding of how Python can be applied to real-world data engineering and citizen complaint analysis.

---

**Submitted by:** W. Mohammed Fardeem  
**Register Number:** 1972260009  
**Course:** B.Tech CSE (AI)  
**Institution:** SIMATS Engineering# CSA0824_1972260009_ASSIGNMENT5

# 🎂 Smart Age Calculator & Profiling System (OOP)

An object-oriented Python command-line application built to process user profiles based on chronological data. Developed as an advanced project with the **Satar (سطر) Platform**, this engine ingests multi-line registration strings, parses and validates date formats, determines historical days of the week, and evaluates population structures to isolate extreme age profiles (the oldest and youngest individuals).

---

## 📂 Project Assets & Structure

* 💻 **[View Core Code Notebook](./main.ipynb)** – Interactive Jupyter Notebook containing the full implementation of the `Person` class, logic loops, and date parsing routines.
* 📋 **Project Criteria:** Fulfills core and extended algorithmic challenges, including dynamic data sorting and specific date matching constraints.

---

## 🛠️ Tech Stack & OOP Concepts

* **Programming Language:** Python 🐍
* **Object-Oriented Programming (OOP):** Encapsulating demographic attributes inside a dedicated `Person` class blueprint with decoupled instance methodologies.
* **Core Libraries:** `datetime` module utilized for structural string-to-date parsing (`strptime`), current time extraction, and customized locale day string transformations (`strftime`).
* **Robust Error Handling:** Active `try-except` blocks intercepting formatting anomalies (`ValueError`) to guarantee execution stability when facing malformed strings.

---

## 🚀 Application Pipeline & Workflow

The system triggers an active loop accepting string configurations (`Name, DD-MM-YYYY`) and coordinates tasks across distinct structural blocks:

### 1. Data Ingestion & Blueprint Instantiation
* Splits strings into distinct text variables and passes them to instantiate a `Person` object.
* Converts birthdate configurations into continuous date matrices:
  $$\text{self.date} = \text{datetime.strptime}(\text{date}, \text{"\%d-\%m-\%Y"})$$

### 2. Analytical Instance Methods
* **Age Calculation (`calculate_age`):** Compares the target birth year parameter against the system's runtime calendar clock to return active chronological intervals.
* **Day-of-Week Extraction (`get_weekday_name`):** Extracts structural text outputs (e.g., "Sunday", "Wednesday") tracking the precise historical calendar day of birth.

### 3. Population Aggregation Logic
* Keeps a running tally of entries and processes arrays to dynamically isolate the **Oldest** and **Youngest** entities via Python's built-in `max()` and `min()` lambda keys.
* **Extended Task Metric:** Triggers automated matching to track and print all profiles whose birthdays occurred specifically on a **Sunday**.

---

## 👤 Developed by:
* **Nada Alaklook**
* 🔗 [Connect with me on LinkedIn](https://linkedin.com/in/nada-alaklook-725049252)

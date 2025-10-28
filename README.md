# 🚐 Kasi Transport Tracker

###  Project Overview

Kasi Transport Tracker is a Python-based application designed to help local taxi drivers and route managers efficiently manage daily operations.
It allows users to register drivers, add routes, record trips, generate daily reports, and identify top-earning drivers.
The system is aimed at improving accountability, transparency, and data-driven decision-making in township transport management.


### 🎯 Features

* **Driver Registration:** Add and manage driver information easily.
* **Route Management:** Create and update taxi routes with origin, destination, and fare details.
* **Trip Recording:** Log daily trips with passenger counts and fares.
* **Daily Reports:** View and export detailed reports (CSV format) of daily earnings and trips.
* **Search Function:** Find drivers or routes quickly using keywords.
* **Top-Earning Driver:** Identify the highest-earning driver of the day.
* **Interactive Menu:** Simple, emoji-enhanced interface for better user experience.


### 🧠 Tech Stack

* **Language:** Python 3
* **Database:** PostgreSQL / SQLite (depending on setup in `db_setup.py`)
* **Libraries Used:**

  * `csv` – for exporting reports
  * `datetime` – for managing dates
  * Custom `db_setup.py` – for database creation and queries


### ⚙️ Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/maneliaugust/Kasi-Transport-Tracker-.git
   cd kasi-transport-tracker
   ```

2. Install dependencies (if any):

   ```bash
   pip install psycopg2
   ```

3. Ensure your database is set up properly in **db_setup.py**.

4. Run the application:

   ```bash
   python transport_app.py
   ```


### 📊 Example Features in Action

**Main Menu:**

```
========== MAIN MENU ==========
1. Add Driver 🚐
2. Add Route 🛣️
3. Record Trip 📝
4. Daily Report 📊
5. Search Drivers 🔍
6. Search Routes 🗺️
7. Top Earning Driver 🏆
8. Exit ❌
================================
```

**Sample Output:**

```
📊 Daily Report for 2025-10-28
Driver Name     Taxi No.    Route               Trips   Total (R)
---------------------------------------------------------------
Manelisi         MJ145GP     Tembisa→Jozi      1      25.50.00
```

* **Manelisi Ncwaba** – Data Science Intern

# Database Information

This project uses a SQLite3 database to store airline performance data.

## 📦 Database File
- Format: SQLite3
- File size: ~110 MB
- The database file is intentionally **not included** in this repository due to GitHub file size limitations.

## 🧾 Reason for Exclusion
- GitHub has a 100 MB file size limit per file
- Large database files are not suitable for version control
- Including the database would negatively impact repository performance

## 🛠️ How the Database Is Used
- Connected using Python's built-in `sqlite3` module
- SQL queries are executed inside the Jupyter Notebook
- Query results are loaded into Pandas DataFrames for analysis

## 🧠 Tables & Schema (Example)
- `flights`
- `airlines`
- `airports`

*(Refer to the notebook for exact table structure and queries)*

## 🧪 Reproducibility
To reproduce this analysis:
- Use any airline dataset with a similar schema
- Create a SQLite database locally
- Update the database path in the notebook

## 📌 Note
All SQL queries used in this project are available inside the notebook.


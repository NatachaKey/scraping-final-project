
# ⚾️ Scraping-Final-Project

## MLB Almanac Dashboard

An interactive **Streamlit** dashboard to explore **MLB historical player statistics (1876–2025)**.

---

### 🔍 Features

#### 📊 Visualizations:

* **Bar Chart** – Top players by selected stat
* **Pie Chart** – Team distribution among top players
* **Line Chart** – Stat trends over time

#### 🎛 Controls:

* **Dropdown** – Choose a statistic
* **Slider** – Set number of top players
* **Year Range Selector** – Filter by season span

#### 📂 Data Source:

* **150+ CSV files** cleaned and imported into a **SQLite** database

---

### ▶️ How to Run

```bash
pip install -r requirements.txt  
streamlit run dashboard.py
```

---

### 📦 Project Files

| File/Folder       | Description                                  |
| ----------------- | -------------------------------------------- |
| `import_to_db.py` | Cleans and loads CSVs into a SQLite database |
| `query_tool.py`   | CLI for database queries                     |
| `dashboard.py`    | Main Streamlit dashboard app                 |
| `data/raw/`       | Folder for raw CSV files                     |
| `mlb_almanac.db`  | Generated SQLite database                    |

---

### 🚀 Deployment

Easily deployable to [Streamlit.io](https://streamlit.io/) or [Render.com](https://render.com/) for public access.



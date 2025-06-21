````markdown
# 📱 Real-Time Google Play Store Data Analytics – Python Project

A data analytics project that leverages **Python, Pandas, Matplotlib, and TextBlob** to extract insights from the Google Play Store dataset. This project is part of the **NullClass Data Analyst Internship** and includes three tasks focusing on business-critical app metrics and visualization.

---

## 📂 Dataset
Dataset used: [Google Play Store Apps Data (Kaggle)](https://www.kaggle.com/datasets/lava18/google-play-store-apps)  
File: `googleplaystore.csv`

---

## 🚀 Project Features

### ✅ Task 1: Scatter Plot – Revenue vs Installs (Paid Apps Only)
- Filters for paid apps only
- Calculates **revenue = price × installs**
- Plots a scatter plot of **installs vs revenue**
- Adds a **trendline** and color-codes by app category

### ✅ Task 2: Grouped Bar Chart – Avg Rating & Total Reviews
- Compares **average rating** and **total reviews** for the **top 10 app categories** by installs
- Filters:
  - Rating ≥ 4.0
  - App size ≥ 10 MB
  - Last updated in January
- ⏰ **Time-sensitive**: Graph only visible between **3 PM – 5 PM IST**

### ✅ Task 3: Bubble Chart – Size vs Rating (with Install-Based Bubbles)
- Filters for:
  - Rating > 3.5
  - Category in: Game, Beauty, Business, Comics, Communication, Dating, Entertainment, Social, Event
  - Reviews > 500
  - App name should **not** contain the letter `'S'`
  - Subjectivity (TextBlob) > 0.5
  - Installs > 50,000
- Translates category labels:
  - Beauty → **Hindi**
  - Business → **Tamil**
  - Dating → **German**
- Highlights **Game** category in **pink**
- ⏰ **Time-sensitive**: Graph only visible between **5 PM – 7 PM IST**

---

## 🧰 Tech Stack

| Tool / Library    | Purpose                        |
|-------------------|--------------------------------|
| `pandas`          | Data cleaning & transformation |
| `matplotlib`      | Visualization                  |
| `seaborn`         | Additional plots               |
| `textblob`        | Sentiment subjectivity         |
| `pytz` & `datetime` | Time-based filtering         |

---

## 🧪 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/google-play-analytics.git
   cd google-play-analytics
````

2. Install dependencies:

   ```bash
   pip install -r requirements.txt
   ```

3. Launch Jupyter Notebook:

   ```bash
   jupyter notebook
   ```

4. Run the file: `playstore_analysis.ipynb`

---

## 📎 File Structure

```
├── googleplaystore.csv
├── playstore_analysis.ipynb
├── requirements.txt
└── README.md
```

---


## 🏁 Outcome

✔️ Successfully implemented real-time visualizations
✔️ Filtered datasets with complex logical conditions
✔️ Practiced data storytelling through visual insights
✔️ Demonstrated internship-level skills in data analytics

---

## 📜 License

This project is for educational and internship purposes under the NullClass Data Analyst Internship Program.

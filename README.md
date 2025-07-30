# Titanic Analytics Dashboard 🚢

## 📌 Overview
This Advanced Titanic Analytics Dashboard is a comprehensive data visualization and exploration tool built with Python's Tkinter GUI library and Matplotlib for interactive charts. It allows users to analyze the Titanic passenger dataset with dynamic filtering, statistical insights, and export capabilities.


## ✨ Key Features
### 📊 Interactive Visualizations
- Survival Rate Analysis (pie charts, bar graphs)

- Age & Fare Distribution (histograms, box plots, scatter plots)

- Class & Gender Comparisons (grouped bar charts)

- Correlation Heatmap (numeric feature relationships)

### 🔍 Dynamic Filtering
- Filter by Passenger Class (1st, 2nd, 3rd)

- Filter by Gender (Male/Female)

- Adjustable Age Range Slider

### 📂 Data Exploration
- Searchable Data Table (real-time filtering)

- Export Filtered Data (save as CSV)

### 🎨 Modern UI
- Dark-themed dashboard with responsive layout

- Custom color schemes for better readability


## 📊 Insights from the Data
### 1️⃣ Survival Rate Analysis
- 1st Class passengers had the highest survival rate, while 3rd Class had the lowest.

- Female passengers survived at a significantly higher rate than males.

- Children (< 10 years) had better survival odds due to "women and children first" policy.

### 2️⃣ Age & Fare Trends
- Higher fare-paying passengers (typically 1st Class) had better survival rates.

- Age distribution shows two peaks: young adults (~20-30) and children (< 10).

### 3️⃣ Embarkation Port Impact
- Cherbourg (C) passengers had the highest survival rate, possibly due to a higher proportion of 1st Class passengers.

### 4️⃣ Correlation Findings
- Fare and Survival show a positive correlation (higher fare = better survival odds).

- Pclass (Passenger Class) and Survival show a strong negative correlation (lower class = lower survival).

## 🛠️ Tech Stack

| Library | Purpose |
|--------|---------|
| `tkinter` | GUI creation |
| `pandas` | Data manipulation |
| `numpy` | Numerical operations |
| `matplotlib` | Data visualization |
| `ttk` | Styled widgets for better UI |
| `filedialog`, `messagebox` | File and message interactions |


## 🚀 Installation & Usage
### Prerequisites
- Python 3.6+

- Required libraries:
  ```bash```
```pip install matplotlib pandas numpy```

### How to Run
1. Download train.csv (Titanic dataset) and place it in the project folder.
2. Run the dashboard:
```python main2.py```

### Controls
- Filter Data: Use dropdowns and sliders in the Overview tab.

- Advanced Analysis: Click buttons in the Analysis tab.

- Search & Export: Use the Data tab to explore and save data.























































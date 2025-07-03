# 🎮 Video Game Sales Analysis Dashboard

##  Overview  
This repository contains an interactive **Power BI dashboard** that explores global video game sales data. The dashboard offers insights into trends across genres, platforms, publishers, and regions, helping users better understand the gaming industry and its evolution over time.

---

##  Dataset  
The data comes from the well-known `vgsales.csv` dataset, which includes global and regional sales figures for video games. Key fields:

- `Name`: Game title  
- `Platform`: Console/platform (e.g., PS4, X360)  
- `Genre`: Game genre (e.g., Action, RPG, Sports)  
- `Publisher`: Game publisher  
- `Year`: Release year  
- `Global_Sales`: Total worldwide sales (in millions)  
- `NA_Sales`, `EU_Sales`, `JP_Sales`, `Other_Sales`: Regional breakdowns  

 Data Source: Kaggle 

---

##  Dashboard Features  

### 1. **Global Sales by Genre**  
Bar chart showing which genres generate the most revenue worldwide.

### 2. **Regional Sales by Publisher**  
Stacked bar chart comparing publisher performance in different regions.

### 3. **Platform Sales Share**  
Pie chart showing which platforms dominate in terms of total sales.

### 4. **Sales Over Time**  
Line chart visualizing global sales trends by release year.

![image](https://github.com/user-attachments/assets/7846cf31-3c44-4249-baf6-8e54eaf8f9cc)

##  Getting Started  

### 1. Clone this repository  
```bash
git clone https://github.com/yoshinyee/vgame.git
cd video-game-sales-analysis
```

### 2. Open the Power BI file  
- Download **Power BI Desktop** (free from [Microsoft](https://powerbi.microsoft.com/desktop/))  
- Open `vgsales_dashboard.pbix` from the `dashboard/` folder  

### 3. Explore  
Use the filters, view the charts, and explore different sales dimensions.

---

## 📁 Folder Structure  

```
video-game-sales-analysis/
├── dashboard/
│   └── vgsales_dashboard.pbix     # Power BI dashboard file
├── data/
│   └── vgsales.csv                # Raw video game sales dataset
├── images
│   
└── README.md                      # This file
```

---

## 🛠 Tools Used  

- **Power BI Desktop** — for building the visuals  

---
## 📄 License  
MIT License © 2025

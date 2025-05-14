

# 🚍 Hydrogen vs. Battery Electric Buses – A Comparative Cost Analysis for Public Transport

This project explores the economic and environmental implications of using **Hydrogen Fuel Cell Buses** versus **Battery Electric Buses (BEBs)** for public transportation.

---

## 📌 Objective

To provide a **comparative cost analysis** between hydrogen and battery electric buses using real-world datasets, focusing on:

- Initial purchase cost 💰
- Cost per kilometer of operation 🚏
- Health impacts due to PM2.5 pollution 🌫️
- Electric vehicle adoption trends 🔋

---

Due to the limited availability of public datasets comparing hydrogen vs. electric buses, I constructed a sample dataset using:

Estimated market values

Published research insights

Logical assumptions based on real-world trends

The dataset includes:

Annual deaths due to PM2.5 (2008–2019)

Electric vehicle sales (2012–2024)

Initial cost of various vehicle types

Cost per kilometer of operation for each type


---

## 📊 Charts & Visuals

| Chart | Description |
|-------|-------------|
| **Chart 1** | Deaths attributable to PM2.5 exposure (2008–2019) |
 ![Screenshot 2025-05-14 063836](https://github.com/user-attachments/assets/3f14c1ee-bb1f-4c55-bcb0-a0734fea806d)

 
 
| **Chart 2** | Electric vehicle sales trends (2012–2024) |
![Screenshot 2025-05-14 063934](https://github.com/user-attachments/assets/d388f8d6-f363-46a3-ba09-acb4a53a4776)

| **Chart 3** | Initial cost comparison of different vehicle types |
![Screenshot 2025-05-14 063946](https://github.com/user-attachments/assets/558a274d-794c-4372-9b82-1915295ff76c)

| **Chart 4** | Cost per kilometer comparison for hydrogen, electric, diesel, and hybrid buses |
![Screenshot 2025-05-14 064001](https://github.com/user-attachments/assets/091e81f2-d589-431b-aa32-2a9204efd5e4)

All charts were built using **Matplotlib** with customized labels, grids, and color schemes.

---

## 🧹 Data Cleaning & Analysis

- Removed missing values and handled inconsistent units
- Merged and aligned datasets by year and vehicle type
- Applied simple statistical summaries to compare vehicle types

---

## 💡 Key Insights

- **Electric buses** have the lowest operational cost per km.
- **Hydrogen buses** are more expensive initially but could scale with infrastructure.
- PM2.5-related deaths have shown gradual decline, correlating with increased EV adoption.
- From 2012 to 2024, EV sales surged globally, highlighting a policy and market shift.

---

## 🛠️ Technologies Used

- **Python 3**
- **Pandas** for data wrangling
- **Matplotlib** for visualization
- **Jupyter Notebook** for code and storytelling

---

## 🧠 Skills Demonstrated

- Exploratory Data Analysis (EDA)
- Data cleaning and merging
- Cost-benefit analysis
- Data visualization and communication
- Environmental policy implications

---

## 🎯 Next Steps for the Future

- Add Total Cost of Ownership (TCO) over 5–10 years
- Deploy a Streamlit dashboard for interactive analysis
- Forecast future trends using linear regression






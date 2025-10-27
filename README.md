# 🚗 Uber Data Analysis — Exploratory Data Insights using Python
This project analyzes Uber ride booking data to uncover key patterns in user behavior such as the most popular ride categories, booking times, and ride distances. The analysis was performed in Jupyter Notebook using Python, leveraging libraries like Pandas, NumPy, Matplotlib, and Seaborn.

# 📊 Objective
Suppose you work as a Data Analyst at Uber, and you’re asked to answer the following business questions based on ride booking data:

1. In which category do people book the most Uber rides?
2. For which purpose do people book Uber rides the most?
3. At what time of day do people book cabs the most?
4. In which months do people book Uber rides less frequently?
5. On which days of the week do people book Uber rides the most?
6. How many miles do people usually travel when booking an Uber?

# 🧰 Tech Stack
**Python**

**Pandas** - for data wrangling and analysis\
**NumPy** — for numerical computation\
**Matplotlib & Seaborn** — for visualization\
**Jupyter Notebook** — for coding and analysis

## ⚙️ Project Workflow

### 1. Data Loading and Exploration
The dataset was imported and inspected for missing values, duplicates, and inconsistent data types.  
Key columns included:
- **START_DATE**, **END_DATE**  
- **CATEGORY** (e.g., Business, Personal)  
- **PURPOSE** (e.g., Meetings, Meals, Errands)  
- **MILES** (distance traveled)  
- **START** & **STOP** locations  

### 2. Data Preprocessing
- Converted date columns to proper datetime format.  
- Extracted **month**, **day of the week**, and **hour** from the booking timestamp.  
- Cleaned missing values in the **PURPOSE** column.  

---

## 📈 Data Analysis and Insights

### 1️⃣ Category with Most Uber Rides
**Insight:** The **Business** category had the highest number of rides booked.  
**Reasoning:** This suggests Uber is widely used by employees for work-related travel or company reimbursements.  

---

### 2️⃣ Most Common Purpose for Uber Rides
**Insight:** The most frequent purpose was **Meeting**, followed by **Meals/Entertainment**.  
**Reasoning:** This implies professionals often rely on Uber for attending client or team meetings and social outings.  

> *(Questions 1 and 2 were visualized together in one subplot for comparison.)*

---

### 3️⃣ Time of Day When People Book the Most Rides
**Insight:** Most bookings happen during **morning (7–9 AM)** and **evening (5–7 PM)** hours.  
**Reasoning:** These peaks align with office commute times, showing strong weekday travel trends.  

---

### 4️⃣ Months with Lowest Ride Bookings
**Insight:** The least rides were booked in **January** and **December**.  
**Reasoning:** Possible reasons include holidays, vacations, and fewer work commitments during winter months.  

---

### 5️⃣ Most Popular Days for Uber Bookings
**Insight:** **Thursday** and **Friday** showed the highest number of rides, while **Sunday** was the lowest.  
**Reasoning:** The end of the workweek likely sees increased movement — business meetings, social outings, or weekend travel.  

---

### 6️⃣ Average Distance (Miles) per Booking
**Insight:** Most rides were within **2–10 miles**, with a right-skewed distribution indicating a few long trips.  
**Reasoning:** This shows Uber is mainly used for **short intra-city rides** rather than long-distance travel.  

---

## 📊 Visualizations

- Bar charts and count plots for categorical comparisons  
- Line plots for monthly trends  
- Box plots and histograms for distance distribution  
- Combined subplots for compact, comparative analysis  

---

## 💡 Key Takeaways

- Business-related rides dominate overall Uber usage.  
- Meeting-related trips are the top purpose for booking.  
- Commute hours show peak demand.  
- Early-year months see less activity.  
- End-of-week days show higher engagement.  
- Most rides are short-distance urban trips.  


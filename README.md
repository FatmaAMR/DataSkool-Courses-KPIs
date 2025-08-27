# Courses Data Analysis & Dashboard Project

## 📌 Project Overview
This project focuses on analyzing a dataset of online courses to extract meaningful insights about **subjects distribution, pricing models, difficulty levels, engagement trends, and revenue proxies**.  
The analysis was conducted using Python (Pandas, NumPy, Matplotlib, Seaborn) and the results were visualized in an **interactive dashboard** for better understanding.  

The aim is to explore how different factors (price, subject, difficulty, duration, lectures) affect **student enrollment, engagement, and potential profitability**.  

---

## Dataset Description
The dataset spans **6 years and 3 months (2011–2017)** and contains **3,667 unique courses** (after removing duplicates).  

### Features:
- **Course Id** → Unique identifier for each course  
- **Course-Title** → Title of the course  
- **Is Paid** → Indicates whether the course is Free or Paid  
- **Level** → Difficulty level of the course (Beginner, Intermediate, Expert, All Levels)  
- **Published Date** → Date when the course was published  
- **Pulished Timestamp** → Unix timestamp of the published date  
- **Subject** → Main subject area (Web Development, Business Finance, Graphic Design, Musical Instruments)  
- **URL1** → Course link  
- **CONTENT DURATION in HR's** → Duration of the course in hours  
- **Num Lectures** → Number of lectures included in the course  
- **Price** → Price of the course (if paid)  
- **Reviews** → Number of reviews received  
- **Students** → Number of students enrolled  

---

## Key Insights
- **Subjects Distribution**:  
  - Web Development (32.7%) and Business Finance (32.5%) dominate the dataset.  
  - Graphic Design (16.4%) and Musical Instruments (18.4%) are smaller but notable.
  - 
- **Difficulty Levels**:  
  - 52% are "All Levels" courses.  
  - 35% Beginner, 11% Intermediate, and only 1.6% Expert.  

- **Pricing**:  
  - 91.5% of courses are **Paid**, while just 8.4% are Free.  
  - Despite price variations, students still prefer **paid courses**.  


- **Time Trends**:  
  - Number of published courses peaked in **2015–2016**, then declined in 2017.  

- **Engagement**:  
  - Review-to-student ratio is relatively low, meaning **few students leave feedback**.  

- **Revenue Estimates (Price × Students)**:  
  - **Web Development** and **Business Finance** are the most profitable categories.  

- **Content Structure**:  
  - Course duration (hours) is positively correlated with number of lectures,  
    but correlation with number of students is weak.  

---

## Dashboard
An **interactive dashboard** was created to visualize:  
- Courses distribution by subject  
- Trends over time  
- Free vs Paid courses  
- Difficulty levels  
- Estimated revenues  
- Student engagement metrics  

<img width="1015" height="554" alt="image" src="https://github.com/user-attachments/assets/0eb503b0-67e5-48dd-ada0-d94c5dc33d0a" />

---

## Tech Stack
- **Python**: Pandas, NumPy, Matplotlib, Seaborn  
- **Data Cleaning & EDA**: Jupyter Notebook  
- **Dashboard**: Power BI

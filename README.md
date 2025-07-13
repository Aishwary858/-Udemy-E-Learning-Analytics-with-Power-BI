# 📘 E-Learning Courses Analytics – Power BI Project

This Power BI project analyzes Udemy's online course data to derive insights into course popularity, pricing trends, content duration, and learner preferences across different subjects and difficulty levels. It is designed to help stakeholders make data-driven decisions in the online education space.

---

## 🔍 Project Overview

The objective of this project is to explore and visualize Udemy’s course metadata using Power BI. Key insights include:

- Course popularity by subject and level
- Average pricing and revenue patterns
- Content duration by subject
- User review trends
- Paid vs. Free course distributions

---

## 🧾 Dataset Information

The dataset includes information on 3,678 Udemy courses and contains the following columns:

| Column Name       | Description |
|-------------------|-------------|
| `course_id`       | Unique ID for each course |
| `course_title`    | Title of the course as listed on Udemy |
| `url`             | Link to the course |
| `is_paid`         | Whether the course is free or paid |
| `price`           | Course price in USD |
| `num_subscribers` | Total number of subscribers |
| `num_reviews`     | Total number of reviews |
| `num_lectures`    | Total lectures in the course |
| `level`           | Difficulty level (Beginner, Intermediate, Expert) |
| `subject`         | Subject category of the course |

---

## 📊 Key Metrics

- **Total Courses:** 3,678  
- **Total Subscribers:** 12 Million+  
- **Total Reviews:** 575,000+  
- **Average Price:** $72  
- **Total Content Duration:** 16,000+ hours  
- **Average Lectures per Course:** 40  

---

## 📈 Visualizations

1. **Courses by Subject:** Bar chart showing the count of courses per subject  
2. **Subscribers by Subject:** Column chart showing subscribers per subject  
3. **Revenue Insights:**
   - Average price per subject
   - Estimated revenue = price × subscribers  
4. **Review Analysis:**
   - Avg. reviews per course level
   - Monthly trend of reviews  
5. **Content Duration Analysis:**
   - Donut chart of content hours by subject  
6. **Free vs. Paid Comparison:**
   - Clustered bar chart comparing free vs. paid course distribution  

---

## 🧠 Key Insights

- **Web Development** is the most popular and revenue-generating subject.
- Most courses are **Beginner Level**, with high reach and engagement.
- Price ranges from **Free to $200**, indicating a wide monetization strategy.
- Subscriber growth increased until 2016, followed by a decline.

---

## 🚀 Future Enhancements

1. **Course Completion Rate** – To measure user engagement.  
2. **Instructor-Level Analysis** – Identify high-performing instructors.  
3. **Dynamic Price Trends** – Track pricing evolution over time.  
4. **Regional Trends** – Use geographic data for location-based insights.  

---

## 🛠️ Tools Used

- **Power BI** – Visualization, dashboarding  
- **Power Query** – Data cleaning and transformation  
- **DAX** – KPI metrics and calculated columns  
- **CSV Dataset** – (from Udemy course listings)

---



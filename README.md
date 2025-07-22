# 🍽️ Zomato Bangalore - Exploratory Data Analysis

This project explores restaurant data from Zomato (Bangalore) to extract meaningful business insights using data cleaning, visualization, and pattern analysis.

---

## 📊 Objective

To understand:

- How various factors like service type, cuisine, and cost influence ratings.
- Customer preferences and market trends in Bangalore’s food industry.
- Strategic insights that Zomato or restaurant owners can use to improve service.

---

## 🧹 Data Preprocessing Highlights

- Removed null values and invalid entries.
- Normalized rating (`rate`) columns.
- Cleaned columns like `approx_cost`, `cuisines`, and `rest_type`.
- Categorical encoding where necessary.

---

## 📈 Exploratory Visualizations

### 1️⃣ Online Order vs Rating (Violin Plot)
Shows the distribution of ratings for restaurants that offer or don’t offer online ordering.

### 2️⃣ Service Type vs Rating (Boxplot)
Compares average ratings across different service types (`rest_type`), such as Casual Dining, Cafes, etc.

### 3️⃣ Cuisines vs Rating (Bar Plot)
Top 15 cuisines by average rating – helps identify popular cuisine choices.

### 4️⃣ Cost vs Rating (KDE Plot)
Shows the density distribution between approximate cost for two and restaurant ratings.

### 5️⃣ Correlation Heatmap
Displays correlation between numerical features like cost, votes, rating, etc.

---

## 💡 Business Insights

- **Online ordering** is associated with slightly higher ratings.
- **Casual Dining** and **Quick Bites** dominate the market in both presence and ratings.
- **North Indian**, **Chinese**, and **South Indian** cuisines are among the highest rated.
- Restaurants with **moderate to premium pricing** tend to receive higher ratings than the cheapest ones.
- Enabling **table booking** may positively influence customer satisfaction.

---

## 🚀 Future Scope

- 📝 **Text Mining:** Analyze customer reviews using NLP techniques.
- 🗺️ **Geo Visualization:** Integrate location data with Folium or Plotly for spatial analysis.
- 📊 **Clustering:** Group restaurants based on rating, cost, and cuisine for targeted marketing.

---

---

## 📁 Project Structure

Zomato_Bangalore_EDA/
│
├── Zomato_Bangalore_EDA.ipynb # Main analysis notebook
├── zomato.csv # Cleaned dataset
├── plots/ # Output plots
│ ├── violin_plot.png
│ ├── boxplot_service.png
│ ├── heatmap.png
│ └── kde_cost_rating.png
└── README.md


---

## 🙋‍♂️ Connect with Me

**Aryan Raj**  
📧 [Your Email]  
🔗 [LinkedIn](https://www.linkedin.com/in/aryanraj1121)  
💻 [GitHub](https://github.com/ARYANRAJ1121)

---

⭐ *If you liked this project, give it a star and share it with your friends!*


# Prediction-of-Product-Sales

This project is part of a data science portfolio aimed at showcasing skills and competencies to potential employers. The focus of this project is on predicting sales for food items sold at various stores. 
  - From the product side, factors such as fat content, item type, visibilit, and product weight are analyzed to understand their influence on sales.
  - From the outlet side, attributes like outlet size, location, and type are considered to capture differences in consumer behavior across different store settings.
By combining these two dimensions, the project provides insights into what drives higher sales and offers a tool to forecast sales more accurately.

**📌The goal:📝**
---
helping retailers understand which product and outlet properties play a crucial role in increasing sales

**📌Data and Methods:✅**
---
- Dataset: ~8,500 records of food items sold across 4 different stores.
  - "Includes product information (fat content, type, visibility, etc.) and outlet details (size, type, location)."
- Main steps taken:
  - Data cleaning (handling missing values and fixed inconsistencies)
  - Exploratory analysis (understanding trends and patterns)

**📌Plots & Insights📊**
---
***Who dominates the sales market ?***

<img width="635" height="453" alt="donut plot" src="https://github.com/user-attachments/assets/28f60d0e-f24b-412f-8317-8bbcba52b39a" />

- **💡Findings**

    - Majority of sales come from Supermarket Type1.
    - Grocery Stores contribute the least to total sales.
    - Larger supermarkets dominate sales due to higher customer traffic and wider product variety.
---
***Which product types sell better depending on fat content ?***

<img width="850" height="601" alt="bar plot" src="https://github.com/user-attachments/assets/c421db21-0f48-455b-b1a0-d84e10f18d1d" />

- **💡Findings**
    - Dominant Product Categories

        - Fruits and Vegetables, Snack Foods, and Frozen Foods show the highest total sales across all categories.

        - Breakfast, Seafood, and Starchy Foods show the lowest sales overall.

    - Low Fat vs. Regular Sales

        - In most categories, Low Fat products dominate (e.g.,Snack Foods, Fruits & Vegetables).

        - Regular fat products lead significantly in Soft Drinks and Hard Drinks.

        - Categories like Meat and Breakfast are more balanced but slightly inclined toward Regular.
    - Consumer Preference
        - Customers clearly prefer Low Fat options in food-related items (Dairy, Frozen Foods, Fruits & Vegetables, Snack Foods).
        - For drinks (Soft Drinks, Hard Drinks), consumers prefer Regular options instead of Low Fat.
    
**🔎Summary:**

Low Fat is the leading driver of sales in most food categories, while Regular dominates in drinks. Businesses could capitalize on expanding Low Fat food offerings, while exploring healthier drink options to balance the market.

---
***Does higher product visibility always lead to higher sales ?***

<img width="953" height="611" alt="point plot" src="https://github.com/user-attachments/assets/d505c732-8677-40a0-a9f8-93f733347d27" />
- **💡Findings**
  - General Visibility Trend by Sales Level
    - Low sales items (blue line) consistently have higher average visibility across almost all item types.
    - High sales items (red line) generally show lower average visibility compared to medium and low sales.
    - Medium sales items (green line) are usually between low and high, closer to high sales values.

👉 */This suggests that higher visibility does not necessarily translate to higher sales. Items with high visibility tend to sell less, while items with lower visibility often sell more./*

  - Key Business Implications
    - Shelf visibility alone is not enough: Just increasing product visibility does not guarantee higher sales (e.g., Breakfast and Seafood).
    - Quality, demand, and positioning matter: Items with low visibility can still achieve high sales (e.g., Frozen Foods, Health & Hygiene).
    - Businesses should re-evaluate marketing and placement strategies — instead of just giving more shelf space, focus on matching visibility with demand and consumer preference.

**🔎Summary:**

Low sales items tend to be overexposed (high visibility but low sales), while high sales items achieve success even with lower visibility. This highlights the importance of demand-driven strategies rather than relying solely on product placement.





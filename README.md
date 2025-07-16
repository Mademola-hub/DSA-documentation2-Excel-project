# DSA-documentation2-Excel-project
This is my first project when I started learning data Analysis, with the incubator hub

## Project Topic : 🏬Amazon Product Review Analysis

### 📁 Project Overview
The main goal of this project was to analyze Amazon product data to uncover insights into sales performance, pricing trends, discount effectiveness, and customer engagement. The aim was to better understand marketplace behavior and discover patterns in product categories, pricing strategies, and review activity.

## 🧾 Data Sources

- **amazon_case_study.csv**:  
  This single dataset contains product-level data scraped from Amazon product listings. Each row includes:
  - Product details: `product_id`, `product_name`, `category`, `discounted_price`, `actual_price`, `discount_percentage`
  - Review metrics: `rating`, `rating_count`
  - Descriptive text fields like product titles and short descriptions

🔧 All pivot tables, charts, and calculations used in this analysis were created manually in Excel from this dataset.

## 🔍 Analysis Performed

The analysis was carried out in **Microsoft Excel** using a combination of:

- ✅ Pivot Tables
- ✅ Calculated Columns
- ✅ Data Filtering
- ✅ Charts (Bar, Column, Pie, and Scatter Plots)

Each of the following 14 tasks was answered using one or more of these tools:

## 1. Average Discount by Product Category 
   → Pivot table to calculate the average discount percentage per category i inserted the category on the row while i averaged the discount percentage .
   
   <img width="620" height="264" alt="Screenshot 2025-07-16 161757" src="https://github.com/user-attachments/assets/fbea659a-4dcb-4b6b-aff9-80120340b030" />
   
   I also visualized it using chart which is a column chart to  better visualize the outcome.
   
   <img width="749" height="460" alt="image" src="https://github.com/user-attachments/assets/03a02f18-5469-40e8-8ee2-8112a3e0a0dc" />
   
  **📉 Insights from Discount Analysis**
- **Home Improvement** products receive the **highest average discount** at **57.5%**, making it the most heavily discounted category overall.
- **Computers & Accessories** and **Health & Personal Care** also show strong discount strategies, both averaging around **53%**.
- In contrast, **Toys & Games** products receive **no discounts at all (0%)**, and **Office Products** only see a small average discount of **12.35%**.
- The **overall average discount** across all categories is **approximately 46.69%**.
  → This reveals that while some categories are aggressively priced to drive sales, others may be missing promotional opportunities or are positioned as premium products.

## 2. How many products are listed under each category?
  **Product Count by Category**
   → Counted unique products using pivot count of `product_name` per `category`.
   <img width="618" height="255" alt="Screenshot 2025-07-16 163416" src="https://github.com/user-attachments/assets/971226ff-6ccb-4044-9707-8dcc4508bb18" />
   
   I used the column chart to visualize the pivot table 
   <img width="753" height="465" alt="image" src="https://github.com/user-attachments/assets/d35f444e-a784-4883-aa03-d2fbe010ed66" />

   ### 📝 Key Insights (In Simple Terms)

#### 📌 Most Products Are in Tech and Home Categories
- **Electronics**, **Home & Kitchen**, and **Computers & Accessories** make up **over 97%** of all products.
- This shows that most items in this dataset are related to **technology** and **household items**.

#### 📉 Some Categories Have Very Few Products
- Categories like **Office Products** have a few listings (e.g., 31).
- Others like **Toys & Games**, **Car & Motorbike**, and **Health & Personal Care** have only **1 product each**.
- These are likely **less popular** or **not a main focus** in this dataset.

#### 💡 This means that
- Amazon seems to **focus more on tech and home products** in this data.
- They can decide to be areas by which they can improve on :
  - ➕ **New areas to grow** if there’s customer interest.
  - ➖ Or they might **not be important right now**, depending on how well those products sell.
  - 
## 3. What is the total number of reviews per category?
 **Total Reviews by Category**  
   → Summed `rating_count` in pivot to get total reviews per category.
   
   <img width="617" height="266" alt="Screenshot 2025-07-16 165049" src="https://github.com/user-attachments/assets/40fd3f64-74b9-459a-9585-ba80c50a933d" />
   
   By using chart expecially the column chart to visualize it.
   
   <img width="627" height="645" alt="image" src="https://github.com/user-attachments/assets/f65bc414-c44f-4693-a168-bea6437672ed" />
   
   *📊 The chart shows this clearly — tall bars for Electronics, Computers & Accessories, and Home & Kitchen; very small bars for the rest.*


### 📝 Key Insights 

**🏆 1. Electronics Leads in Reviews**
- The **Electronics** category has over **14 million reviews**, which is the highest.
- ✅ This shows that customers are **very active** when it comes to electronics.
- More reviews usually mean more interest and more sales.

**💻 2. Tech & Home Are Very Active**
- After electronics, **Computers & Accessories** (6.3 million) and **Home & Kitchen** (3 million) also get a lot of reviews.
- ✅ These three categories have the most customer engagement.

**⚠️ 3. Big Gap Between Categories**
- Categories like **Car & Motorbike** and **Health & Personal Care** have **very few reviews** — just a few thousand or even less.
- ✅ This could mean:
  - There are **fewer products** in those categories.
  - Or customers are **not reviewing** them much.
- Less feedback means it's harder for companies to learn what people like or dislike.

**🔍 Summary**
Most of the **customer feedback** in this dataset is about **Electronics**, **Computers**, and **Home products**. These are the **most active** categories where people are talking, buying, and reviewing the most.

## 4. Which products have the highest average ratings?
**Top-Rated Products**  
   → Sorted products by highest `rating` and visualized using Line with Marker chart .
   
<img width="569" height="304" alt="Screenshot 2025-07-16 170922" src="https://github.com/user-attachments/assets/d51e4b9e-85ef-4709-a1a6-745e42266c9a" />

<img width="750" height="462" alt="image" src="https://github.com/user-attachments/assets/00dde160-59e1-484a-98a6-fa887881da38" />

### 🌟 Insights from Product Ratings

- Several products in the dataset have a **perfect average rating of 5.0**, which shows **very high customer satisfaction**.
- Most of these highly rated items are found in **Electronics** (like smartphones, smart home devices, and cameras).
- ✅ This suggests that these products are doing an excellent job of **meeting or even exceeding customer expectations**.

## 5. What is the average actual price vs the discounted price by category?
 **Average Actual Price vs. Discounted Price (by Category)**  
   → Compared averages using pivot and illustrated with a **clustered column chart**.

   <img width="836" height="262" alt="Screenshot 2025-07-16 171707" src="https://github.com/user-attachments/assets/2287fae5-d08a-4a99-876e-a3d8b0f9be88" />

   <img width="1494" height="472" alt="image" src="https://github.com/user-attachments/assets/606e06aa-df20-4952-8ffc-07e6d84c9bf1" />

   ### 💸 Price & Discount Insights

**📊 What the Data Shows**

- **All categories offer discounts:**  
  The average discounted price is **lower than the original price** in every product category.  
  ✅ This means Amazon uses discounts across all types of products.

- **Big savings on Tech and Home items:**  
  Categories like **Electronics**, **Computers & Accessories**, and **Home & Kitchen** have the **largest price drops**.  
  ✅ These are also high-value categories, so customers save more money here.

- **Noticeable savings in smaller categories too:**  
  Even in categories with fewer products like **Car & Motorbike** or **Health & Personal Care**, the discounted prices are clearly lower than the original prices.

#### 📝 Key Insight:

Amazon uses **discounting as a regular strategy** to make products more affordable — especially in popular, high-price categories like tech and home goods.  
✅ This likely helps attract more customers by offering big savings compared to original prices.


## 6. Which products have the highest number of reviews?
 **Most Reviewed Products**  
   → Identified products with the most `rating_count`, visualized in a bar chart.
   
<img width="573" height="267" alt="Screenshot 2025-07-16 172523" src="https://github.com/user-attachments/assets/7b92cb52-5e32-46c8-9a00-6ccfd56ab6fd" />

<img width="1502" height="730" alt="image" src="https://github.com/user-attachments/assets/82a5faae-4588-40db-9e3e-270c4a571415" />

### 🗣️ Most Reviewed Products

**📊 What the Data Shows:**

A few products in the dataset have an **extremely high number of customer reviews**, showing massive popularity and strong customer engagement.

- **Amazon Basics HDMI Cables:**  
  - "Amazon Basics High-Speed HDMI Cable, 6 F"  
  - "AmazonBasics Flexible Premium HDMI Cable"  
  ✅ Both have over **400,000 reviews** each.

- **Boat Bassheads 100 Earphones:**  
  - "Boat Bassheads 100 In Ear Wired Earphone"  
  ✅ This product has **more than 360,000 reviews**.

#### 📝 Key Insight:
These products are not only **best-sellers**, but they also generate a **huge amount of customer feedback**.  
✅ A high number of reviews builds **trust and credibility** with new buyers.  
✅ It also provides **rich insights into customer satisfaction**, helping brands improve and market more effectively.

## 7. How many products have a discount of 50% or more?
**How many products have a discount of 50% or more?**

To identify products with a discount of 50% or more, I added a new column titled `High Discount` with the following formula:

```excel
=IF([@[Discount %]] >= 50, "Yes", "No")
```

- This labels each row as:
     - **"Yes"** if the product has a 50%+ discount
     - **"No"** otherwise

<img width="1366" height="768" alt="Screenshot 2025-07-16 174648" src="https://github.com/user-attachments/assets/f4c91815-ef58-4ab5-8635-336fd3a70707" />

 **Count the Products**

   - To find how many products are marked "Yes", i used the count if formula:
     ```
     =COUNTIF([High Discount], "Yes")
     ```
   - This gives the **total number of products** that have a **discount of 50% or more**.

This shows that there are 608 products that have a discount of 50% or more.

<img width="582" height="66" alt="Screenshot 2025-07-16 174832" src="https://github.com/user-attachments/assets/21ed4315-b45a-4b80-9f14-c54d0d3dfaec" />

## 8. What is the distribution of product ratings (e.g., how many products are rated 3.0,
4.0, etc.)
 **Rating Distribution (e.g., 3.0, 4.0, etc.)**  
   → counted the product name by category and displayed using a  **column chart** to show distribution.
   
<img width="435" height="445" alt="Screenshot 2025-07-16 175941" src="https://github.com/user-attachments/assets/3c9e218a-9b5b-4b3b-bbc9-66344ef95f4b" />

<img width="752" height="465" alt="image" src="https://github.com/user-attachments/assets/5b092460-9294-408c-b8fb-e64398e4dbaa" />

#### 📝 Key Insight:
The product ratings are mostly high, with the most common ratings falling between 4.1 and 4.3. There are very few products with ratings below 3.0 or above 4.8, and only a single product has a rating of 0.


## 9.What is the total potential revenue (actual_price × rating_count) by category?
 **Total Potential Revenue by Category**  
   → Calculated `actual_price × rating_count` in a new column, summed in pivot and displayed using a clusterded column chart .

   <img width="527" height="220" alt="Screenshot 2025-07-16 180852" src="https://github.com/user-attachments/assets/d84925c5-72df-4af5-a392-49a194675f76" />


   <img width="625" height="478" alt="image" src="https://github.com/user-attachments/assets/4fdf8961-b78a-4399-9519-5ef9d432f618" />

#### 📊 What the Data Shows:

- The categories **Electronics**, **Computers & Accessories**, and **Home & Kitchen** account for the **majority of potential revenue** in the dataset.
- These categories have:
  - High product counts
  - High original prices
  - A large number of customer reviews (suggesting high demand)

#### 📝 Key Insight:

These three categories represent the **best opportunities for strong sales and revenue**, especially if products are sold at or near their original prices.

On the other hand, smaller categories like **Car & Motorbike**, **Health & Personal Care**, and **Toys & Games** contribute **very little** to the total potential revenue.

✅ **Conclusion:** Focusing on the top categories can have the **biggest impact** on business growth and profitability.

## 10. What is the number of unique products per price range bucket (e.g., <₹200, ₹200–₹500, >₹500)?
**Product Count per Price Bucket**  
    → Created buckets: `<₹200`, `₹200–₹500`, `>₹500` , counted the product id and used a **bar chart** to visualize counts.
   I created a price bucket where i used the if function to segregate price in a point or range value.
    ```=IF([@[discounted_price]]<200,"<₹200",IF([@[discounted_price]]<500,"₹200–₹500",">₹500"))
```

<img width="1366" height="768" alt="Screenshot 2025-07-16 181956" src="https://github.com/user-attachments/assets/9679173a-0aa5-4763-b65e-15818161dd72" />

<img width="544" height="121" alt="Screenshot 2025-07-16 182118" src="https://github.com/user-attachments/assets/7e8acc65-5b82-4736-b022-7a9ee76fd761" />

<img width="411" height="253" alt="Screenshot 2025-07-16 182331" src="https://github.com/user-attachments/assets/b947374f-c05f-4171-a776-ce4d3bc18d58" />

#### 📊 What the Data Shows:

- Most products are priced **above ₹500**, with **850 unique items** in this range.
- The next largest group includes products priced between **₹200 and ₹500**, with **342 items**.
- The smallest group includes products **under ₹200**, with only **159 items**.

#### 📝 Key Insight:

Most of the items in this dataset fall into the **higher price range** (above ₹500).  
✅ This suggests that the dataset focuses more on **mid to high-end products**, rather than budget items.

## 11.How does the rating relate to the level of discount?
**Relationship Between Rating and Discount**

### 🔧 Steps

 ## A. Created Discount Buckets
   Added a new column to group `Discount%` into ranges like **0–10%**, **11–20%**, ..., **91–100%**.

   **Formula used in Excel:**
   ```excel
   =IF([@Discount%]<=0.10, "0-10%",
   IF([@Discount%]<=0.20, "11-20%",
   IF([@Discount%]<=0.30, "21-30%",
   IF([@Discount%]<=0.40, "31-40%",
   IF([@Discount%]<=0.50, "41-50%",
   IF([@Discount%]<=0.60, "51-60%",
   IF([@Discount%]<=0.70, "61-70%",
   IF([@Discount%]<=0.80, "71-80%",
   IF([@Discount%]<=0.90, "81-90%",
   "91-100%")))))))))
```
### B 📊 Built a Pivot Table

- **Rows**: `Discount Bucket`  
- **Values**: Average of `Rating`
  
<img width="544" height="241" alt="Screenshot 2025-07-16 183818" src="https://github.com/user-attachments/assets/d91893b6-2525-48e1-bf31-8e3a10ea9911" />

### C  📈 Created a Line Chart

Used the Pivot Table data to visualize the trend of average ratings across discount ranges.

<img width="625" height="460" alt="image" src="https://github.com/user-attachments/assets/8befe646-8262-4dda-96ab-c4998dd80ee3" />

### 💡 Key Insight

The data shows that the level of discount generally doesn't affect customer satisfaction.  
A heavily discounted product is **not necessarily** rated lower than one sold at full price.

In fact, deeper discounts may even lead to **slightly higher ratings**, as customers feel they got a better deal.

> ✅ Offering large discounts usually **won’t hurt** the perceived quality of your products.



## 12. How many products have fewer than 1,000 reviews?
**Products with Fewer than 1,000 Reviews**   
    Used the following Excel formula to count how many products had fewer than 1,000 reviews:

    ```excel
    =COUNTIF(amazon!P:P, "<1000")
    ```

    Result: **310 products**
    
<img width="723" height="48" alt="Screenshot 2025-07-16 184529" src="https://github.com/user-attachments/assets/c7626b89-541d-467f-95be-10eb0ddecc4a" />

## 13. Which categories have products with the highest discounts?
**Top Discounted Categories**  
    → i sorted the discount percentage column and picked the top 10 and i visualize using a column chart.
    
<img width="550" height="202" alt="Screenshot 2025-07-16 184745" src="https://github.com/user-attachments/assets/61adc25c-c8db-43f9-80bd-96bd988c2daf" />

<img width="752" height="478" alt="image" src="https://github.com/user-attachments/assets/1b44b062-98d2-4bec-8e2c-b2bcd6494ece" />


## 14. Identify the top 5 products in terms of rating and number of reviews combined.
 **Top 5 Products by Rating + Review Volume**  
 
    To rank products based on both **rating** and **number of reviews**, I created a new column named weighted using the formula below:

    ```excel
    =[@rating]+([@[rating_count]]/1000)
    ```
 After that i used this formula to get the top 5 products in terms of rating and number of reviews combined 
 
    ```excel
    =Table1[@rating] + (Table1[@[rating_count]] / 1000)
    ```

    This combines the product's average rating with a scaled version of its review count (divided by 1,000 to normalize).

    ➤ I then sorted the results in descending order to identify the **top 5 products** with the highest combined score.

    
<img width="549" height="208" alt="Screenshot 2025-07-16 185757" src="https://github.com/user-attachments/assets/86d7094f-9172-494e-b189-286d37d9a341" />

I then use a column chart to visualize 

<img width="752" height="483" alt="image" src="https://github.com/user-attachments/assets/64abc333-1d0b-4368-a7f5-4cdb3d5fdd30" />

### 🔍 Key Insight: Dominance of a Few Products

**1. Dominance of Specific Products**  
The top 5 spots are almost entirely occupied by two product lines:  
- **Amazon Basics HDMI cables**  
- **Boat Bassheads earphones**

These items are both **highly rated** and have **large numbers of reviews**, indicating strong popularity and customer satisfaction.

**2. Reliable Favorites**  
These products are consistent top performers. Their high volume of positive feedback suggests they are:
- Reliable
- Offer great value
- Satisfy a common customer need effectively

**3. Strong Brand Performance**  
This reflects positively on both brands:
- ✅ **Amazon Basics**  
- ✅ **Boat Bassheads**  
It highlights strong performance of key products in the dataset.

> 💬 **In summary**: If you're looking for products that consistently perform well with customers, **Amazon Basics HDMI cables** and **Boat Bassheads earphones** stand out as clear winners.


## 📦 Deliverables
- Amazon case study. csv csv [Download here ]()
- Amazon case study final.csv [Download here ]()







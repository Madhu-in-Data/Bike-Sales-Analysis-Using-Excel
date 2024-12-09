# Bike-Sales-Analysis-Using-Excel

## Table of Contents
1. [Project Objective](#project-objective)
2. [Dataset](#dataset)
3. [Data Cleaning](#data-cleaning)
4. [Analysis and Insights](#analysis-and-insights)
5. [Key Insights](#key-insights)
6. [Suggestions](#suggestions)


### **Project Objective**  
The goal of this project is to analyze customer data to identify trends and patterns that influence bike purchases. The insights derived will help in creating targeted marketing strategies to increase bike sales.


---

### **Dataset**  
The dataset contains the following columns:  
- **ID:** Unique identifier for each customer  
- **Marital Status:** Indicates whether the customer is married or single  
- **Gender:** Male or Female  
- **Income:** Annual income of the customer  
- **Children:** Number of children the customer has  
- **Education:** Educational qualification of the customer  
- **Occupation:** Profession of the customer  
- **Home Ownership:** Indicates whether the customer owns a home  
- **Cars:** Number of cars owned by the customer  
- **Commute Distance:** Distance the customer commutes to work  
- **Region:** Geographical region of the customer  
- **Age:** Age of the customer  
- **Purchased Bike:** Whether the customer purchased a bike  



---

### **Data Cleaning**  
1. **Removed duplicates:** Ensured data consistency and accuracy by removing duplicate rows.  
2. **Updated categorical labels:**  
   - In **Marital Status**, replaced "M" and "S" with "Married" and "Single" for clarity.  
   - In **Gender**, replaced "M" and "F" with "Male" and "Female".  
3. **Checked for unique values and inconsistencies:** Used filters to identify and correct errors or inconsistent representations.  
4. **Created age brackets:** Grouped customers into the following categories for easier analysis:  
   - **Adolescent:** Age < 31  
   - **Middle Age:** 31 ≤ Age ≤ 54  
   - **Old:** Age > 54  
   Nested `IF` statements were used instead of `IFS` to avoid excluding rows that did not meet certain conditions.

---

### **Analysis and Insights**  
Below is the breakdown of analyses performed, along with the insights derived:

#### 1. **Income vs Bike Purchase**  
Analyzed the average income by gender and further grouped it by bike purchase status to identify trends.  

<img width="398" alt="Screenshot 2024-12-09 at 9 57 47 PM" src="https://github.com/user-attachments/assets/c0e1aaf3-483a-4336-969b-f7a9ad41ad84">

**Insight:**  
- Male customers who purchased bikes had a higher average income compared to those who did not.  
- Similarly, female customers who purchased bikes earned slightly more than those who did not, but the difference was less pronounced compared to males.  





#### 2. **Commute Distance vs Bike Purchase**   
Counted bike purchases for each commute distance and ensured commute distances were sorted correctly by renaming "10+ miles" to "More than 10 miles".  

<img width="398" alt="Screenshot 2024-12-09 at 9 57 59 PM" src="https://github.com/user-attachments/assets/4b485a77-fb6c-42fb-8a0b-a348cc278f4f">

**Insight:**  
- Customers commuting 0–1 mile and 2–5 miles were more likely to purchase bikes.  
- Longer commute distances (more than 10 miles) had lower purchase rates, potentially due to the impracticality of biking for such distances.  





#### 3. **Age Bracket vs Bike Purchase**   
Grouped customers by age bracket and analyzed bike purchases within each group.  

<img width="383" alt="Screenshot 2024-12-09 at 9 58 36 PM" src="https://github.com/user-attachments/assets/779144d3-a6ef-4fe2-95ed-4d3e5bcd7831">

**Insight:**  
- Middle-aged customers (31–54 years) had the highest bike purchase rates, likely due to higher disposable incomes and an interest in fitness or leisure.  
- Adolescent and older customers were less likely to purchase bikes, possibly due to limited income or physical limitations.  





#### 4. **Customer Profession vs Bike Purchase**   
Analyzed bike purchases across different professions to identify trends.  

<img width="398" alt="Screenshot 2024-12-09 at 9 58 10 PM" src="https://github.com/user-attachments/assets/23c3c8d8-7afd-4f98-b402-81b7261ad58d">

**Insight:**  
- Professionals had the highest bike purchase rates, likely due to their higher income levels and a preference for biking as a leisure activity.  
- Clerical, management, and skilled manual workers showed lower purchase rates, indicating a potential market segment for targeted marketing.  





#### 5. **Cars Owned vs Bike Purchase**   
Examined the number of cars owned by customers and its relationship with bike purchases.  

<img width="383" alt="Screenshot 2024-12-09 at 9 58 24 PM" src="https://github.com/user-attachments/assets/768b1274-70ac-4370-a344-c01daf2c344f">

**Insight:**  
- Customers with zero or one car were more likely to purchase bikes, potentially viewing them as an alternative mode of transport.  
- Customers owning two or more cars showed significantly lower bike purchase rates, indicating that they rely more on cars for transportation.  



### **Use of Interactive Filters**  
To provide a dynamic exploration of the data, interactive filters were created for the following attributes:  
- **Marital Status**  
- **Education**  
- **Region**  
- **Home Ownership**  

These filters enable users to drill down into specific segments and uncover patterns.
For example, filtering by "Region" can help identify geographical trends in bike purchases, while filtering by "Marital Status" can reveal purchasing behaviors of married vs. single customers.

<img width="1400" alt="Screenshot 2024-12-09 at 10 09 12 PM" src="https://github.com/user-attachments/assets/a758a9ec-de89-4b46-8175-fff7324243ca">

---

### **Key Insights**  
1. Middle-aged customers (31–54 years) are the primary target group for bike sales.  
2. Professionals are the most likely to purchase bikes among all occupations.  
3. Customers with shorter commute distances (0–1 mile and 2–5 miles) are more inclined to buy bikes.  
4. Households with zero or one car present a higher likelihood of purchasing bikes.  
5. Income levels influence bike purchases, particularly among male customers.  

---

### **Suggestions**  
1. **Target Middle-Aged Customers:**  
   - Focus marketing campaigns on middle-aged individuals, highlighting health and leisure benefits.  

2. **Profession-Based Marketing:**  
   - Create tailored advertisements for professionals, emphasizing premium bike models suited for leisure and fitness.  

3. **Promote Short-Distance Biking:**  
   - Highlight the convenience of bikes for short commutes in urban areas through localized marketing efforts.  

4. **Incentives for Low-Income Groups:**  
   - Introduce affordable bike options or installment plans for customers in lower income brackets to increase accessibility.  

5. **Expand in Regions with High Potential:**  
   - Use the "Region" filter to identify underperforming areas and run targeted campaigns to boost sales in those regions.



# Diwali Sales Analysis


## Objective

Improve customer experience by analyzing sales data and increase revenue

## Key Performance Indicators (KPIs) to be examined include:

-       Which gender group made maximum sales?
-       Which age-group made maximum sales under which gender category?
-       State wise sales made.
-       What is the marital status of the customers from whom the orders have been received and what is their purchasing power?
-       List top 10 occupation from which we have received the maximum numbers of orders?
-       Top 3 Product categories where the maximum numbers of orders were placed.
-       Top 3 Product categories where the maximum sales were made.

### Steps followed 

- Step 1: We have utilized pandas and numpy to clean and transform our data.
- Step 2: Identified few values in the amount column are Null.

![snap 15](https://github.com/VBS-03/T20-Cricket-World-Cup-Analysis/assets/162421729/a26558fa-35c9-4a0f-ac8c-327eed65c2b1)

- Step 3: Calculated mean for each category and filled NA with mean for that category
![snap 16](https://github.com/VBS-03/T20-Cricket-World-Cup-Analysis/assets/162421729/051026ec-ac3a-4a5b-bd1f-f879449cde16)
- Step 4: Dropped null values using 

        df.dropna(inplace=True)
- Step 5: Changed data type of the 'amount' column.
- Step 6: Renamed column 'Marital_Status' to 'Married'.
- Step 7: Created a new column "Age_group" by categorizing the different ages into several age groups.

![snap 17](https://github.com/VBS-03/T20-Cricket-World-Cup-Analysis/assets/162421729/1d582e1a-3eef-44ac-99cc-08261344facf)
- Step 8: Next we performed the Exploratory Data Analysis using the 'matplotlib' and 'seaborn' libraries.

## Exploratory Data Analysis

1. Gender v/s Amount Spent

![snap 18](https://github.com/VBS-03/T20-Cricket-World-Cup-Analysis/assets/162421729/903a2491-b3e2-4deb-b43a-03f472725716)


        - From above graphs we can see that most of the buyers are females and even the purchasing power of females are greater than men.

2. Age group who have placed maximum orders and the maximum amount spent.

![snap 19](https://github.com/VBS-03/T20-Cricket-World-Cup-Analysis/assets/162421729/70958047-0682-4f93-b6db-b7ea91fc4c70)

![snap 20](https://github.com/VBS-03/T20-Cricket-World-Cup-Analysis/assets/162421729/44d58ccf-55d4-4d36-9a3e-2e4cc83c4381)

        - From above graphs we can see that most of the buyers are of age group between 26-35 yrs female.

3. State wise orders placed and amount spent.

![snap 21](https://github.com/VBS-03/T20-Cricket-World-Cup-Analysis/assets/162421729/92b15347-5880-420f-b0a5-8e94d60a7895)

![snap 22](https://github.com/VBS-03/T20-Cricket-World-Cup-Analysis/assets/162421729/0e08f300-5337-48e9-85fb-d37878374c32)

        - From above graphs we can see that most of the orders & total sales/amount are from Uttar Pradesh, Maharashtra and Karnataka respectively.

4. Marital Status of the customers placing maximum orders and the group which have spent maximum amount.

![snap 23](https://github.com/VBS-03/T20-Cricket-World-Cup-Analysis/assets/162421729/be2b7cd4-78ea-432b-9b06-ff05532b30a0)

![snap 24](https://github.com/VBS-03/T20-Cricket-World-Cup-Analysis/assets/162421729/c21e0bce-7b12-4ff1-b69a-2bc1e00f3b91)


        - From above graphs we can see that most of the buyers are married (women) and they have high purchasing power

5. Top 3 occupations which the buyers belongs.

![snap 25](https://github.com/VBS-03/T20-Cricket-World-Cup-Analysis/assets/162421729/27d1d0f3-0d02-4b33-a9b2-49119669989f)

        - From above graphs we can see that most of the buyers are working in IT, Healthcare and Aviation sector

6. Top 3 Product categories where the maximum numbers of orders were placed.

![snap 26](https://github.com/VBS-03/T20-Cricket-World-Cup-Analysis/assets/162421729/b8593fa3-35c8-4b24-bbdb-ee092cf68b1f)

        - From above graphs we can see that most numbers of orders are placed from the product category Clothing & Apperals, Food and Electronics & Gadgets.

7. Top 3 Product categories where the maximum sales where made.

![snap 27](https://github.com/VBS-03/T20-Cricket-World-Cup-Analysis/assets/162421729/f1681a3a-a654-4489-bb4e-6d86372b7c19)

        - From above graphs we can see that most of the sold products are from Food, Clothing and Electronics category.

8. Top 10 most sold products.

![snap 28](https://github.com/VBS-03/T20-Cricket-World-Cup-Analysis/assets/162421729/47c7434f-af79-4859-a3a4-d5a8004dddd2)


# Conclusion


Married women age group 26-35 yrs from UP, Maharastra and Karnataka working in IT, Healthcare and Aviation are more likely to buy products from Food, Clothing and Electronics category

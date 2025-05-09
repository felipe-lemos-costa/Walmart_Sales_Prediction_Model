# Walmart Sales Prediction Model
![Walmart Logo](images/0_walmart_logo.jpg)

# Summary
This project performs an exploratory data analysis (EDA) on Amazon sales data, focusing on product reviews and their impact on sales performance. The analysis includes visualizations and statistical insights related to product categories, pricing, and customer ratings.

# Key Insights
1. The "Rating Histogram" graph shows that most of the reviews are between 4.0 and 4.5:
![Rating Histogram](images/1_rating_histogram.jpg)

2. I created a column to categorize the rating numbers into rating descriptions in a particular way:
* 1 to 2 -> 'Terrible'
* 2 to 3 -> 'Poor'
* 3 to 4 -> 'Average'
* 4 to 5 -> 'Good'
![Number of Rating per Rate Description](images/2_number_of_ratings_per_rate_description.jpg)

3. I created a new column, "Macro Category" to identify the number of products evaluated per "Macro Category":
![Most Evalueted Products per Macro Category](images/3_most_evalueted_products_per_macro_category.jpg)

4. This graph shows the top 10 average ratings per "Macro Category", where we can see that the first three evaluated products in the previous graph ("Electronics", "Computers&Accessories" and "Home&Kitchen") have an average rating between 4.0 and 4.2. In addition, the two best-rated products ("OfficeProducts" and "Toys&Games" have only 31 and 1 evaluations, respectively, in the previous graph:
![Average Rating per Macro Category](images/4_rating_average_per_macro_category.jpg)

5. I created a new column "Micro Category" to analyze the top 10 evaluated products per "Micro Category":
![Top 10 Evalueted Products per Micro Category](images/5_top_10_evalueted_products_per_micro_category.jpg)

6. This graph shows the top 5 and bottom 5 average ratings per "Micro Category", where we can identify that all the top 10 evaluated products in the previous graph aren't included in the top 5 best-rated products in this graph. In addition, we can see the worst-rated products in "Micro Categories" which have ratings between 3.3 and 3.6, classified as "Average" in the "Rating Description".
![Rating Average per Micro Category (Top 5 and bottom 5](images/6_rating_average_per_micro_category_top_5_and_bottom_5.jpg)

# Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

# How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/felipe-lemos-costa/Amazon-Sales-EDA-Analysis.git
   ```

2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Open and run the Jupyter Notebook:
   ```bash
   jupyter notebook Amazon-Sales-EDA-Analysis.ipynb
   ```

# License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

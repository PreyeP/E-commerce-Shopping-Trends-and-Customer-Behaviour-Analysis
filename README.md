# E-commerce-Shopping-Trends-and-Customer-Behaviour-Analysis
## Project Description
This report uses MS Excel to presents key insights from the "Shopping Trends and Customer Behaviour Dataset". It focuses on purchasing patterns, seasonal trends, the impact of discounts, and payment method preferences. The analysis was performed using pivot tables and various charts to identify actionable findings. The dataset for this analysis can be found at [Download here](https://www.kaggle.com/datasets/sahilislam007/shopping-trends-and-customer-behaviour-dataset).

### Tools
- MS Excel [Download here](https://microsoft-excel.en.download.it/).

### Data Cleaning and Preparation
The original data had an extra column which didn't add any meaning to the data, therefore the following task were performed;

- Remove the extra column.
- Bolded the column headers.

### Exploratory Analysis
EDA involved exploring the shopping behaviour of customers and answers key questions such as; 
- What is the Average Purchase Amount by Category and Gender.
- What is the Total Purchase Amount by Category and Season.
- How does Discount Impact the Purchase Amount.
- What is the Frequency of Purchases by Payment Method.

### Average Purchase Amount by Category and Gender
<img width="939" height="318" alt="purchase by category and gender" src="https://github.com/user-attachments/assets/4327da4f-5045-4088-a24b-d9225669a0b1" />
There are distinct gender-based preferences in spending across product categories.

- Women tend to have a higher average purchase amount for Accessories.
- Men, conversely, show a higher average purchase amount for Footwear.
- Footwear is the only category where men's average purchase amount surpasses that of women.
- For all other categories, women's average spending is either comparable or higher.
  
#### Implication: Marketing campaigns could be tailored to target these specific gender preferences. For instance, promoting accessories more heavily towards female audiences and focusing on new footwear collections for male customers.

### Total Purchase Amount by Category and Season
<img width="1298" height="433" alt="Purchase by category and season" src="https://github.com/user-attachments/assets/1b0edc3c-95a4-4983-bda4-82b76c7111d4" />

Clothing is the dominant sales category, with specific seasonal peaks, while outerwear consistently performs lowest.

- Clothing emerges as the category with the highest overall purchase amount across all seasons.
- The peak seasons for Clothing sales are Spring, Winter, and Fall, in that order.
- Outerwear consistently registers the lowest total purchase amount across all seasons.
  
#### Implication: This insight is vital for inventory planning and seasonal promotions. Resources should be allocated to ensure sufficient stock of clothing during its peak seasons. Strategies for boosting outerwear sales, or re-evaluating its product offering, might be considered.

### Impact of Discount Applied on Purchase Amount
<img width="829" height="411" alt="Discount applied" src="https://github.com/user-attachments/assets/bf0ad60c-b3ec-488f-81cd-8dfc7f5e15a6" />

The average purchase amount is higher when no discount is applied, suggesting that discounts do not necessarily drive larger individual purchases.

- The analysis revealed that the average purchase price for transactions without a discount applied is higher than for transactions where a discount was utilized.
  
#### Implication: This is a critical finding for profitability. It suggests that discounts might be attracting more budget-conscious buyers or simply reducing the profit margin on sales that would have occurred anyway. The business should carefully evaluate discount strategies to ensure they are genuinely incremental and not eroding average transaction value. A focus could shift to value-added promotions or loyalty programs rather than solely relying on price reductions.

### Frequency of Purchases by Payment Method
<img width="876" height="394" alt="Frequency of Purchase by Payment method" src="https://github.com/user-attachments/assets/148b6f32-1b96-4c55-863f-ab9fb9baa37d" />

PayPal is the most favored payment method among customers, followed by Cash, with Bank transfer being the least preferred.

- PayPal is the most frequently used payment method.
- Cash ranks as the second most preferred method.
- Bank transfer is the least preferred payment method.
  
#### Implication: Ensuring a smooth and reliable payment experience for PayPal users is paramount. While Cash remains significant, businesses should also consider optimizing the experience for less preferred methods like Bank transfers if they aim to encourage their use or if there's a strategic reason to do so. Understanding these preferences also helps in managing payment gateway fees and user experience.

### Conclusion 
This analysis provides a foundational understanding of customer behavior and shopping trends within the dataset. The insights highlight opportunities for targeted marketing, optimized inventory management, and strategic promotional planning.

### Recommendations

- Tailored Marketing: Develop gender-specific campaigns for accessories and footwear.
- Seasonal Inventory: Prioritize clothing stock for Spring, Winter, and Fall, while re-evaluating strategies for outerwear.
- Strategic Discounting: Re-assess the impact of discounts to ensure they drive true incremental sales and profitability rather than just attracting lower-value transactions.
- Payment Optimization: Continue to facilitate seamless PayPal transactions and consider ways to enhance the appeal or ease of use for less popular payment methods like bank transfers.

### Methodology: Dashboard and Visuals Creation Process
This report details the complete process of creating the e-commerce purchase behavior dashboard, from pivot tables to dashboard creation.

- Step 1: Creating the PivotTables
The visualizations are built on the foundation of PivotTables, as they allow for flexible summarization and easy filtering.

a. PivotTable 1 (Average Purchase Amount by Category and Gender): To create the "Average Purchase Amount by Category and Gender" chart, a PivotTable was inserted (Insert > PivotTable).

-  Rows: Category
-  Columns: Gender
-  Values: Purchase Amount as "Average".

b. PivotTable 2 (Total Purchase Amount by Category and Season): For the "Total Purchase Amount by Category and Season" chart.
  
- Rows: Category
- Columns: Season
- Values: Purchase Amount as "Sum".

c. PivotTable 3 (Impact of Discount Applied on Purchase Amount): To analyze the "Impact of Discount Applied on Purchase Amount."

- Rows: Discount Applied.
- Values: Purchase Amount "Sum".

d. PivotTable 4 (Frequency of Purchase by Payment Method): To analyze the "Frequency of Purchase by Payment Method."

- Rows: Payment Method
- Values: Payment Method as "Count".

- Step 2:Dashboard Design
The focus shifted from data analysis to visual presentation to remove the "Excel feel" and create a professional dashboard.

- Worksheet Gridlines: To create a clean canvas, the worksheet gridlines were hidden (View > Show > uncheck Gridlines).
- Formula Bar: The formula bar was hidden (View > Show > uncheck Formula Bar) to prevent visual distraction and accidental edits.
- Chart Buttons: The small chart buttons that appear on PivotCharts were hidden (PivotChart Analyze > Field Buttons > Hide All).
- Background Color: A solid background color was applied to the worksheet using the "Page Layout" tab to create a uniform and branded appearance.
- Chart Formatting: Individual chart elements were formatted for clarity:
- Chart titles were made prominent.
- Axis labels were formatted for readability.
- Data labels were added where appropriate 

- Step 3: Adding Slicers for Interactivity
The final step implemented in the final dashboard image, is the addition of slicers to make the dashboard interactive.

- Slicer Insertion: From any of the PivotTables or PivotCharts, a slicer was inserted (PivotChart Analyze > Insert Slicer).
- Field Selection: The Season and Location fields were selected to create two separate slicers.
- Connecting Slicers: This is the most critical step. For each slicer, the "Report Connections" feature was used (Right-click Slicer > Report Connections...). The slicers will be connected to all four PivotTables (PurchaseAmount_Gender, TotalPurchase_Season, Discount_Impact, and Payment_Frequency).

### Final Product
<img width="837" height="458" alt="Final Dashboard" src="https://github.com/user-attachments/assets/73f7da70-a8a5-434b-aadd-5a1ec857f011" />


The result is a clean, visually appealing dashboard that provides at-a-glance insights into purchase behavior. The groundwork for interactivity has been established, and the addition of slicers transforms the static report into a powerful analytical tool.


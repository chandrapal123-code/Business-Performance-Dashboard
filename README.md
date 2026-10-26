# Business-Performance-Dashboard
This project analyzes business sales, costs, gross profit, and gross margin from 2021 to 2024. Python was used for data inspection, cleaning and validation, exploratory data analysis (EDA), trend analysis, product profitability, outlier review, product-mix analysis, and hypothetical cost-reduction scenarios. 

### Project Overview
  * This project analyzes business sales, costs, gross profit, and gross margin from 2021 to 2024. Python was used for data inspection, cleaning and validation, exploratory data analysis (EDA), trend analysis, product profitability, outlier review, product-mix analysis, and hypothetical cost-reduction scenarios. Power BI was used to communicate the results through an interactive dashboard.
### business question :-
   Why is the company's margin declining despite revenue growth, and what three specific actions should management take?
### Project Objectives
* Analyze sales, costs, gross profit, and gross margin over time.
* Compare annual performance from 2021 to 2024.
* Identify differences in product and division profitability.
* Examine whether product-mix changes may be associated with margin changes.
* Review outliers and document data-quality limitations.
* Model hypothetical cost-reduction scenarios.
* Build an interactive Power BI dashboard and provide business recommendations.
### Tools & Technologies
    * Tool 
    * Python
    * Liberarys
    * Jupyter Notebook
    * Power BI
    * CSV / Excel
    * GitHub
### Dataset
    The dataset includes fields such as Row ID, Order ID, Order Date, Ship Date, Ship Mode, Customer ID, Country/Region, City, State/Province, Division, Region, roduct ID, Product Name, Sales, Units, Gross Profit, and Cost.

### Project Workflow
 * Data loading and inspection
   * Loaded the dataset and reviewed rows, columns, data types and descriptive statistics.
*  Data cleaning and validation
    * Checked missing values and duplicate records.
    * Validated date fields and reviewed implausible shipping durations.
    * Investigated unusual sales records rather than automatically deleting them.
    * Documented data-quality limitations.
* Exploratory data analysis
    * Calculated descriptive statistics, including mean, median, standard deviation, quartiles and IQR where applicable.
    * Analyzed sales, cost, gross profit and gross margin.
    * Compared annual and monthly trends.
    * Reviewed product-level profitability, product mix, assortment changes and outliers.
    * Examined sales and gross-profit correlation with appropriate caution.
* Product and mix analysis
     * Compared products by sales contribution and gross margin.
     * Looked for high-sales products with relatively low margins.
     * Compared product sales shares between selected years.
     * Investigated whether product-mix changes may help explain the margin movement.
* Cost scenario analysis
   * Modelled illustrative 0%, 2%, 5% and 10% cost-reduction scenarios.
   * Estimated the effect on gross profit and margin while holding sales constant.
   * Treated scenarios as hypothetical calculations, not guaranteed savings.
* Power BI dashboard
   * Presented KPI cards, annual and monthly trends, product profitability, product-mix comparisons and cost scenarios.
### Key Findings
   * Overall performance

                | Metric | Reported value |
                | Total Sales | $141,783.63 |
                | Total Cost | $48,340.83 |
                | Total Gross Profit | $93,442.80 |
                | Overall Gross Margin | Approximately 65.91% |
 * Annual performance
   
                     | Year | Sales | Gross Profit | Gross Margin |
                     | 2021 | $28,953.55 | $18,942.37 | 65.42% |
                     | 2022 | $29,002.65 | $19,209.06 | 66.23% |
                     | 2023 | $36,859.32 | $24,340.58 | 66.04% |
                     | 2024 | $46,968.11 | $30,950.79 | 65.90% |
* From 2022 to 2024, sales increased by approximately 61.94% and gross profit increased by approximately 61.13%. Gross margin fell from 66.23% to 65.90%, a decrease of 0.33 percentage points. This means sales and gross profit grew, while gross profit as a share of sales declined slightly.

### Product-level findings
   * Kazookles: Reported sales of $1,205.75, gross profit of $92.75 and margin of 7.69%. Verify aggregation and filters before treating this as a final finding.
   * Chocolate division: Reported gross margin of approximately 67.45%.
   * Other division: Reported gross margin of approximately 44.84%.
   * Lickable Wallpaper: Reported sales share increased from 2.76% in 2022 to 6.22% in 2024, with a reported margin of 50%. Validate these figures and the mix          calculation before concluding that this product contributed to the overall margin change

 ### Illustrative Cost-Reduction Scenarios
* These scenarios use reported 2024 values: sales of $46,968.11, cost of $16,017.32 and gross profit of $30,950.79
  
                 | Cost reduction | Estimated savings | Scenario gross profit | Scenario margin |
                 | 0% | $0.00 | $30,950.79 | 65.90% |
                 | 2% | $320.35 | $31,271.14 | 66.58% |
                 | 5% | $800.87 | $31,751.66 | 67.60% |
                 | 10% | $1,601.73 | $32,552.52 | 69.31% |
# Business Recommendations
### Optimize product mix and pricing
    * Goal: Improve the profitability of sales without sacrificing valuable demand.
* Evidence: The overall margin declined from 66.23% in 2022 to 65.90% in 2024. Your product-level analysis also identifies substantial differences in margins, including a previously reported 7.69% margin for Kazookles.

 * Actions:
    * Review products with low margins and high sales shares first.
    * Investigate product costs, selling prices, discounts if available, and supplier terms.
    * Test selective price changes or promotions rather than applying blanket price increases.
    * Assess whether growing lower-margin products are reducing the overall margin.
    * KPIs to track: Gross Margin %, Product Sales Share %, Gross Profit by Product.
      * Success measure: Improve margin while maintaining sales volume and customer demand. Set a specific target after reviewing product-level economics.

### Launch a targeted cost-efficiency review
    * Goal: Reduce avoidable costs without damaging product quality or sales.
 * Evidence: Your cost-reduction scenarios estimate that a 5% reduction in the reported 2024 cost base could produce approximately $800.87 in savings, assuming sales remain constant.

* Actions:
    * Investigate the largest cost contributors first.
    * Review supplier pricing, purchasing terms, waste, and production or distribution costs only where relevant data is available.
    * Pilot a realistic cost-reduction initiative before applying it across the business.
    * Compare actual savings against the scenario estimate.
    * KPIs to track: Total Cost, Cost as % of Sales, Gross Profit, Gross Margin %.
         * Success measure: Deliver verified savings without reducing sales, product quality, or customer satisfaction. The 5% scenario is a test case, not a                 guaranteed outcome.

### Establish margin monitoring and review triggers
    * Goal: Detect margin deterioration early instead of reacting after it occurs.
* Evidence: Sales grew substantially from 2022 to 2024, but gross margin did not sustain its 2022 peak. This demonstrates why sales growth alone is not enough to evaluate business performance.

* Actions:
   * Review sales, gross profit and gross margin monthly.
   * Track margin by product, division and region where data is sufficiently reliable.
   * Flag products with falling margins or rising sales share alongside weak profitability.
   * Assign a responsible person to investigate material changes and document corrective action.
   * KPIs to track: Monthly Gross Margin %, Sales Growth %, Gross Profit, Low-Margin Product Count.
        * Success measure: Investigate material margin deterioration within an agreed review period and track whether corrective actions improve profitability.

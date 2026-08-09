Retail Sales & Profitability Analysis

### Business Problem
Sales have grown steadily over four years (2014–2017), with a 20.36% increase in
the most recent year alone. But is that growth translating into equally strong
profit — or are some products, regions, and customers quietly underperforming
without anyone noticing?

### Approach
I built a multi-page Power BI dashboard using four years of retail transaction
data (Superstore dataset), covering Orders, Products, Customers, and a custom
Calendar table. I structured the data into a proper star schema (one fact table,
three dimension tables) rather than a single flat file, so relationships and
time-intelligence calculations (YTD, YoY) would work correctly. I built over a
dozen DAX measures — including Profit Margin %, YoY Growth %, and Average Order
Value — and organized the report into four focused pages: Sales Overview,
Product Analysis, Regional Analysis, and Customer Analysis, each answering a
different business question with synced filters and consistent navigation.

### Insights (the real findings, with numbers)

1. **Furniture sells well but barely profits.** Furniture generates 32.3% of
   total sales but only 6.44% of total profit — a 2.7% profit margin, far below
   Technology (17.9%) and Office Supplies (16.7%).

2. **Regional performance isn't just about sales volume.** West is the top
   region by sales (₹0.76M), but East has the best profit margin (15.46%).
   South is the weakest performer on both fronts — lowest sales (₹0.40M) AND
   the worst margin (7.51%).

3. **The company's biggest customer is losing money.** Sean Miller is the
   #1 customer by total spend (₹25,043) but is running at a -8% profit margin,
   actively costing the business ₹1,980 rather than contributing profit.

4. **Customer revenue is healthily diversified.** The top 10 customers account
   for only 6.69% of total revenue — the business isn't overly dependent on a
   small handful of big accounts.

5. **Profit growth is starting to lag behind sales growth.** While profit grew
   faster than sales in 2015–2016, in 2017 sales grew 20.36% while profit grew
   only 14.24% — the first sign that margins may be under pressure as the
   business scales.

### Impact (what the business should actually do)

- **Investigate Furniture pricing and cost structure** before expanding that
  category further — its current margin makes growth in this category
  potentially unprofitable.
- **Study what East region is doing right** (best margin) and see if pricing
  or discounting practices can be applied to South, the weakest-performing
  region.
- **Review Sean Miller's account terms** — heavy discounting or high-cost
  fulfillment may be turning a top customer into a financial liability.
- **Monitor 2018 margins closely** — if sales continue outpacing profit
  growth, it may signal rising costs or over-discounting that needs
  addressing before it compounds further.

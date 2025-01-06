# Portfolio-Projects

# Analysis of Vertex Office Supplies Sales Methods and Revenue Performance 


# PROJECT OVERVIEW

Vertex Office Supplies Sales Strategy Analysis

Background
Vertex Office Supplies, established in 1984, supplies high-quality office products to large organizations. While they don’t produce our their items, they've built strong customer trust by offering top-tier products from other manufacturers.

As consumer purchasing habits evolve, so must their sales strategies. With the recent launch of a new office stationery line, they aim to identify the most effective sales techniques to ensure successful product adoption while minimizing costs.

New Product and Sales Methods
The new stationery line focuses on tools that enhance creativity and brainstorming, such as notebooks, pens, and sticky notes. To test sales effectiveness, they implemented three strategies over six weeks:

Email: Two targeted emails were sent (at launch and after three weeks), requiring minimal effort.
Call: Sales representatives engaged customers in 30-minute phone calls.
Email + Call: Customers received an initial email followed by a 10-minute phone call a week later.
This project aims to evaluate the performance of these methods to determine the optimal approach for future product launches.






# Sales Method Analysis Report
## 1. Data Validation
**Cleaning and Validation Steps**


**Revenue Data:** I made sure all the revenue data was in the right numerical format. Any non-numerical values or inconsistencies were fixed by either replacing them or just removing them.

**Sales Method Data:** I checked the sales methods to ensure they only contained "Email," "Call," and "Email + Call." There were no major issues, but I had to remove any rows that didn't match those three values.

**State Data:** The states were checked for consistency, and everything matched correctly with the expected state names. There were no invalid or misspelled states.

**Missing Data:** When reviewing the dataset, I noticed that the "Email + Call" method made up only about 7.09% of the total data. After looking at how this affected the overall results, I decided it was best to remove those rows since it didn't have a significant impact on the analysis.

## 2. Exploratory Analysis
I took a look at the overall revenue and also broke it down by each sales method to understand how things were performing:

**Revenue for all methods combined:**

Total Revenue: $1,304,734.36

Minimum Revenue: $1,199.22

Maximum Revenue: $229,765.55

Average Revenue: $17,587.59

These figures helped give an overall idea of the total sales and how they were distributed among the methods.

**Revenue by Sales Method:**

Email + Call: This method showed steady growth in the first few weeks, peaking around weeks 5 and 6.

Call: It had the lowest revenue, but there was an increase in revenue between weeks 2 and 5.

Email: Even though Email brought in the highest revenue overall, the data showed a sharp decline by week 6.

Next, I looked at how revenue varied by state and sales method to get a better idea of where things were happening:

State-Based Revenue: California really stood out, generating the highest revenue across multiple methods. The "Email" method brought in $83,163.31 in revenue there. Texas and New York followed, but places like Florida had significantly lower contributions.

![Screenshot (33)](https://github.com/user-attachments/assets/ba7e86fc-1882-4d34-be30-88b5a603d620)

This helped me see where the big revenue drivers are and where the sales efforts could be focused more.

## 3. Key Metric
**Key Metric: Revenue per Method**
The key metric the business should track is Revenue per Method, as it will show how each method is performing in terms of revenue generation. Monitoring this will give insights into which method is bringing in the most return, helping guide future strategies.

**Initial Value Estimation Based on Current Data:**

Email: $672,317.83 total revenue

Email + Call: $404,787.15 total revenue

Call: $227,563.49 total revenue

These values give a good baseline to work with and track how things change in the future.

## 4. Final Summary and Recommendations

**Key Findings:**

Email is still the top performer revenue-wise, but its revenue has been decreasing over time. This decline is something to keep an eye on.
Email + Call seems to offer good potential, especially in weeks 4 to 6, despite its lower revenue at the start.
Call has the smallest revenue overall but shows steady growth, which means there could be opportunities to boost its performance.

**Recommendations:**
I’d suggest continuing to focus on Email since it's still the highest revenue-generating method. But I'd also recommend addressing the decline in performance over time and seeing if any improvements can be made to stabilize it.
Email + Call could be worth further exploring for consistent growth, especially considering how it performed during weeks 4 to 6.
For Call, it might be a good idea to dig deeper into why it's generating the lowest revenue and look at ways to increase its numbers, whether that's through better targeting or changing the approach.
The business should keep an eye on Revenue per Method and track how each method is doing so that it can adjust strategies as needed.

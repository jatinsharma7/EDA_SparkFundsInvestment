# EDA - SparkFundsInvestment

## Project Brief
Spark Funds is an asset management company who wants to make investments in a few companies. The CEO of Spark Funds wants to understand the global trends in investments so that she can take the investment decisions effectively.
 

## Business and Data Understanding
Spark Funds has two minor constraints for investments:
1. It wants to invest between 5 to 15 million USD per round of investment
2. It wants to invest only in English-speaking countries because of the ease of communication with the companies it would invest in.

- For analysis, I considered a country to be English speaking only if English is one of the official languages in that country
- I used wikipedia list of countries where English is an official language.

These conditions will give us sufficient information for your initial analysis. Before getting to specific questions, let’s understand the problem and the data first.

 ### 1. What is the strategy?
Spark Funds wants to invest where most other investors are investing. This pattern is often observed among early stage startup investors.

### 2. Where did we get the data from? 
Real investment data from crunchbase.com is taken, so the insights received may be incredibly useful. Data is divided into the following files:

Uses three main data tables for the entire analysis:

### 3. What is Spark Funds’ business objective?
The business objectives and goals of data analysis are pretty straightforward.

**Business objective**: The objective is to identify the best sectors, countries, and a suitable investment type for making investments. The overall strategy is to invest where others are investing, implying that the 'best' sectors and countries are the ones 'where most investors are investing'.

Goals of data analysis: Your goals are divided into three sub-goals:<br/>
**Investment type analysis**: Comparing the typical investment amounts in the venture, seed, angel, private equity etc. so that Spark Funds can choose the type that is best suited for their strategy.
Country analysis: Identifying the countries which have been the most heavily invested in the past. These will be Spark Funds’ favourites as well.<br/>

**Sector analysis**: Understanding the distribution of investments across the eight main sectors. (Note that we are interested in the eight 'main sectors' provided in the mapping file. The two files — companies and rounds2 — have numerous sub-sector names; hence, you will need to map each sub-sector to its main sector.)

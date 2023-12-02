# Click Rate Analysis for the Center for Indonesian Policy Studies (CIPS)
> This project aimed to understand whether CIPS' publication downloads were decreasing and, if so, why.

## Datasets
1. *Publication characteristics*

This was a database of all of CIPS's released publications to date. Characteristics include year released, title, author, and keywords among many others

2. *Digital Media dashboard*

CIPS's dashboard contained each publication's performance on their website and Neliti, a repository of research publications. Each publication was available in English and Indonesian and performance was measured by downloads or views. The data spanned the period of January 2019 - August 2023

*Datasets cannot be shared due to privacy reasons

## Methodology & Conclusions
- Project was exploratory in nature, taking advantage of descriptive and diagnostic analysis
- Most time spent was on data wrangling and cleaning as both datasets were largely unusable in their starting forms. Data from *publication characteristics* was then added to the *digital media dashboard* data to aid in further analysis
- **Countplots** were used on the *publication characteristics* database to understand the distribution of publications across types and topics, the characteristics thought to have the biggest impact on performance
- **Lineplots** (particularly displayed on Seaborn's FacetGrids) were used to visualise historical performance. Deep dives were then carried out on performance spikes and crashes seen in the lineplots
- **Stacked barplots** were used to visualise the performance distribution for types and topics. Each plot had two bars denoting either Website or Neliti.
- To test the impact of types and topics on performance, ANOVA tests were used for these subsets of interest: Neliti downloads, Neliti views, and Website downloads. Results showed that types had a significant impact on performance while topics did not.

## Limitations
- There may be some errors in the accuracy of the data as the digital media manager had been manually inputting the data each month and Neliti underwent a website revamp, changing the way downloads and views were counted
- More data may increase the reliability of the results as some categories had a very small sample. The 'Book' type, for example, only had 1 entry

## Further Research
- Using Google Trends to estimate the popularity of publication keywords and testing the strength of this relationship on performance

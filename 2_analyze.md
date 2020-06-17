---
layout: page
title:  Analyzing your Data
permalink: /analyze/
---
## Section 2: Analyzing Your Data

<a name="top"></a>
### Table of Contents
###   Part A: [Cleaning your Dataset](#cleaning "Cleaning & De-Identifying your Dataset")
###   Part B: [Learning Resources](#resources "Learning Resources")
###   Part C: [Review — Facts, Stats, and Trends](#review "Statistics Review")

___

## <a name="cleaning"></a> Part A: Cleaning & De-Identifying your Dataset

A dataset that has duplicate entries or misspelled words can skew your outcomes. Check out Microsoft Office’s [Top Ten Ways to Clean your Data](https://support.office.com/en-us/article/Top-ten-ways-to-clean-your-data-2844b620-677c-47a7-ac3e-c2e157d1db19) before starting your analysis.

### CHHS Data De-Identification Guidelines

  Every single employee of CHHS — whether working with data in a technical capacity, as a manager, an analyst, or otherwise -- is responsible for ensuring **no personal or redacted information is ever shared throughout their project**. The [De-Identification Guidelines](https://chhsdata.github.io/dataplaybook/documents/CHHS-DDG-V1.0-092316.pdf) will walk you through this process. 
  As Departments classify data tables and catalog their publishable state data, they should be mindful of legal and policy restrictions on publication of certain kinds of data. The CHHS Data Subcommittee put together the following guidelines to ensure a standard of data governance across CHHS. 
![De Identification Contents]({{ site.baseurl }}/assets/images/03_figure05.png)
  The CHHS Data De-Identification Guidelines support CHHS governance goals to reduce inconsistency of practices across Departments, align standards used across Departments, facilitate the release of useful data to the public, promote transparency of state government, and support other CHHS initiatives, such as the CHHS Open Data Portal.
See the full guidelines [here](https://chhsdata.github.io/dataplaybook/documents/CHHS-DDG-V1.0-092316.pdf).

### De-Identification Considerations:

1. The CHHS Data De-Identification Guidelines are the default policy for CHHS departments. If a CHHS Department wants to customize the guidelines, it must have appropriate references to departmental processes and must file a copy of their guidelines with the Office of the Agency Information Office.
2. While most state agencies are covered by the California Information Practices Act (IPA), some are also covered by or impacted by HIPAA, the United States Health Insurance Portability and Accountability Act. Unlike the IPA, which applies to all personal information, HIPAA only applies to certain health or healthcare-related information. HIPAA requirements apply in combination with IPA requirements.
3. For Departments covered by HIPAA, de-identification must meet the HIPAA standard. The CHHS Data De-Identification Guidelines serve as a tool to make and document an expert determination consistent with the HIPAA standard.

>[Click for Back to Top](#top)

___

## <a name="resources"></a> Part B: Learning Resources

### Learning Resources

If you don’t have much experience with data analysis, it may be helpful to review some of the key concepts in statistics and math to make sure you understand what you are actually looking at during data analysis.
  * [Central Tendency](https://statistics.laerd.com/statistical-guides/measures-central-tendency-mean-mode-median.php)
  * [Correlation](https://www.excelfunctions.net/excel-correl-function.html)
  * [Paired t-test](http://www.real-statistics.com/students-t-distribution/paired-sample-t-test/)
  * [Regression Analysis](https://www.qimacros.com/hypothesis-testing/regression/)
  * [Multiple Regression in Excel](https://www.businessinsider.com/understand-excel-multiple-regression-2014-10)

Other Resources: 
  * [Coursera](https://www.coursera.org/courses?query=beginner&nbsp;data&nbsp;analysis) almost always has free online classes for new or experienced  data analysts
  * [Khan Academy](https://www.khanacademy.org/computing/ap-computer-science-principles/data-analysis-101) is one of the most popular online learning tools if you have more  specific questions about data analysis.
  * [Lynda](https://www.lynda.com/Tableau-tutorials/Tableau-9-Essential-Training/386886-2.html) has a number of Tableau Learning Tutorials

>[Click for Back to Top](#top)

___

## <a name="review"></a> Part C: Review — Facts, Stats, and Trends

Data analysis can be daunting for the first-time data analyst. To simplify the vast work of  data science, we’ll stick to the “facts-stats-trends” framework:
>1. **Facts** are counts, sums, and numbers.  
>2. **Stats** are basic descriptive statistics  (mean, median, mode, distribution)
>3. **Trends** are found by comparing data between two points in time or groups (e.g. percent change, percent different)
    * You can compare **across time** in the same group (*longitudinal*), or **between groups** in the same time period (*cross-sectional*)

### Facts

>Facts are useful for providing a **high-level summary** of your data or methods. (*e.g. How many participants completed your program?  What was the average calorie intake of participants  at 4 weeks?*) 

  * Facts can **contextualize** your data as percentages, fractions, or rates (*e.g. 100 participants  completed the program out of  150 = 67% completion rate*)
  * If you ever had benchmark measurements or metrics to set a baseline for your data, you can  compare facts with those to assess **whether some intervention was successful.** (*E.g. Only 80/150 participants  completed the program prior to our change in outreach. Thus, we increased completion by nearly 14% through this project.*)

### Stats

>Gathering meaningful statistics about your data is essential to gaining a deeper understanding into the impacts it had on your users. Even basic statistical transformations can reveal surprising patterns in your data.

  * Simply put, stats present high-level summaries and suggest implications of your data
  * Often the basis of simple charts and tables
  * **Central Tendency** is one simple but powerful statistical measure
    * Mean, median, and mode are all measures of central tendency — that is, how each data  point relates to the average
    * Excel can [calculate](https://access-excel.tips/excel-central-tendency-mean-mode-median/) this for you
  * It can be useful to **compare the central tendency of different populations** in your study  (*Example: did individuals who completed your program experience fewer days of unemployment on average than those who did not complete the program?*)
  * **The Distribution** of your dataset — or how each data point relates to the set as a whole — can tell you a lot about your data through **visualizations** or **graphs**
    * You can easily mistake a skewed dataset for a positive/negative outcome if you only rely on central tendency  (*e.g. out of 100 participants who completed the program, one reported 300 days of unemployment compared to an average of 14-20 days for the remaining 99. Since the 50  who did not complete the program experienced an average of 20-30 days of unemployment, __you underestimated the effectiveness of your program__ due to the presence of this outlier.*) 

### Trends

>Trends are what result when you combine your **facts** with your **stats** — they reveal broader patterns that describe your program’s impact and answer your guiding questions.

Some examples trends and how to find them:
  * Compare the average rate of completion of your project over time (How many participants  completed your program on average at three different timepoints?)
  * How did the percent of people who reported high satisfaction with the program change over time? (Was the percentage higher in at one time? Why?)
  * Was one group more likely to experience unemployment one year after completion than another? 

>**Note**: When comparing distributions or central tendencies between two populations over time, you must prove any differences are statistically significant — that is, **it is more than 95% likely** that the differences you found between populations is actually due to your intervention and **not to random chance**. You can do this using something called a [t-test](http://www.real-statistics.com/students-t-distribution/paired-sample-t-test/).  Read more about statistical  significance [here](https://hbr.org/2016/02/a-refresher-on-statistical-significance).

>[Click for Back to Top](#top)

<!-- Pagination -->
<div class="pagination">
  <a class="pagination-item older" href="{{ site.baseurl }}/plan_c_find">&laquo; Prev</a>
  <a class="pagination-item newer" href="{{ site.baseurl }}/communicate">Next &raquo;</a>
</div>

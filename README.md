# Analysis of Crowdfunding Campaigns: Insights and Limitations

Crowdfunding platforms such as Kickstarter and Indiegogo have witnessed substantial growth in popularity over the past decade. These platforms have attracted a diverse range of projects and creators, but not all campaigns achieve their funding goals. In this analysis, I delved into a dataset of 1,000 sample crowdfunding projects to extract valuable insights and identify potential limitations.

**Insight**

1. **Geographic Distribution**:
   - The majority of crowdfunding campaigns (76%) are based in the United States, while the remaining 24% are distributed across Australia, Canada, and various European countries, including England, Denmark, Switzerland, and Italy.

2. **Top Industries**:
   - The theater, film and video, and music industries stand out with the highest number of fundraising campaigns, accounting for 34%, 18%, and 18% of the total respectively.

3. **Success Rates by Industry**:
   - The success rate for campaigns falls within the range of 50% to 60% across all industries.
   - Journalism has the lowest number of campaigns but a 100% success rate, with all four campaigns in the United States achieving their goals.
   - Within the theater industry, the "Plays" sub-category boasts the highest success rate at 54%.
   - In the film and video industry, Drama, Documentary, and Animation have success rates of 60%, 57%, and 62%, respectively.
   - In the music industry, Rock and Indie Rock have the most successful campaigns, with success rates of 58% and 51%, respectively.
   - The success rates of campaigns vary by country and industry, with some industries performing better in specific countries.

4. **Temporal Patterns**:
   - Data spans from 2010 to January 2020, with an average of approximately 100 campaigns run per year.
   - June and July exhibit an increased number of successful campaigns, with July having the highest count (58).
   - September has the fewest failed campaigns (23).
   - August shows a low success rate, coupled with a high number of both failed and canceled campaigns, suggesting it may not be an optimal time to launch a new campaign.

5. **Funding Amounts**:
   - Surprisingly, as the funding amount increases, the success rate of campaigns also rises. The range from $15,000 to $49,999 demonstrates a success rate of more than 67%, increasing to 100%. However, campaigns seeking more than $50,000 have a higher failure rate (53%).

**Limitations of the Dataset**

1. **Limited Geographic Detail**: The dataset lacks detailed geographic information, such as the distribution of campaigns across different U.S. states. This data could provide insights into which states are more conducive to specific campaign industries.

2. **Demographic Data**: The dataset lacks information about the genders and ages of backers. Including this data would enable a more in-depth analysis of the crowdfunding dynamics.

**Additional Tables and Graphs**

To enhance the analysis, we could consider:

1. **Temporal Analysis by Industry**: Examining the relationship between campaign success rates and campaign duration for each industry.

2. **Yearly and Country-Specific Analysis**: Filtering the data by year and country to explore how crowdfunding trends vary across time and location.

3. **Average Donation vs. Success**: Analyzing the impact of the average donation amount on the likelihood of a campaign's success by defining donation ranges.

**Mean vs. Median**:

In this skewed dataset, the median is a more suitable measure to summarize the data, as it is less affected by outliers.

**Variability**:

Successful campaigns exhibit higher variability with a standard deviation of 1266.24, compared to failed campaigns with a standard deviation of 959.99. This suggests that successful campaigns have more variation in their funding amounts, as evidenced by the presence of outliers and a wider interquartile range.


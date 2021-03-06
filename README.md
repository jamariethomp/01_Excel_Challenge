# Kickstarting with Excel

## Project Overview

Kickstarter is an online crowdfunding platform known for supporting creative projects and goals; in this case, the relative fundraising success of play-related fundraising campaigns is being examined. To support content creators working on plays, it would be helpful to know 1) the relative success of funding outcomes based on a fundraiser’s launch date and 2) the success rate of funding outcomes relative to a fundraiser’s goals. This analysis seeks to draw conclusions around both questions.

## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date

From the dataset in question, 1,369 theater-related Kickstarter campaigns are being examined over a span of nine years (2009-2017). Each individual campaign is categorized as “successful,” “failed” or “canceled.” For our analysis, we seek to learn the outcome of campaigns over the course of a typical year:

![Theater_Outcomes_vs_Launch.png](https://github.com/jamariethomp/ExcelChallenge/blob/main/Theater_Outcomes_vs_Launch.png)

The above graphic demonstrates the relative success of theater-related fundraising campaigns over the course of nine years, broken down by month. Evidently, theater-based Kickstarter campaigns become progressively more successful starting in the month of April, peak in May, and steadily decline for the remainder of the calendar year. Based on this interpretation, May is the ideal month for theater-based content creators to initiate a crowdfunding campaign on the Kickstarter platform.

### Analysis of Outcomes Based on Goals

To determine the outcome of Kickstarter campaigns relative to their initial fundraising goals, we examine only theater-based projects categorized as “plays,” which makes our dataset more finite than the previous one. In our analysis of outcomes based on goals, we find that each goal range carries with it a distinct rate of success:

![Outcomes_vs_Goals.png](https://github.com/jamariethomp/ExcelChallenge/blob/f98551397df79a9a0167c6a29bfc84275232ba37/Outcomes_vs_Goals.png)

The data and graphic suggest that the most successful play-based Kickstarter campaigns have fundraising goals of $1,000 or less, with a success rate of nearly 80%. The overall trend suggests that the larger the fundraising goal, the less successful the fundraising campaign (except for the $35,000 to $44,999 goal range, which displays a success rate of nearly 70%). Overall, content creators of plays would likely have more success raising money for their campaigns if they can manage to set minimum amounts to their production budgets and, by extension, their fundraising goals.

### Challenges and Difficulties Encountered

The dataset in question provides us with a wealth of information about Kickstarter campaigns that allows us to look at different types of campaigns across-the-board while also allowing us to drill into the data for the specific type of content that we are looking to analyze (in this case, we are looking into theater productions, specifically plays). Greater detail about the successfully funded plays being produced, such as their line-item budgets, themes, production times, etc. would offer even greater insight into the decision-making process behind the most successfully sourced plays. More specifics about the projects themselves (beyond the Kickstarter dataset) would be beneficial in offering content creators more specific advice about their campaigns. Furthermore, more detail about the most successful fundraising goal amounts would be beneficial in determining the outliers in the data, which show a spike in the campaign success rate for campaigns raising between $35,000 and $44,999. It might be helpful if we were able to derive similar data about theater and play productions from other crowdfunding platforms, such as GoFundMe or Patreon.


## Results

- One conclusion that can be drawn from the information provided on theater outcomes of success based on launch date is that crowdsourcing campaigns tend to be most successful when they are launched between April and July, with the strongest changes of success peaking in May. Another conclusion is that out of all campaigns launched, the greatest percentage of failed campaigns launch later in the calendar year, particularly in December.

- The outcomes based on the fundraising goals for each play-based campaign suggest that in general, the smaller the fundraising goal, the greater the chances of fundraising success.

- While the dataset offers a lot of information about Kickstarter campaigns overall, more specific information about projects in question (in this case, the plays) would be beneficial in helping us determine best practices for content creators seeking to manage successful crowdfunding campaigns. Such information might include budgets, themes, specific locations, run times, etc. Further, similar data from similar crowdfunding platforms, would help us to verify our conclusions.

- Other helpful graphics may offer us a comparison of a play-specific analysis of outcomes based on launch date relative to the theater-based graph. Graphics to help us determine and understand outliers (such as a Box and Whisker plot) might also be beneficial.


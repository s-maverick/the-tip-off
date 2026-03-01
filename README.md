# The Tip-Off: How does gender influence tipping behavior in restaurant settings.

**Author:** Sangam Patil

## Introduction

This project investigates the potential existence of gender bias within restaurant tipping culture. Exploring the underlying reasons for gratuity amounts is especially relevant today, as state-level elections have proposed abolishing tips and implementing a minimum wage.

## Methodology

**Experimental Design:** The study utilized a 2x2 factorial design survey experiment.

**Sample Size:** The experiment included a total of 220 participants.

**Scenario:** Participants were presented with an identical dining scenario in which their server makes a small mistake.

**Treatment Variable:** The independent variable was the server's gender, established by randomly assigning participants to view a photo of either a male or female server. This was coded as a dummy variable (1 = male server, 2 = female server).

**Outcome Variable:** The dependent variable was the numeric amount of gratuity (tip) the participant reported they would leave.


## Analysis and Technologies Used

**Environment:** The data was analyzed using R, relying on libraries such as `tidyverse`, `ggplot2`, `dplyr`, and `patchwork`.

**Data Cleaning:** Extreme outliers (tip amounts greater than 49) were removed from the dataset, and percentages were converted into dollar amounts.

**Statistical Testing:** A two-sample t-test assuming equal variance was conducted to compare the mean gratuity amounts between the two server gender groups.


## Results and Findings

**Server Gender:** The t-test resulted in a p-value of 0.3332, leading to a failure to reject the null hypothesis. The analysis concluded that tipping behavior is not significantly influenced by the gender of the server.

**Respondent Gender:** While server gender lacked statistical significance, graphical analysis revealed that the gender of the respondent played a noticeable role. Female respondents were more likely to leave a tip than male respondents. Additionally, female respondents tended to tip more generously, as shown by higher medians in the data distribution.


## Discussion and Future Work

Although the primary hypothesis regarding server gender was incorrect, the data analysis opened new avenues for future exploration. A cursory review of the dataset suggests that female customers might tip out of a sense of obligation, whereas male customers appeared to be more scrutinizing. These observations lay the groundwork for future experiments focused specifically on how the customer's gender factors into tipping amounts.

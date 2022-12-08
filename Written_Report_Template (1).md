# Kickstarting in Excel

## Overview of Project
**Let's Kickstart a PLay**
A playright has come to us to help with her new crowdfunding campaign for her new play **FEVER**
### Purpose
The purpose of this project was to uncover a pattern to determine the right dollar amount to accomplish the goal of making Louise's dreams come true. She has a budget in mind of $10000 and we are going to find out if that is possible. If it is not, then we will find the *sweet spot* for her crowdfunding campaign to succeed.
## Analysis and Challenges
Our first goal was to determine how many play kickstarters succeeded or failed. We found that more succeeded than failed. Once that was accomplished we further broke that down into the mean `=AVERAGE('Successful US Kickstarters'!D:D)` and median `=MEDIAN('Successful US Kickstarters'!D:D)` of each to see if any obvious patterns arose. They did not. So why did some fall short? By using codes such as`=COUNTIFS(Kickstarter!R:R,"plays",Kickstarter!F:F,"successful",Kickstarter!D:D,">=1000",Kickstarter!D:D,"<=4999")` we were able to determine success/fail numbers of campaigns by the asked for amount.
### Analysis of Outcomes Based on Launch Date
![image](https://user-images.githubusercontent.com/111661058/187737586-d66036df-762e-4fb0-8877-b201ffbe5dc0.png)
### Analysis of Outcomes Based on Goals
![image](https://user-images.githubusercontent.com/111661058/187737979-9958a925-1e6e-4844-9ca4-73864d4ed551.png)
### Challenges and Difficulties Encountered
The date, while good, was a little too much and just a little short. Having the Unix time stamp was not difficult but added another step that should have been unnecessary. Being able to decipher types of plays may have helped our client dig deeper into what would help her kickstarter even more.
## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?

 1) Beginning in April there is a distinct uptick in successful campaigns until the end of summer.
 2) The winter is by far the worst time to create a Kickstater campaign.
- What can you conclude about the Outcomes based on Goals?
 
 Funding goals up to $4999 have the greatest chance for success
- What are some limitations of this dataset?

 Again, being able to break down types of plays would have been most helpful.
- What are some other possible tables and/or graphs that we could create?

 We could further divide our outcomes vs goals to find the success/fail rate for every $200 between $0 and $4999.
 Using that data we could cross reference to their launch dates. 

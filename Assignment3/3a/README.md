# Marketa Analytics - Understanding Promotions

# Objective
We need to study and analyse the various modelling techniques used for promotions and build dashboards for various models to facilitate the client to make marketting decisions

# Adstock Modelling

# Clat Document
https://docs.google.com/document/d/1DLM4eJ_ZYoxjd5eog_X3P22VM0B1l3M9zBS8Ym2FdV8/edit#heading=h.7sa4zxkhmsum

# What
We are given a dataset about the adstock sales model for a company and we need to understand and provide our insights on the same
![](https://github.com/Team-11-VKAS/INFO7374DigitalMarketingAnalytics/blob/master/Assignment3/images/table_definition.PNG)

Advertising adstock or advertising carry-over is the prolonged or lagged effect of advertising on consumer purchase behavior. Adstock is an important component of marketing-mix models. The term "adstock" was coined by Simon Broadbent. Adstock is a model of how the response to advertising builds and decays in consumer markets.

TV Adstock has two components:
a. Diminishing Returns: The underlying principle for TV advertisement is that the exposure to TV ads create awareness to a certain extent in the customers’ minds. Beyond that, the impact of exposure to ads starts diminishing over time. Each incremental amount of GRP would have a lower effect on Sales or awareness. So, the sales generated from incremental GRP start to diminish and become constant. This effect can be seen in the above graph, where the relationship between TV GRP and sales in non-linear. This type of relationship is captured by taking exponential or log of GRP.
b. Carry over effect or Decay Effect: The impact of past advertisement on present sales is known as Carry over effect. A small component termed as lambda is multiplied with the past month GRP value. This component is also known as Decay effect as the impact of previous months’ advertisement decays over time.

# Relation of sales to weeks
We can see that there is a repetitive cycle of around 50 weeks.
We are assuming that the sales start on 01/01/2014, so the maximum sales are during the months of May - June and then the sales begin to decrease.
Every year the sales increase and then decrease as compared to the previous year.
The figure below summarises our conclusions.

 ![](https://github.com/Team-11-VKAS/INFO7374DigitalMarketingAnalytics/blob/master/Assignment3/images/basesales-week.PNG)
 
 # Dashboards
 We have the following dashboards:
 
 ![](https://github.com/Team-11-VKAS/INFO7374DigitalMarketingAnalytics/blob/master/Assignment3/images/dashboard1.PNG)
 ![](https://github.com/Team-11-VKAS/INFO7374DigitalMarketingAnalytics/blob/master/Assignment3/images/dashboard2.PNG)
 ![](https://github.com/Team-11-VKAS/INFO7374DigitalMarketingAnalytics/blob/master/Assignment3/images/basesSalesDashboard.PNG)
 
 __________________________________________________________________________________________
 
 # Attribution Modelling
 
 # Clat Document
 https://docs.google.com/document/d/1DLM4eJ_ZYoxjd5eog_X3P22VM0B1l3M9zBS8Ym2FdV8/edit?ts=5e4db30e#
 
Today, people will visit your site several times prior to converting. They'll find your blog post, return directly a week later, and click a retargeting ad the next day. Then, they will finally convert!

So which marketing channel gets credit? Was your blog responsible for the new sale? Or was it your Facebook Ad?

When trying to show clients the value of each marketing channel, it can be difficult. With multiple touchpoints in the buyer journey, each channel plays its part.

These are the questions at the heart of attribution models.

Attribution modeling is a framework for analyzing which touchpoints, or marketing channels, receive credit for a conversion. Each attribution model distributes the value of a conversion across each touchpoint differently.

A model comparison tool allows you to analyze how each model distributes the value of a conversion.

First-click attribution. The other one-touch model, first-click attribution, gives 100 percent of the credit to the first action the customer took on their conversion journey. It ignores any subsequent engagements the customer may have had with other marketing efforts before converting.

Last-click attribution. With this model, all the credit goes to the customer’s last touchpoint before converting. This one-touch model doesn’t take into consideration any other engagements the user may with the company’s marketing efforts leading up to that last engagement.

Linear attribution. This multi-touch attribution model gives equal credit to each touchpoint along the user’s path.
 
Time decay attribution. This model gives the touchpoints that occured closer to the time of the conversion more credit than touchpoints further back in time. The closer in time to the event, the more credit a touchpoint receives.

U-shaped attribution. The first and last engagement get the most credit and the rest is assigned equally to the touchpoints that occured in between. In Google Analytics, the first and last engagements are each given 40 percent of the credit and the other 20 percent is distributed equally across the middle interactions.


 
 
 
 
 

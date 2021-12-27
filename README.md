# Kickstarting with Excel

## Overview of Project

### Purpose
     The purpose of this analysis is to take both the launch dates and funding goals of all the campaigns, and compare that information to the outcome of the campaign, looking for trends.

## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date
     The first thing I did was relate the campaign outcomes to their launch date. I performed this using a pivot table, with filters allowing certain years and categories to be selected. 

### Analysis of Outcomes Based on Goals
     The second chart I made related the successfulness of the campaigns to the funding goal set. I did this using the “countifs” function with the original Kickstarter data set, which allowed me to tally up all the outcomes for each goal cost bracket. 

### Challenges and Difficulties Encountered
     For “Theater Outcomes by Launch Date”, The only challenge I experienced with this chart was the appearance of a “blank” category in my column of “months”. Upon filtering to just the “theater” category, that “blank” category disappeared, though I’m still not entirely certain as to why, since the original chart of data seemed to have a start date for every entry.

     For “Outcomes Based on Goals”, The challenge I experienced with this chart was mastering the “countifs” function, particularly with the goal brackets. I kept trying to pull the text into the function as a string, before realizing I had to use greater/less/equal expressions. Even then, I wasn’t confident in my equations (especially with the zero column for canceled campaigns) until my graph came out identical to the one in the module.

## Results

**- What are two conclusions you can draw about the Outcomes based on Launch Date?**

     The first conclusion I drew was that the launch date didn’t seem to affect the likelihood a campaign would be cancelled, as it remains relatively constant throughout the year (ignoring the gap in October). The likelihood of a campaign failing also doesn’t seem to be affected by start date, aside from a spike in October. 

     The second conclusion I drew is that the month of May seems to be the best month to launch a successful campaign. There’s a noticeable surge in total campaigns from May to August (as seen in the climb shown on both the “successful” and “failed” trend lines), and in that timeframe, May has the highest chance of success (though all four months seem to have a higher likelihood of success than failure).


**- What can you conclude about the Outcomes based on Goals?**

     Aside from the spike in the 35k-45k section of the graph on the “successful” line (which is due to a small sample size at that bracket), Outcomes have the highest percentage of success up to about $15,000. As goals increase beyond that point, the outcome of success decreases inversely.

**- What are some limitations of this dataset?**

     There are a couple limitations that come to mind. The first that comes to mind is that the most recent campaign was in 2017, so the dataset isn’t current. This could influence the conclusions drawn regarding goals met or failed, as the financial situation of the world 4 years ago is different from the world today.

     The second limitation is that the dataset is only based off Kickstarters from a handful of countries. Drawing conclusions from those countries might not be indicative of the trends in different countries. Therefore, if you were using this data for your own kickstarter goal, you’d want to be in one of the countries listed in order for the data to have the highest reliability.

**- What are some other possible tables and/or graphs that we could create?**

     One other graph that could be created is a further drilled down version of the “outcomes based on goal” graph, adding an additional parameter for “country”. You could also do a mirrored version of the “Theater Outcomes Based on Launch Date”, but instead use deadline date. You could then do a different graph for outcomes based on kickstarter duration (end date-start date), to determine if success percentage increases the longer a campaign is.
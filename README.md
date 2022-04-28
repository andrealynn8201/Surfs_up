# Surf’s Up Analysis

## Overview
I was tasked to continue my analysis of whether a surf and ice cream shop is sustainable year round in Oahu.  Specifically the months of June and December, since they are opposite times of the year and they have different temperature variations.

## Results

For the month of June, I was able to write a query that filtered the Measurement table in order to retrieve temps for the month of June.  

![Screen Shot 2022-04-28 at 3 54 56 PM](https://user-images.githubusercontent.com/93801125/165851341-396715fe-575c-401b-989f-56a290a9692a.png)

![Screen Shot 2022-04-28 at 3 57 10 PM](https://user-images.githubusercontent.com/93801125/165851392-60249b2f-1134-4380-b056-d44c1dfc3b4c.png)


I then converted it to a list, then to a DataFrame.  After, I was able to generate the summary statistics by using the ‘.describe()’  function.

Getting the summary statistics, I was able to show:

* How many times the temp was recorded that month
* The average temp for the month
* The minimum and maximum temps for the month as shown below

I completed the same analysis for the month of December, using the same syntax, data and codes, as shown below:

![Screen Shot 2022-04-28 at 4 02 09 PM](https://user-images.githubusercontent.com/93801125/165851445-d31e82cd-39c2-4a27-8dae-dadad2553516.png)

![Screen Shot 2022-04-28 at 4 02 30 PM](https://user-images.githubusercontent.com/93801125/165851462-4f381ac4-8740-4de3-aa64-2130a831150d.png)


## Summary

Using the summary statistics, and comparing the two, the max temp in both is 85 degrees and 83 degrees respectively, and the average being  about 75 and 71 degrees respectively.  

I also created a summary statistics table to compare the temps with precipitation for the months of June and December.  It shows there was very little rainfall for either month, and if so, it didn’t last, as seen in these images.

![Screen Shot 2022-04-28 at 4 42 24 PM](https://user-images.githubusercontent.com/93801125/165851571-16c9b910-0e39-4e5e-bd40-5558fc6f1dcc.png)

![Screen Shot 2022-04-28 at 4 42 55 PM](https://user-images.githubusercontent.com/93801125/165851618-f4f5962c-f913-4315-a579-fe0447b0f43a.png)

I then created a bar graph to visualize how many instances each temp were recorded for that month. 

![Screen Shot 2022-04-28 at 4 43 25 PM](https://user-images.githubusercontent.com/93801125/165851661-27c9aab0-9693-435d-b2be-3492bed509ab.png)

![Screen Shot 2022-04-28 at 4 43 34 PM](https://user-images.githubusercontent.com/93801125/165851680-5555b269-efa7-4d6d-a6e1-8fe47ee0842b.png)


In June, there were at least 100 instances or more, within 30 days,  where the temp was between about 71 degrees and 79 degrees. In December, there were at least 100 instances or more where the temp was between about 65 degrees and 77 degrees.

These temps indicate a pretty stable temperature environment, with little precipitation throughout the year.  Although temps fluctuate, and can be higher or lower, the environment needed to establish a surf and ice cream shop seems to be there in Oahu, according to the data.

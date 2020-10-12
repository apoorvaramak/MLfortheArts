<span style= "font-size:16px"> **Who collected and compiled it?**</span>

The collector is the City of Chicago, so it is a government run dataset. It was compiled by someone that works for the City of Chicago, but that is unspecified on the dataset.

<span style= "font-size:16px"> **Why was it collected?**</span>

It is collected to see how many crashes there are in the city of Chicago. This is collected to see where and when crashes are more likely to happen. This can be used for a variety of things, such as having the police in certain areas at times that have higher instances of crashes, or to warn people driving then about the higher instance of crashes on the boards that hang above the highway.

<span style= "font-size:16px"> **How was it collected?**</span>

It is collected by reports from the Chicago Police Department. So these are only crashes that are severe enough to have the police called, and are only the area within the Chicago Police Department’s jurisdiction. 

<span style= "font-size:16px"> **Describe the data: What are the dimensions? What are the variables and their data types? What can the first 5-20 rows tell us?**</span>

There are 53 columns and 450,000 rows. There are many variables, but the ones that are most interesting are the estimated crash time, the speed limit at the crash site, the injuries, and the type of crash. Most of this is qualitative data, so they are Strings. The first 5-20 rows can show us a lot depending on how the table is sorted. If sorted by most recent, there is a lot less information, especially because some of the data of more recent accidents are withheld purposefully until a later date. If you sort by the fatality of the accident, you can see the amount of fatal hit-and-run accidents that have happened recently. Or, you can find where and under  what conditions the most fatal accidents happen.

<span style= "font-size:16px"> **Is there missing, incorrect, or otherwise problematic data?**</span>

There is a lot of missing data, such as report numbers for more recent accidents. A lot of other data that is missing is the column that says whether or not photos were taken of the accident, which seems important in the case of a fatal crash. The amount of lanes in the road where the accident happened is also largely empty. Some of this missing data could be problematic because not having data on where the crash happened could make finding where crashes happen harder. For example, if it was a 4 lane highway versus an intersection that makes a big difference. Also, some of the data is up to the officers discretion, so whether or not an intersection was involved is all up to the officer reporting it. That could be problematic because the police officer might report one thing that they think is true but is actually not representative of what actually happened. 

<span style= "font-size:16px"> **For whom is this data accurate or useful? What is this data unrepresentative of? (Who is missing and left out of the data?)**</span>

This data is accurate and useful for certain tasks, such as finding out what time and what streets specifically crashes happened. So, if you were trying to see when and where exactly crashes are more likely to happen, this data set would be helpful. However, if you were looking for something that is less filled out, like if there was an intersection involved in the crash, the data would not be as accurate or useful because there is a lot of data missing in that column.

<span style= "font-size:16px"> **Knowing what you know now about machine learning, what will a model trained on this data help you do? Are there alternative (non-machine learning) methods you could use instead?**</span>

A model trained on this could be able to predict where the most crashes will be by street and what time they would happen. It would also be able to determine how likely the crash is to be fatal given the time and street that the crash occurred. An alternative method could be just figuring which streets are more likely to have crashes and what times are more likely to have crashes and put those together to figure it out, but this would be much less accurate because it would not take in as many factors at the same time. 




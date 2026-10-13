# 2014/2015 New Year's Resolutions on Twitter: Data Analysis

An Excel dashboard analyzing 2015 New Year's Eve tweets, built using tools such as Power Query, Pivot Tables, Pivot Charts, Slicers, Timelines, and Linked Pictures.

## Data Source Segmentation in Power Query

I structured the data segmentation by referencing the folder path and file name (with its extension) to make it easy to download and analyze the data independently. 
After downloading the repository, you only need to update the folder path to the location where you saved the raw dataset on your local machine.

![Data Segmentation](data%20segmentation/Zrzut%20ekranu%202026-10-12%20212448.png)

## Cleaning

### Power Query
First, I performed data cleaning in Power Query. This involved changing data types, extracting data from columns, removing unnecessary columns, and replacing specific values to standardize the dataset.

![Cleaning in PQ](cleaning/cleaning%20in%20PQ.png)

### Excel
In Excel, I performed some additional data cleansing that came to mind after the initial Power Query processing. I also wrote a complex formula to extract hashtags. The goal was to count how many hashtags were in a cell and then replicate that quantity in an extracted column. However, it didn't work perfectly because the hashtags weren't always grouped together—some were at the beginning and others at the end of the tweets. As a result, I extracted some of them manually, as combining all these edge cases into a few formulas proved too overly complex.

![Hashtags Extraction](cleaning/HASHTAGS%20EXCTRACTION.png)

## Ideas

I brainstormed a color palette that aligns with the topic of the analysis. In the same spreadsheet, I also noted down a few key questions I wanted to ask the data.

![Data Analysis Question Ideas](ideas/data%20analysis%20question%20ideas.png)

Those weren't the only ideas—I created samples of data visualizations as well, which I ultimately implemented in my final dashboard.

![Dashboard Ideas](ideas/dashboard%20ideas.png)

## Final Dashboard

### Linked Pictures
While finalizing data visualizations in my target dashboard spreadsheet, I encountered an issue with Pivot Tables: they were losing their cell formatting when resizing due to applied filters. The solution was to copy these Pivot Tables to another spreadsheet and link them to the final dashboard as pictures.

![Data Linked as Pictures](final%20dashboard/data%20linked%20to%20dashboard%20as%20pictures.png)

### Dashboard and Analysis

![Final Dashboard](final%20dashboard/final%20dashboard.png)

Tweets regarding 2015 New Year's Eve were created relatively equally by both females and males. 

The most common tweet category was **Personal Growth**, regardless of gender. The differences appeared in the second and third most popular categories. Almost 20% of women's posts were about **Health & Fitness**, and less than 14% were humorous. On the other hand, the leading category for men after Personal Growth was **Humor** (about 24%), followed by Health & Fitness (slightly over 15%).

Importantly, the dashboard reveals a psychological trend: when a chapter of our lives comes to an end, we tend to summarize our recent achievements. Most of us want to improve ourselves and set plans for the upcoming period. A large portion of people also want to spend this time having fun, staying positive, and sharing their energy with others.

The biggest demographic difference lies in the distribution of the **Career** category. More males than females tweeted about career goals. However, the data doesn't suggest a narrative like "men struggle more, bring home more money, or work harder." Not at all! What stands out to me is how we complement each other. Women in this dataset posted more about how we feel at home, our relationships, organization, and often finances, while men brought more humor to the timeline. That’s wonderful! Every perspective is important in our society, and we should respect each other and be thankful for the relatives around us.

It's been a while since these 2014/2015 New Year's resolutions were made. I can't wait to see what happens in the last quarter of this year and analyze how people's mindsets have changed over the last 12 years!

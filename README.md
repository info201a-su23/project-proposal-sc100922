# Final Project Proposal

## Unveiling the Magnitude of Gun Violence in the United States

### Lufei Chen   lufeic@uw.edu
### Hongye Lin   hlin9@uw.edu
### Shipei Huang shipeh@uw.edu
### Wendy Bu   wsb22@uw.edu

### 7/28/23

## Abstract

Our main question is to analyze the geographic patterns and temporal trends of gun violence incidents in the United States. This question is important because it allows people to identify high-risk areas and to find potential ways to prevent gun violence. To address the question, we will conduct a comprehensive analysis of the dataset obtained from Kaggle, examining changes in the frequency of gun violence incidents over time and exploring potential patterns or correlations with demographic factors.

## Keywords
1. Gun Violence
2. Public Safety
3. Social Impact

## Proposal

1. Introduction  

> Briefly introduce your project.  Include 3-5 research questions. What motivates the questions? Why are they important? (at least 200 words)

Gun violence is a serious problem that affects residents in the United States. Our project aims to analyze the geographic patterns of gun violence and the reasons behind gun violence in the United States by using the dataset we found from Kaggle. The dataset includes date, location, number of people that were killed, and number of people that were injured of each gun violence incident that were documented from 2013 to 2022. 

The research questions that we'll be focusing on are:
- How has the number of gun violence incidents changed over time in different states and cities?
- Are there any seasonal or temporal patterns in gun violence incidents?
- Does gun violence differ in cities, suburbs, and rural areas?
- Does demographic factors such as age, gender, and ethnicity intersect with gun violence trends?

The motivation behind our research questions is driven by an urgent need to combat gun violence in the United States. We want to figure out if there’s any certain trends of gun violence by either location, group of people, seasons of the year, etc. By analyzing these questions, we can better understand gun violence and the potential reasons behind it. Since it affects the safety and well-being of all residents in the United States, studying the trends over time and across different areas can help us to learn more about the factors that contribute to gun violence and find ways to prevent it.

2. Related Work  

> Describe your topic and related work in this space. You must include 3 citations to related work (URLs to similar work, high quality articles from the popular press, research papers, etc. ) Please use a standard citation style of your choice. (at least 200 words)

Our topic is investigating the gun violence happened in past several years around the United States. Firstly, We analyze from the locations and draw a map to show which area is affected by gun violence most and least. Secondly, we analyze from the time, we will compare the data through the timeline to find out the rising and falling rate of gun crimes in some areas. Thirdly, we analyze the number of injuried people and death to speculate the type of un-supervised gun around that area. Besides these, we will keep doing more researchs based on the dataset and get more meaningful results. Finally, The result of analysis can be used by the federal governments to enhance security work or used by local government to improve citizens' safety. Why we are doing this analysis? We want to make this land under our feet to become a safer and more trust-worthy environment for anyone who lives than any moment before.

Related Work: 
- "GUN VIOLENCE IN AMERICA AN ANALYSIS OF 2018 CDC DATA". The Educational Fund to Stop Gun Violence. https://efsgv.org/wp-content/uploads/Gun-Violence-in-America_An-Analysis-of-2018-CDC-Data_February-2020.pdf, February 2020.
- "What the data says about gun deaths in the U.S." JOHN GRAMLICH. https://www.pewresearch.org/short-reads/2023/04/26/what-the-data-says-about-gun-deaths-in-the-u-s/, APRIL 26, 2023.
- "GUN VIOLENCE PROBLEM ANALYSIS SUMMARY REPORT Washington, D.C." National Institute forCriminal Justice Reform. https://cjcc.dc.gov/sites/default/files/dc/sites/cjcc/release_content/attachments/DC%20Gun%20Violence%20Problem%20Analysis%20Summary%20Report.pd, December 2021.


3. The Dataset

> Where did you find the data? Please include a link to the data source
> 
We found the data set from Kaggle: https://www.kaggle.com/datasets/emmanuelfwerr/gun-violence-incidents-in-the-usa. This is the source of the data set:  https://www.gunviolencearchive.org 
 
> Who collected the data?
>
The data was collected from the Gun Violence Archive (GVA).
> How was the data collected or generated?
>  
GVA collects data from most law enforcement, government, and commercial sources on a daily basis to provide people with real-time data. Kaggle users then selected data from the GVA website for analysis.
> 
> Why was the data collected?
> 
The data was collected to raise awareness of the magnitude of the problem of gun violence

>How many observations (rows) are in your data?
>
The data set has two files: all_incidents.csv has 472820 observations, and mass_shootings.csv has 3609 observations.
>How many features (columns) are in the data?
>
There are seven features in the data.
> What, if any, ethical questions or questions of power do you need to consider when working with this data?
>
The dataset includes the geographical location of the incidents. Although the data doesn't include names, it's still necessary to protect the privacy of the individuals involved.
The collected data may be biased, which can reduce the accuracy of data analysis.
The topic of gun violence is sensitive, so sensitivity is extremely important when presenting results.
> What are possible limitations or problems with this data?   (at least 200 words)
>
The data may face the challenge of incompleteness, meaning not all gun violence incidents are included in the dataset. Incidents in populous areas might be more likely to be exposed and reported, while gun violence incidents in less populated areas may go unreported. Therefore, this could reduce the representativeness and reliability of the data. Additionally, due to societal complexities and existing biases, there may also be biases in the collected dataset of gun violence incidents, potentially distorting results. This can reduce the validity and accuracy of the data. This is because the data on gun violence comes from various places such as the government, media, law enforcement departments, etc. For instance, media organizations often decide which gun violence incident to report based on its news value, thus introducing bias; given the sensitivity of the topic of gun violence, governments, and law enforcement may hide the true situation, leading to data bias. Moreover, the dataset lacks specific background information. Society is complex, and if we record just the location of the gun violence incidents, the data and analysis obtained would be one-sided. Only by understanding the different economic and political conditions in each state can we analyze these factors in detail as to the causes of gun violence incidents. 

These issues might lead to incorrect analysis and recording of the data, causing misconceptions about gun violence incidents, which is a challenge for the dataset.


4. Implications

> Assuming you answer your research questions, briefly describe the expected or possible implications for technologists, designers, and policymakers. (at least 150 words)

For technologists, our project can build predictive models that can forecast potential gun violence hotspots and identify the patterns of these incidents. We can also do data visualization to communicate the patterns and trends in gun violence effectively. Different technologists can revise or improve their projects for their own purposes based on our data visualization. 

For designers, they can effectively decide when/where to sell their products (to make maximum profits and keep the communities safe at the same time). It enables designers to consider the needs of all users (all people), including victims' families, community leaders, and law enforcement personnel when designing platforms or tools to address gun violence, ensuring that the solutions are effective and beneficial to all users.

For policymakers, they can rely on our model to make informed decisions on gun violence prevention strategies. Also, knowing the areas with the highest rates of gun violence can let them allocate resources to those regions appropriately. This targeted approach can maximize the impact of interventions.

5. Limitations & Challenges
>What challenges or limitations might you need to address with your project idea more broadly? Briefly discuss. (at least 150 words)

One of the limitations is that our data doesn’t include the specific type of gun that shooters prefer to use. We believe that there will be certain types of guns that attackers prefer to use in these violent incidents. Through analyzing the guns, we can give suggestions to gun sellers or manufacturers about your sell strategies. For example, they can reduce the amount of sales at certain times or seasons when gunshot cases are expected to reach the peak based on our model. Another challenge we might have is related to policy. The gun laws are not consistent throughout all the States. Different states have different policies on gun control. And these policies are frequently being revised or changed, meaning that the gunshots may not have a constant pattern as we expected. The changing government policy can make our model hard to predict trends because our model is based on the assumption that policy is fixed. Thus, we may have a larger statistic marginal error bar.

Acknowledgements
>
Thank you to our team members for working together!

# Group-Project2

## Global Shark Attack Data Visualization Project 

## Group Repositories

Group 21479_4

Lena Dindayal - https://github.com/lenadindayal/Group-Project2

Jonathan Troyer - https://github.com/jonathantroyer31/Group-Project-2

Carol Hubach - https://github.com/lilyathey/Project2.git

Lily Athey - https://github.com/carolhubach/Group-Project-2.git

Valerie Penaranda - https://github.com/valerieep/Group-Project2


## Describing your dataset and what data it contains:
Our group used Kaggle to find a dataset suitable for data visualization and analysis. While browsing the available datasets, we were intrigued by the dataset “Global Shark Attacks.” This data set had 16 columns: Case Number, Date, Year, Type, Country, Area, Location, Activity, Name, Sex, Age, Injury, Fatal (Y/N), Time, Species, and Investigator or Source. Case number is the identifier for the attack. “Date” and "Year” correspond to the date and year of the attack. The “Type” column refers to if the attack was provoked, unprovoked or invalid. “Country” has all the countries where the attack happened while “Area” goes more in depth to which specific area in the country. “Location” goes even further and refers to the specific location of the attack. “Activity” details what someone was doing when the attack happened. The “Name” column houses data of all the names of people who were attacked. The “Sex” column refers to the sex of the people who were attacked (M or F). Similarly, the age of the person attacked is in the “Age” column. The “Injury” column stores the injury involved in the attack such as “Lacerations” while “Fatal(Y/N)” column stores whether the person involved in the attack died or not. The column “Time” displays the time of the attack. Next, the column “Species” houses the species of the shark involved in the attack. Lastly, the “Investigator” column has the investigator of the attack and acts as a source column. The dataset also had 6303 rows which means that this dataset went very far back in time (1800s) and recorded attacks since then. Most of the data types in this dataset are String data except for the “Date” column

## The 2 questions the team generated and why they are interesting and important:
1. What location had the most shark attacks in the last 10 years (globally/in the US)?  
      a. What country has the most shark attacks?   
      b. Create a map of the different attacks in that country?

The first question we asked related to which country has the most shark attacks in the last ten years. This question is important as it can provide insight into which geographic areas may have a higher risk of shark attacks. This information can be useful for tourists, people going to the beach, and surfers, as well as for coastal communities to help mitigate attacks and for safety measures. By displaying this data with a map, people can see which country has a higher volume of attacks. This question ties to the data set of “Global Shark Attacks.” 

Next, we wanted to go a step further and see which specific areas had the most shark attacks in the country with the most shark attacks. By evaluating the prevalence of shark attacks in specific locations, we are able to see which places might be less appealing to travel to due to a high volume of shark attacks. 


2. What activities led to the most shark attacks since 1998?  
      a. Which of these led to the most fatalities?  
      b. How many were provoked vs. unprovoked 

We posed an overarching question related to which activities led to the most shark attacks. This was important to us to ask because regular civilians might be interested to know which activities have a higher risk of shark attacks for safety purposes. Knowing which activities are more likely to result in shark attacks can help people make informed decisions about how to stay safe in the water. People can take extra safety precautions or avoid those activities altogether if they know which activities are more associated with shark attacks. Similarly, for research purposes, knowing which activities are more likely to result in shark attacks can help researchers better understand shark behavior and ecology. This research can be used to develop measures for reducing the risk of shark attacks, maybe through technology.  Lastly, understanding which activities are more related to shark attacks can inform conservation efforts to protect shark populations. Conservationists can use the data to focus on reducing threats to help protect both sharks and people.

Going along this question, we wanted to ask about the correlation between the activities and the fatality rates. If one activity has a much higher fatality rate than another, people might find that information helpful for the same safety, research, and conservation purposes. Ultimately, displaying which activities lead to more deaths, can allow people to make more informed decisions in the water and then also, help researchers come up with ways to deter shark attacks. 

Next, we wanted to dig deeper into which of these attacks were provoked versus unprovoked. This is important because some attacks are more probable than others if they are provoked. We wanted to display how activities, fatality rates, and the type of the attack were related to ultimately inform public safety and help people find ways to reduce the risk of future attacks. 

## The manipulations applied to the data set as part of the analysis:
The first set of manipulations that we performed on the data set were concerning finding a way to make the data more uniform. We had to go through certain columns and change the data so that we could analyze and visualize it. For example, we went through and changed all of the “Date” data so that they were in the same day-month-year format. Another manipulation we made was cutting down the data set. Because there were over 6000 rows of data and we did not need a majority of them, we refined the data set in order to have less clutter clouding the data we were actually using and to fit the relevant time frame. The data ranged from 1843-2018 but we were only interested in looking at the past 20 years, so the data we ended up with ranged from 1998-2018. Ultimately, there were a lot of different uses for the “Find & Replace” function while cleaning up this data set. For example, in the “Date” column some of the cells started with “Reported,” “Between,” or “Circa,” which we had to change using the “Find & Replace” Excel function. 

Next, we removed the “Name” column from the dataset because there was no need to know the name of someone who was in a shark attack. Moreover, there were errors in the data in this column since some rows would not have a name but rather the sex of the person attacked which is redundant given that the “Sex” column already exists. 

In Tableau, we sorted all the activities into 22 different groups based on their descriptions. Before, there were over 150 different activities, but grouping them allowed us to see a more overall view of which activities. For example, the “Fishing” group includes activities such as “Fishing for tarpon” and “Fishing for sharks.”

## Analysis and Results:
The first question we asked created two maps that allowed our group to effectively analyze the most popular locations of shark attacks both globally and then within the US. The first map created was to visualize exactly which country had the most reported shark attacks. That map showed the group that the US was the leading country in attacks. From there, we wanted to make a more detailed map of specifically the US to find out what regions or states had the most attacks. The US has a lot of coastline, and this map helped the group differentiate between places like the leading state Florida which recorded 287 attacks from 2008-2018. This number accounts for over half of the recorded attacks within the time period and allows viewers to see and understand just how serious the shark attack problem is in Florida compared to other states. The next state with the most attacks was Hawaii with 83 attacks but this is nothing compared to Florida's number. If these maps were to become public, it may deter people from vacationing in Florida which would weaken the state's economy because it is so heavily supported by tourism. Although most vacationers know that Florida has shark attacks, if they were to see this data their eyes may be opened to exactly how threatening this possibility really is. This map could also urge the citizens or government to add and enforce more safety measures in order to lessen this number or at least be more prepared on what to do when an attack happens.

The next question asked took a deeper look into the most dangerous activities regarding the possibility of shark attacks. Millions of people do water-based activities everyday which could lead to an attack, but the number of people who are actually attacked is much smaller. Regardless, it is important to be aware of the most dangerous activities so that those who partake in them can be properly educated on how to prevent and react to attacks. We first created a bar chart so that we could see exactly which activities had the most frequent rate of attack. The bar chart showed that surfing was by far the most dangerous activity when it comes to shark attacks. Swimming was in second place, but had a fraction of the amount of reports that surfing has. Surprisingly, although swimming is far less popular than surfing, swimming had a recorded 56 fatalities where surfing only had 29 fatalities. From this graph, we can conclude that surfing is the most dangerous activity when it comes to being a part of a shark attack, but swimming is the most dangerous regarding dying from a shark attack. These conclusions lead us to believe that swimmers need to be educated on the danger of swimming and prepared with better ways to react and survive if an attack is to happen. Surfers could also use education regarding what to do in the event of an attack and how to best support the other surfers around them if they are attacked. Further, the vast majority of all attacks were, not surprisingly, unprovoked. The surfing category had only 11 provoked attacks, but fishing had 76 provoked attacks compared to 46 unprovoked. The activity with the largest majority of provoked attacks was the “Messing with Sharks” group. This group includes events such as “Attempting to lasso a shark” and “Grabbing a shark for a selfie”, so this comes as no shock to us.  

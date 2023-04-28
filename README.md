# **Tableau Gun Violence Statistics Project**



# **Members (Group 21482)**

Christian Myrie (https://github.com/crm50057/GunViolence-/blob/main/README.md)

Ben Satinoff (https://github.com/bss63709/Gun-Violence/blob/main/README.md)

Josh Berman (https://github.com/joshbrmn/Gun-VIolence-by-State)

Chandler Denton (https://github.com/cld39518/GunViolence/blob/main/README.md)

# **Dataset Description**
**Where It Was Obtained:**

We obtained the dataset from Kaggle. 

**Dimensions:**

There are 7 columns and 56,794 rows after filtering the data for 2021. 

**Column Names:**

The Column Names are: Incident ID, Date, State, City, Address, Number Killed, Number Injured

**Data Types:**

Numerical, Date, String, Geographical, Calculated Numerical

# **Our Questions**
**Question One:**

What are the total number of people affected by gun violence _by state_ in 2021?

**Why is this Important?**

This is important because it allows us to see the magnitude of the effect that gun violence has on the different states. It allows us to see just how much of a problem gun violence is in the United States and it can help raise awareness of the issue. Another reason for its importance is for the sake of safety. By seeing our chart it is possible to see what are the safest states and what are the most violent. You can see which states are the safest to travel to or the safest to move to.

**Question Two:**

How much gun violence is there in each _individual city_ in the United States in 2021?

**Why is this Important?**

Knowing the amount of gun violence in individual cities of the United States gives you a good viewpoint of how each state is specifically affected. Overall it may seem like certain states are safe, but by looking at our map you can see that in certain locations that is not the case. You can see which cities that you should avoid when thinking about traveling or moving. This map also allows for us to question or make assumptions about gun violence in the United States. For example, Illinois seems like one of the more dangerous states, but by looking at the map you can see that almost all of the gun violence comes from Chicago. This brings up the question why there is so much violence in Chicago, and allows us to question what we can do to fix it. It also shows us that you could visit Illinois but avoid Chicago.

# **Manipulations**

First we manipulated the dataset to remove the years 2013-2020 and 2022. This left us with just 2021 as it has the most recent data. The purpose of removing these years is 2022 did not have data for the whole year and threw off our anlaysis, and we wnated to see more recent data so people could know where to live based on recent statistics not what happened nearly a decade ago. 

We also calculated the total # of people affected by gun violence. Affected as in killed or injured, not as in imapcted such as surviors families. We did this by creating a calculated field that summed the number of people killed and injured by gunviolence. The purpose of this is to see not just how many people are killed, but how many people are shot at as that better encompassses what we believe is gun violence. 

# **Analysis & Results**

**States Map**
<img width="1415" alt="Screenshot 2023-04-28 at 2 22 52 PM" src="https://user-images.githubusercontent.com/129543675/235224620-ce319fa4-061d-4fa2-ae17-19da13daa455.png">

In this graph the darker the color the more gun violence there is. The three states with the most gun violence in order are Illinois, Texas, and California. I find this interesting because I did not think that out of all of the states Illinois would have the most violence. From this graph it seems that outside of California, east coast states are more violent than west coast states. 



**Cities map**
<img width="1414" alt="Screenshot 2023-04-28 at 2 22 14 PM" src="https://user-images.githubusercontent.com/129543675/235224680-24faa06c-7b22-465a-9c3f-6ae8e33a8d37.png">

This graph shows a view of gun violence in the United States, specific to each city. Each dot represents a city in the United States with gun violence, and the size of the circle represents the magnitude of gun violence in the individual city. The larger the circle the more gun violence. We are able to see that most gun violence is in the east or west coast, with the midwest being relatively unaffected. One thing that was surprising was just how dangerous Chicago was. According to the map there is over 3.5x more gun violence in Chicago than the entire state of Maine, New Hampshire, Vermont, Rhode Island, Massachusetts, and Connecticut combined. You could use this information to figure out the safest places to relocate or travel.



**Total Killed and Injured across USA in 2021**
<img width="1399" alt="Screenshot 2023-04-28 at 2 23 32 PM" src="https://user-images.githubusercontent.com/129543675/235224696-f155e2f2-3e99-4e02-a53a-274afca68337.png">

This graph shows that around 21k people were killed by gun violence, around 41k people were injured by gun violence, totaling to around 62k people affected by gun violence via death or injury.

# **Tableau Packaged Workbook**

The packaged workbook is added as a file in the repository.

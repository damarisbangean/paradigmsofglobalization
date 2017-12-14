# Epic Epoch by country names 
Here we run an Epic Epoch on Cortext to analyze the most frequently occuring country names in the World Bank reports. 

An Epic Epoch is a simple script for tracking dramatic changes in the composition of a field over time. It acts in three steps:
- First, the N most frequently occurring entities are selected at each time period,
- A frequency timeline is built for each of the selected terms
- A bump graph shows the evolution of frequency and ranking through time


# How to run an Epic Epoch? 

First, we run a Name Entity Recognizer (which allows us to identify and index names, places, and organizations). As we want to focus on places, we choose the GPE on the corpus to extract the most frequently occuring terms, and we standardize the list names to avoid double counting names when they might just be the same place (i.e. The United States, the US, the U.S. all become different recognizable forms of the "United States"). 

Below is our "clean" list of country names that we will use: 

### Term List

> <iframe src="https://docs.google.com/a/sciencespo.fr/spreadsheets/d/1tF_U7ZMbhaeNWkYaYExDcN3MQUNGQczto7o-nxAzUkw/edit?usp=sharing" frameborder="0" style="overflow:hidden;border:1px solid #DDDDDD;" width="800" height="800" allowfullscreen></iframe>

Once we have our "clean" list of country names, we run an Epic Epoch. 


Unsurprisingly, the US figures most prominently throughout the reports. But, smaller countries also rise and fall over time, as evidenced by major world events.  
- Indonesian mass killings of 1965–1966
- Japan’s rise in 1990 at the start of its financial crisis
- Poland’s 1989 revolution against Communism
- Bosnian genocide 1995 
- West bank and Gaza 1993/1995 
- Bangladesh 2004 tsunami
- Start of Arab spring December 2010

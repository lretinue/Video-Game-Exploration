# Video-Game-Exploration
## Dataset
The data consists of information regarding 16291 video games, including Rank,Name,Platform,Year,Genre,Publisher,NA_Sales,EU_Sales,JP_Sales,Other_Sales ,Global_Sales. The dataset can be found [here](https://www.kaggle.com/gregorut/videogamesales).
But in this exploration, we only use 8108 records and 9 features(Name,Platform,Genre,Publisher,NA_Sales,EU_Sales,JP_Sales,Other_Sales ,Global_Sales).  
**Platform:** DS,PS2,PS3,Wii,360,PSP,PS,PC,XB,GBA,GC,3DS,PSV,PS4,N64,SNES,XOne,SAT,WiiU,2600,NES,GB,DC,GEN,NG,WS,SCD,3DO,TG16,PCFX,GG  
**Genre:** Action,Sports,Misc,Role-Playing,Shooter,Adventure,Racing,Platform,Simulation,Fighting,Strategy,Puzzle  
**Publisher:** Electronic Arts,Activision,Namco Bandai Games,Ubisoft, Konami Digital Entertainment.  
## Summary of Findings
In the exploration, I found that there was a strong relationship between global price and platform, publisher, and genre. Action and sport games have higher global sales than other genres. Global sales median do not vary much by genre and by publisher. However, it does vary by platform.  
Outside of the main variables of interest, it is interesting to see that NA and EU sales are the best indicators for global sales, especially for NA sales.
## Key Insights for Presentation
For the presentation,I focus on just the influence of platform, publisher and genre,leaving out the intermediate derivations. I start by global sales variable, followed by distribution of platform, publisher, and genre. Afterwards, I introduce each of the categorical variables one by one vs Global Price. In the end, I plot them on 3 heatmaps to see relationship among 3 variables.

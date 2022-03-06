# surfs_up
weather analysis for opening a surfing store

## Overview of the analysis
This project is to analyze Oahu's weather, an island in Hawaii, to support the business decision of openning a surf shop and persuade investors to back up this business plan. Since the operation of the surf shop depends a lot on the weather, we analyzed the dataset of Oahu's weather from 2010 to 2017 by using SQLite and Python. Here shows the temperature analysis results of June and December for every year in the challenge file. We also have analyzed the precipitation over all the time and the activity levels of different stations to locate an ideal spot for the surf shop in another climate_analysis file.


## Results
This is the summary statistics for the June and December temperatures from 2010-2017.

![Oahu's temperature in June](https://github.com/ZiwenLyu/surfs_up/blob/main/june_temp.png) ![Oahu's temperature in December](https://github.com/ZiwenLyu/surfs_up/blob/main/dec_temp.png)

- From the statistics summary we can know that, the average, minimum, maximum temperature in June and December are very close on Oahu. It states that the winter and the summer on Oahu don't change a lot. It may has very stable temperatures all over the year without any significant seasonal change.
- Second, the average temperatures in June and December are exceeding 70F. Also, the 25% quartile temperature in June and December both are around 70F, which suggests that Oahu is very warm in the winter and the summer. 
- Thrid, from the minimum temperature, maximum temperature, and standard deviation in June amd December we can know that the temperature change within a month is also insignificant, indicating that the weather of Oahu is steady. 

## Summary
Based on the warm weather and the stability of it for Oahu, opening a surf shop may be recommended in June and December. 

In order to dive more into this analysis, I also performed the precipitation analysis in June and December.

![Oahu's precipitation in June](https://github.com/ZiwenLyu/surfs_up/blob/main/june_prcp.png) ![Oahu's precipitation in December](https://github.com/ZiwenLyu/surfs_up/blob/main/dec_prcp.png)
From the average we know that, the precipitation in June and December is quite low, and precipitation in December is little bit more than June's. But we also notice that the median of precipitation is not zero both for June and December, indicating that at least half of these two months are raining. So, we may need to dive more into the dataset to more dive into specific stations.

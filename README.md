# Citi Bikes Tableau

Since 2013, the Citi Bike program in New York City has implemented a robust infrastructure for collecting data on the program's utilization. Each month, bike data is collected, organized, and made public on the Citi Bike Data webpage.

However, while the data has been regularly updated, the team has yet to implement a dashboard or sophisticated reporting process. City officials have questions about the program, so your first task on the job is to build a set of data reports to provide the answers using Tableau. 

Dats provided was collected from July and December 2022.


# Summary

Your task in this assignment is to aggregate the data found in the Citi Bike Trip History Logs and answers to the following questions.

1. What is the difference in total rides in July and December?

    - Total rides in July were 3,497,390

![Alt text](<Screen Shot 2024-01-09 at 2.20.20 PM.png>)

    - Total rides in December were 1,649,652

![Alt text](<Screen Shot 2024-01-09 at 2.20.52 PM.png>)

There were clearly more rides in July likely due how warm it is while it gets very cold in December in New York.

2. What were the most popular start stations?

    - In July, the top 5 stations were:

        - West St & Chambers St

        - W 21st & 6th Ave

        - Broadway & W 58th

        - Broadway & E 14th

        - 6th Ave & W 33rd St

![Alt text](<Screen Shot 2024-01-09 at 2.32.10 PM.png>)

    - In Dec, the top 5 stations were:

        - W 21st & 6th Ave

        - 1st Ave & E 68th St

        - Broadway & W 58th

        - University Pl & E 14th

        - 6th Ave & W 33rd St

![Alt text](<Screen Shot 2024-01-09 at 3.07.34 PM.png>)

3. What were the most popular end stations?

    - In July, the top 5 stations were:

        - West St & Chambers St
        
        - W 21st & 6th Ave

        - Broadway & E 14th

        - 12th Ave & W 40th St

        - Broadway & W 58th

![Alt text](<Screen Shot 2024-01-09 at 3.08.25 PM.png>)

    - In Dec, the top 5 stations were:

        - W 21st & 6th Ave

        - 1st Ave & E 68th St

        - Broadway & W 58th

        - University Pl & E 14th

        - 6th Ave & W 33rd St

![Alt text](<Screen Shot 2024-01-09 at 3.08.49 PM.png>)

4. What are the most popular days? Outliers?

    - July

![Alt text](<Screen Shot 2024-01-09 at 2.52.40 PM.png>)

- Most of the days numbers were consistently high with the excpetion of July 4th weekend which is a popular time for local citizens to be out of town. July 18th was also an outlier but after further investigation I discovered there was torrential raintorms that day as described in this article: https://ny1.com/nyc/all-boroughs/weather/2022/07/18/parts-of-city-experienced-heavy-flooding-monday-afternoon

    - December

![Alt text](<Screen Shot 2024-01-09 at 3.09.24 PM.png>)

- Most days are consistent with a few outliers. December 11th had lower than usual numbers due to snow storm as shown in this article: https://www.news10.com/weather/12-11-2022-snow-day-sunday/. December 16th also had a low day due to another storm that came in: https://www.fox5ny.com/news/winter-storm-new-york-city-snow. December 25th was also low due to Christmas.

5. What were the popular times?

    - July

![Alt text](<Screen Shot 2024-01-09 at 3.13.26 PM.png>)

    - December

![Alt text](<Screen Shot 2024-01-09 at 3.14.02 PM.png>)

- Both graphs are consistent with each other in that their peak rental times coincide with rush hour.

6. Create a static map that plots all bike stations with a visual indication of the most popular locations to start and end a journey, with zip code data overlaid on top.

* There are gaps in latitude and longitude data as it shows less rides than the previous charts, but that data is still consistent throughout the set.

    - July

![Alt text](<Screen Shot 2024-01-09 at 3.18.03 PM.png>)

![Alt text](<Screen Shot 2024-01-09 at 3.18.11 PM.png>)

    - December

![Alt text](<Screen Shot 2024-01-09 at 3.19.00 PM.png>)

![Alt text](<Screen Shot 2024-01-09 at 3.19.09 PM.png>)

- Both maps are consistent with each other in that despite that change in total rides, more rides start in the center of NYC and end in more resendtial sections. One key differnece between the two maps is that in December, there is less of a variety in end stations as outdoor spaces are less frequented in the winter months than in the summer.

7. Create a Dashboard to show functionality.

    - July

![Alt text](<Screen Shot 2024-01-09 at 3.24.24 PM.png>)

https://public.tableau.com/app/profile/adam.salinas/viz/Citi_Bikes_July_StartDash/StartDashJuly?publish=yes

![Alt text](<Screen Shot 2024-01-09 at 3.24.36 PM.png>)

https://public.tableau.com/app/profile/adam.salinas/viz/Citi_Bikes_July_EndDash/EndDashJuly?publish=yes

    - December

![Alt text](<Screen Shot 2024-01-09 at 3.25.11 PM.png>)

https://public.tableau.com/app/profile/adam.salinas/viz/Citi_Bikes_Dec_StartDash/StartDashDec?publish=yes

![Alt text](<Screen Shot 2024-01-09 at 3.25.19 PM.png>)

https://public.tableau.com/app/profile/adam.salinas/viz/Citi_Bikes_Dec_EndDash/EndDashDec?publish=yes

- In this section I showed the fucnctionality between my Ride Station maps and Popular Stattion graphs. Full functionality can be seen through my links to my public Tableau.

8. Create a story

    - July

![Alt text](<Screen Shot 2024-01-09 at 3.28.40 PM.png>)

https://public.tableau.com/app/profile/adam.salinas/viz/Citi_Bikes_July_Story/Story1?publish=yes

    - December

![Alt text](<Screen Shot 2024-01-09 at 3.29.13 PM.png>)

https://public.tableau.com/app/profile/adam.salinas/viz/Citi_Bikes_Dec/Story1?publish=yes

- In this section I created Tableau Stories that can be viewed through my Tableau public link.





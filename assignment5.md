# Assignment 5

Kaitlin Bell

[WMATA Ridership Dataset](https://docs.google.com/spreadsheets/d/1cDfjV-5x1QB7sLThLQQnEtKsbjoKbJ4H8PPPbYs2wqA/edit?usp=sharing) 

### Questions
1. **Did the decrease in percentage of use between 2019-2020 align with what stations closed?** Some of the closures that took effect on March 26 were justified in the [WMATA press release](https://www.wmata.com/about/news/COVID-19-Service-Update-4-Station-Closures.cfm) by a single day’s numbers. Even with the loss of ridership between March 26-August 16, there were still some stations that remained open that had a higher decrease in percentage between 2019 and 2020. One of the most notable was Navy Yard, which has another metro within a mile, another justiciation for station closures.

2. **Did the decrease in total ridership numbers align with what stations were closed?** This analysis presented a huge disparity in the stations that remained open. For example, Dupont Circle saw a decrease of around 148,000 riders between 2019 and 2020. While the total ridership may be higher than that in the stations that were closed, it shows that closures can’t be justified on one thing — especially a single day’s numbers.

3. **How did the closed stations fare after they were reopened?** Analyzing this showed that quite a few stations began to reopen in July. The most surprising thing from the analysis was that Grosvenor station jumped from 268 to 815 between July and August before leveling back down to the 300s for the rest of the year. It lines up with the ridership portal data, but there could be an issue with that entry.

### Cleaning and Analysis Steps 

- **Cleaning steps:** 
    - Added L’Enfant Plaza into our data set
    - Filtering to only show data from 2019-2020 and put in a separate spreadsheet
    - Filtering out to focus on the months stations were closed ([March 26](https://www.wmata.com/about/news/COVID-19-Service-Update-4-Station-Closures.cfm) - [August 16](https://www.wmata.com/about/news/More-Metro.cfm), focusing on April-July), also put in a separate spreadsheet

- **Question 1** 
    - To get full year totals, I created a pivot table showing only 2019-2020 that calculated the total number of rides for each station
    - From the pivot table, I used the percentage formula =(new-old)/old
    - I separated the pivot tables with filters to create three: open stations, closed for low ridership and closed other station <1 mile away

- **Question 2**
    - This followed a similar format to the previous question, except I calculated the difference (=new-old) instead of the percentage
    - I split the stations up into the three tables again

- **Question 3**
    - Again, I used a pivot table
    - I used the months as a row and filtered out to show only the closed stations for the full months they were closed (April-July)
    - In a second pivot table, I filtered to show the months following the stations’ reopening
    - I also found the difference (=new-old) between July and August to have an easier way to see the inital change

# Can a single day’s numbers justify a Metro station’s closure?

WMATA’s temporary station closures in the early days of the pandemic cited “extremely low-ridership” for eight of the stations. The agency provided a single day’s total as justification, despite conflicting percentage losses at other stations.

# NbaAveragePlayer

This project analyzes the statistics for the average NBA player since the 1979-80 season (when the 3 point shot was first introduced). I sourced my data from basketball-reference, and took into consideration 20 different statistics: PTS, REB, AST, STL, BLK, TOV, PF, FG%, 3PT% FT%, TS%, 3PAr, FTr, REB%, AST%, STL%, BLK%, TOV%, PER, and USG%. In order to remove outliers, I only considered "rotational players", who either played at least 70% of the games in a season, or played the equivalent of 1000 minutes in an 82 game season.

After analyzing over 25000 data points over 43 seasons, I developed an interactive dashboard of the data, alongside a report. Here were some of the main takeaways:
* The 3 pointer continuously became more common in the league, however it truly began to skyrocket at different times for different positions. For point guards, shooting guards and small forwards, there was a spike in 3PAr during the mid 1990s, when the league temporarily shortened the 3pt line, and after that spike, the 3 point grew at a much faster rate for these positions. For Power forwards, they didn't truly embrace the 3 point shot until the 2010s, where the 3PAr skyrocketed from 0.1009 in 2011-12 to 0.4054 in 2021-22 (indicating that PF were shooting 4x as many 3 pointers). For Centers, their 3PAr rose from 0.0139 to 0.1648 over the same period. This could be due to Dirk winning a championship in the 2010-11 season, proving that a shooting big can lead a team to a ring, as well as the influx of shooting bigs such as Karl-Anthony Towns.

* Because of the increased shooting across the league, especially the massive jump for power forwards during the 2010s, Centers deviated away from the other positions in terms of BLK%, FTr, REB%, FG%, TS% and PER. This is due to the increased spacing making power forwards spend more time on the perimeter, allowing for Centers to play more in the paint, leading to more rebounds, more efficient shots and more fouls.

* Based off of a similarity score that considered how much a players stats deviated from the average players stats, Franz Wagner in 2021-22 had the most average season relative to his position in NBA history, followed by Grant Hill in 2010-11 and Jeremy Lamb in 2017-18. Rodney Rogers was the most average for his position for the longest time of 7 years, followed by Kelly Olynyk at 6 years.

Below is a link to the article, which goes more in depth with the analysis, alongside a link to a dashboard if you want to play with the data yourself.

Dashboard (Optimized for tablets/desktop/laptop): https://public.tableau.com/app/profile/jaden.noronha/viz/HistoricalAverageNBAPlayer/Dashboard1?publish=yes

Article: https://medium.com/@jpnoro2003/analyzing-the-average-nba-player-from-1979-80-to-2021-22-8c7556b07b49

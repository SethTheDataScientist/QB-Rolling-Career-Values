# QB-Rolling-Career-Values
Welcome! This is my attempt to answer the hardest question in football; is your Quarterback good enough?

The first folder is WAR-EPA. These plots represent my homebrew version of PFF's Wins Above Replacement value as well as the Opponent and Win Probability adjusted Expected Points Added per play by game. The values are a rolling career average on a percentile scale from all QB's from 2011-2021. There is a decaying weight for the first 8 games in the sample just to help smooth out the beginning of the graph.


![Baker Mayfield Career Rolling Per-Game WAR and EPA](https://user-images.githubusercontent.com/81538390/151229687-1506c5fe-d701-4ba3-815e-45424fb04757.png)


The Second Folder is Structure-Playmaker. These plots represent my attempt to quantify a QB's Playstyle. Structure is composite metric that takes into account play in more stable environments such as clean pocket, quick passing, etc. Playmaker takes a similar approach but uses more volatile metrics such as under pressure, longer pass plays, and rushing ability. I used PFF grades, Big Time Throws, Turnover-Worthy Plays, and efficiency by each facet to create the composite values. These are also on a percentile scale. 



![Andrew Luck Career Rolling Per-Game Structure vs Playmaker](https://user-images.githubusercontent.com/81538390/151229712-00c86812-f5c5-41a9-8d6c-57d76624af96.png)


Finally, there is a folder for QB Clustering. This folder takes the values of Playmaker, Structure, and stability of Structure play both on a game-to-game and year-to-year measure, along with growth from the QB's first Structure Value to their Last Structure Value. The growth measure is to separate out players like Andrew Luck, who have low yearly stability because they improved yearly, from players like Baker Mayfield, who wildly change with no pattern of growth.


![Andrew Luck  Seasons](https://user-images.githubusercontent.com/81538390/151229760-275a8b4e-0e48-47e2-89d8-a51cdfa21d36.png)

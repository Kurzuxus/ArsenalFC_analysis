# ArsenalFC_analysis
Exploring a comprehensive analysis of Arsenal FC's 2023 Premier League performance. Uncover match insights and key moments that shaped the season for the Gunners.

## Introductory
This repository serves as a personal project I decided to do in order to ameliorate different skills sets such as data acquiring, cleaning organazing, manipulating and visualizing. I went ahead and picked a topic that's in the realm of my interest which is Football and the team I support Arsenal, Although I can assure you that this analysis is objective and I prefer to let the stats and numbers speak about the performance.

As you browse this repository, you will most certainly come across some mistakes or errors, be it a coding mistake or typos in the comments I make about the output. I implore you to direct them to me to further assist me in improving my skills.

## Data Dictionary
The following dataset that I would be working in, **TheArsenal.csv**, contains 25 columns in total. I will go to each one and explain what it represents and it's datatype.

* Matchweek: Respresents the matchweek number that the match took place in. It's an object type and I would like to note that this column in particular is suitable to be used as the index for the data frame.

* Day: Represents the day of which that match took place in. The days are in abbreviated format. It's an object type column.

* Time: Represents the time of day the match took place in. It's an object type.

* Venue: Represents the location of where the match took place in, either Home (Emirates Stadium) or Away. It's an object type column.

* Attendance: Represents the attendance number of the match. It's worth noting that before making any aggregate functions, it's an object type and not an integer because of the comma separating the numbers.

* Referee: Represents the referee that was officiating the match. It's an object type

* Oppponent: Represents the name of the team Arsenal faced in the matchweek. It's an object type.

* Result: Represents the outcome of the match with either a Win, draw or a loss. It's a object type column.

* Possession: Represents the possession percentage of Arsenal during the full match. It's an integer type column.

* Goals for: Represents the number of goals  Arsenal scored during the match. It's an integer type column.

* Goals against: Represents the number of goals Arsenal conceded during the match. It's an integer type column.

* Excpected goals (there is a type in the column name): Represents the XG or the probability of Arsenal scoring a goal based on different variables. It's a float type column.

* Shots: Represents the total number of shots Arsenal had in the match. It's an integer type column.

* Shots on target: Represetns the number of shots that Arsenal had that were in the vacinity of the goal frame. It's an integer type column.

* Passes: Represents the total number of passes Arsenal attempted during the match. It's an integer type column

* Passes completed: Represents the total number of passes Arsenal completed succsessfuly during the match. It's an integer type column.

* Short passes, Medium passes, Long passes: These three columns represents the total number of passes attempted distributed based on the range of the pass. They are integer type columns

* Corners: Represents to total number of corners Arsenal had in the match. It's an integer type column.

* Tackles: Represents the total number of tackles or challenges made in the match. It's an integer type column.

* Tackels won: Represents the number of challenges Arsenal won in the match. It's an integer type column.

* Fouls: represent the number of fouls or mistakes Arsenal players commited during the match. It's an integer type column.

* Penalties attempted: Represent the number of penalties awarded to Arsenal in a match. It's an integer type column.

* Penalties made: Represents the number of penalties that were convered succsessfuly into a goal. It's an integer type column.

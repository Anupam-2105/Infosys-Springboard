Sports Craft Company has organized tournaments in multiple individual sports and invited top ranked players to play. Each tournament comprises of multiple matches in knock out format. Each match is played between two players.
Problem Statement: Create the Player table as per information provided below:

Column Name 	Data Type 		Constraint 		Description
PId 			INTEGER 		PRIMARY KEY 	Unique player Id is mandatory for every player
PName 		VARCHAR2(20) 	NOT NULL 		Player Name
Ranking 		INTEGER 					Player's ranking


Query : 

CREATE TABLE Player(
PId INTEGER PRIMARY KEY,
PName VARCHAR2(20) NOT NULL,
Ranking INTEGER
)
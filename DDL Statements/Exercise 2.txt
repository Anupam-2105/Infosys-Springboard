Create the Tournament table as per information below:

Column Name 	Data Type 		Constraint 		Description
TId 			INTEGER 		PRIMARY KEY 	Unique tournament Id for every tournament
TName 		VARCHAR2(30) 	NOT NULL 		Tournament Name
StartDt 		DATE 			NOT NULL 		Start Date of the tournament
EndDt 		DATE 			NOT NULL 		End Date of the tournament
Prize 		INTEGER 		NOT NULL 		Prize to be won in the tournament


Query : 

CREATE TABLE Tournament(
TId INTEGER PRIMARY KEY,
TName VARCHAR2(30) NOT NULL,
StartDt DATE NOT NULL,
EndDt DATE NOT NULL,
Prize INTEGER NOT NULL
)
Add 'MatchesPlayed', 'MatchesWon' columns of type NUMBER to Player table discribed below:

ColumnName		Data Type		Constraint		Description
PId			INTEGER		PRIMARY KEY		Unique Player Id
PName			VARCHAR2(20)	NOT NULL		Player Name
Ranking		INTEGER					Player's ranking
ContactNo		NUMBER(10)					Player Contact Number


Query : ALTER TABLE Player ADD (MatchesPlayed NUMBER,MatchesWon NUMBER)
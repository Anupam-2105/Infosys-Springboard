Drop Column 'ContactNo' from table Player.

ColumnName		Data Type		Constraint		Description
PId			INTEGER		PRIMARY KEY		Unique Player Id
PName			VARCHAR2(20)	NOT NULL		Player Name
Ranking		INTEGER					Player's ranking
ContactNo		NUMBER(10)					Player Contact Number


Query : ALTER TABLE Player DROP (ContactNo)
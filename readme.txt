D:\Dev\IT30A\backups

1. CREATE DATABASE <database_name>;
2. SHOW DATABASES;
3. CONNECT <datanase_name>;
4. CREATE TABLE <table_name_in_plurals> ();
5. INSERT INTO <table_name_in_plurals>
    (columns)
    VALUES(values);

Utitlity Commands
\! cls
mysqldump -u root -p --databases library_db > D:\Dev\IT30A\backups\08182026_library_db.sql

mysqldump -u root -p --databases library_db > "D:\Dev\IT30A\backups\%date:~4%_%date:~4,2%_%date:~7,2%_%time:~0,2%_%time:~3,2%_%time:~6,2%_library_db.sql"

%date:~4%_
%date:~4,2%_
%date:~7,2%_
%time:~0,2%_
%time:~3,2%_
%time:~6,2%_
library_db.sql
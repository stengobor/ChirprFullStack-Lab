CREATE USER 'chirprapp'@'localhost' IDENTIFIED WITH mysql_native_password BY 'password';

GRANT ALL PRIVILEGES ON chirpr.* TO 'chirprapp'@'localhost';


SELECT * FROM chirpr.chirps;
use chirpr;
SELECT * from chirps where chirps.id = 10;
DELETE from chirps where chirps.id = 8;
INSERT INTO chirps (userid, content, location) values (2, "Hello people Hello people Hello people.", "bham")

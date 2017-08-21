[See assignment in Alexa](https://alexa.bitmaker.co/cohorts/72/assignments/2247/latest)


SELECT COUNT(*) FROM dinos;

SElECT * FROM dinos where period ='Jurassic';

SELECT SUM(length) FROM dinos WHERE period='Cretaceous';

SELECT name, species FROM dinos where period ='Jurassic' OR period ='Cretaceous' ORDER BY species;


SELECT name FROM dinos WHERE t_order ='Saurischia' AND diet='Herbivorous';

SELECT name FROM dinos WHERE length=(SELECT min(length) FROM dinos);
SELECT id FROM dinos where name ='Liaoxiornis' ;
UPDATE dinos SET name ='Shortie' WHERE id =160;

SELECT MIN(name) FROM dinos;

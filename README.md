<!--
Modellizzare la struttura di una tabella per memorizzare tutti i dati riguardanti delle auto usate messe in vendita da un concessionario
 -->

USED CARS
id | NOT NULL - INT - AUTO INCREMENT - PRIMARY KEY
brand | NOT NULL - VARCHAR(20)
model | NOT NULL - VARCHAR(20)
version | NOT NULL - VARCHAR(100)
alimentation | NOT NULL - VARCHAR(10)
cylinder capacity | NOT NULL - VARCHAR(10)
power | NOT NULL - CHAR(5)
change | NOT NULL - VARCHAR(10)
horses | NOT NULL - VARCHAR(10)
registration date | NOT NULL - YEAR
kilometres | NOT NULL - INT
co2 emissions | NULL - VARCHAR(10)
iva | NOT NULL - CHAR(1) DEFAULT '1'

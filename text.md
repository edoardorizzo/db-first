/*

Modellizzare la struttura di una tabella per memorizzare tutti i dati riguardanti delle auto usate messe in vendita da un concessionario.

*/

id: BIGINT, PK, NOTNULL
brand: VARCHAR(255), PK, NOTNULL
model: VARCHAR(255),
fuel: VARCHAR(255), PK,
price: FLOAT(6,4), PK,
in-stock: TINYINT, NULL, 
year: YEAR, NULL 
km: MEDIUMINT, NULL, 
trasmission: VARCHAR(255), NULL,
kw: VARCHAR(255), NULL,
cilinder: VARCHAR(255), NULL,
color: VARCHAR(255), NULL,
length: SMALLINT, NULL
height: SMALLINT, NULL
width: SMALLING, NULL
description: TEXT, NULL, 
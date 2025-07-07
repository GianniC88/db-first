# library db

Modellizzare la struttura di una tabella per memorizzare tutti i dati riguardanti delle auto usate messe in vendita da un concessionario

## table name: Cars

-id | BIGINT - PRIMARY_KEY AUTO_INCREMENT NOTNULL UNIQUE

- marca | VARCHAR(100) INDEX NOTNULL
- modello | VARCHAR(100) INDEX NOTNULL
- anno | YEAR NULL
- versione | VARCHAR (100) INDEX NOTNULL

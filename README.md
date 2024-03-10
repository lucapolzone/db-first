# Esercizio: Primo DB (07/03/2024)
nome repo: `db-first`

Modellizzare la struttura di una tabella per memorizzare tutti i dati riguardanti delle auto usate messe in vendita da un concessionario

# Svolgimento

| FIELD                     | TYPE           | ATTRIBUTES                         | INDEXES      |
| ------------------------- | -------------- | ---------------------------------- | ------------ |
| id                        | INT            | UNIQUE, NOT NULL, AUTO_INCREMENT   | PRIMARY KEY  |
| brand                     | VARCHAR(20)    | NOT NULL                           |              |
| model                     | VARCHAR(20)    | NOT NULL                           |              |
| year                      | YEAR           | NOT NULL                           |              |
| color                     | VARCHAR(20)    | NOT NULL                           |              |
| doors                     | TINYINT        | NOT NULL                           |              |
| km                        | MEDIUMINT      | NOT NULL                           |              |
| power                     | VARCHAR(4)     | NOT NULL                           |              |
| displacement              | MEDIUMINT      | NOT NULL                           |              |
| fuel_source               | VARCHAR(20)    | NOT NULL                           |              |
| price                     | FLOAT(8,2)     | NOT NULL                           |              |
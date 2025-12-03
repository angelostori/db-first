# DB Schema
Modellizzare la struttura di una tabella per memorizzare tutti i dati riguardanti delle auto usate messe in vendita da un concessionario

## Table name: cars (Entity name: car)

### Columns:
fields             type             constrains

- id                BIGINT          PRIMARY KEY AUTO_INCREMENT

- brand             VARCHAR(50)     NOT NULL

- model             VARCHAR(50)     NOT NULL

- fuel_type         VARCHAR(50)     NOT NULL

- fuel_consumption  DECIMAL(5,2)    NOT NULL

- km_driven         INT             NOT NULL

- year              YEAR            NOT NULL

- price             DECIMAL(8,2)   NOT NULL

- color             VARCHAR(50)     NOT NULL

- transmission      VARCHAR(50)     NOT NULL

- description       TEXT            NULL

- horsepower        SMALLINT        NOT NULL

- displacement_cc   SMALLINT        NOT NULL

- places            TINYINT         NOT NULL

- doors             TINYINT         NOT NULL

- marches           TINYINT         NOT NULL

- empty_weight      INT             NULL

- emission_class    VARCHAR(50)     NOT NULL

- power             SMALLINT        NOT NULL (*60Kw\h*)

- type              VARCHAR(50)     NOT NULL (*suv, berlina, citycar, ecc.*)

- traction          CHAR(3)         NOT NULL DEFAULT (*2WD*)

- previous_owners   TINYINT         NULL

- image_url         VARCHAR(255)    NULL

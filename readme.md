# DB Schema
Modellizzare la struttura di una tabella per memorizzare tutti i dati riguardanti delle auto usate messe in vendita da un concessionario

## Table name: cars (Entity name: car)

Columns:

- id BIGINT PRIMARY KEY AUTO_INCREMENT
- car_brand VARCHAR(50) NOT NULL
- car_model VARCHAR(50) NOT NULL
- fuel_type VARCHAR(50) NOT NULL
- fuel_consumption DECIMAL(5,2) NOT NULL
- km_driven INT NOT NULL
- year YEAR NOT NULL
- price DECIMAL(10,2) NOT NULL
- color VARCHAR(50) NOT NULL
- transmission VARCHAR(50) NOT NULL
- description TEXT NULL
- car_horsepower INT NOT NULL
- displacement_cc INT NOT NULL
- places TINYINT NOT NULL
- doors TINYINT NOT NULL
- marches TINYINT NOT NULL
- empty_weight INT NULL
- emission_class VARCHAR(50) NOT NULL
- type_of_vehicle VARCHAR(50) NOT NULL
- traction CHAR(3) NOT NULL DEFAULT ('2WD')
- previous_owners TINYINT NULL


## Data Base Name


#### Relation Diagram 
```mermaid
classDiagram

      Animal  "1" --> "N"  Duck
      Animal  "1" --> "N"  Fish
      Animal  "1" --> "N"  Zebra
      
      class Animal{
          *id
          animalId()
          isMammal()
          quack()
          mate()
      }
      class Duck{
          *id
          +animal_id
          quack()
      }
      class Fish{
          *id
          +animal_id
          Fish()
      }
      class Zebra{
          *id
          +animal_id
          Zebra()
  }    
```
#### Tables

| name                                  | type            | Details |
| ------------------------------------- | --------------- | ------- |
| [/TABLE_NAME](tables/tables_template) | temp, table ... |         |



## Dependencies

no se espesifica hasta el metodo

| Database | Server         | Schemes | Tables | permissions |
| -------- | -------------- | ------- | ------ | ----------- |
| Service  | Queue tracking | datas   | test   | 60000       |
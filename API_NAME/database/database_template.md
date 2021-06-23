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

| name                                  | type                      | Details |
| ------------------------------------- | ------------------------- | ------- |
| [/TABLE_NAME](tables/tables_template) | <temp or table or others> |         |



## Dependencies

In this section the dependencies of other tables, loading processes and dblinks are defined.

| Database | Server | Schemes | Tables | permissions         |
| -------- | ------ | ------- | ------ | ------------------- |
|          |        |         |        | read, write, create |

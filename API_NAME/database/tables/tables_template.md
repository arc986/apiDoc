## Table Name


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


##### Description

<The purpose of the table is defined.>

##### Constrains

| name | owner | type | condition |
| ---- | ----- | ---- | --------- |
|      |       |      |           |

##### Foreign Keys

| name | owner | refTable | type |
| ---- | ----- | -------- | ---- |
|      |       |          |      |

##### Indexes

| name | table | unique | tablespace |
| ---- | ----- | ------ | ---------- |
|      |       |        |            |

##### Triggers

| name | table | column | status |comment|
| ---- | ----- | ------ | ------ ||
|      |       |        |        ||

##### Attributes

| Column | Type|null?|length| comment |
| ------ | ----| | |----------- |
|        |     | | |            |


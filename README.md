# SQL-Questions-
## Problem : Occupations 


![sql-question5](https://user-images.githubusercontent.com/83380670/135698678-be1b89d1-9ddc-49f6-9e1b-33bd247eb961.png)
#### QUERY :
![sql-ans5](https://user-images.githubusercontent.com/83380670/135698680-0b14d8c6-ec8f-4b9e-9b59-74a2fcacb7da.png)



## Problem 1 : Type of Triangle 
![sql-question1](https://user-images.githubusercontent.com/83380670/135332427-7c4e6252-346f-4998-a24a-2b73c079301c.png)
#### QUERY:

![image](https://user-images.githubusercontent.com/83380670/135699023-25fb2e39-90ed-46c7-a55d-1887074b0785.png)



## Problem 2 :
![sql-question2](https://user-images.githubusercontent.com/83380670/135344180-fb551687-1314-4a6b-b799-8fdcb933bbdb.png)

#### QUERY : 
SELECT CONCAT (NAME, '(', LEFT(OCCUPATION,1),')') FROM OCCUPATIONS ORDER BY NAME ASC;
SELECT CONCAT ('There are a total of ', COUNT(OCCUPATION), ' ', LOWER(OCCUPATION), 's.') FROM OCCUPATIONS GROUP BY OCCUPATION ORDER BY COUNT(OCCUPATION) ASC, OCCUPATION ASC; 

## Problem 3 :

![sql-question3](https://user-images.githubusercontent.com/83380670/135633834-67a7a6d4-98f1-4871-9a8b-73bfe08b84d6.png)
#### QUERY :
![sql-ans3](https://user-images.githubusercontent.com/83380670/135644564-f4d58c3d-9da9-43d2-9dc3-dcc0bdefc14f.png)

## Problem 4: New Companies 

![sql-question4](https://user-images.githubusercontent.com/83380670/135678116-613e0348-ab02-4ce5-ac0f-cdb0af50ab19.png)
#### QUERY :
![sql-ans4](https://user-images.githubusercontent.com/83380670/135678125-aca8c3d3-5040-4708-b97c-d69531f47f31.png)

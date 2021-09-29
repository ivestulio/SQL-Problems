# SQL-Questions-
## Question 1 :
![sql-question1](https://user-images.githubusercontent.com/83380670/135332427-7c4e6252-346f-4998-a24a-2b73c079301c.png)
#### QUERY:
SELECT 
CASE 
WHEN A + B > C AND A + C > B AND B + C > A THEN
CASE 
WHEN A = B AND B = C THEN 'Equilateral'
WHEN A = B OR B = C OR A = C THEN 'Isosceles'
ELSE 'Scalene'
END 
ELSE 'Not A Triangle'
END 
FROM TRIANGLES ; 


## Question 2 :
![sql-question2](https://user-images.githubusercontent.com/83380670/135344180-fb551687-1314-4a6b-b799-8fdcb933bbdb.png)

#### QUERY : 
SELECT CONCAT (NAME, '(', LEFT(OCCUPATION,1),')') FROM OCCUPATIONS ORDER BY NAME ASC;
SELECT CONCAT ('There are a total of ', COUNT(OCCUPATION), ' ', LOWER(OCCUPATION), 's.') FROM OCCUPATIONS GROUP BY OCCUPATION ORDER BY COUNT(OCCUPATION) ASC, OCCUPATION ASC; 

# SQL PRACTICE QUESTIONS: Fundamentals to Aggregates

This practice sheet covers everything shown in your progress image:  
- Selecting data  
- Filtering (WHERE, AND, OR, BETWEEN, IN, LIKE, NOT LIKE, %, _, IS NULL, IS NOT NULL)  
- Aggregates (COUNT, AVG, SUM, MIN, MAX, ROUND)  
- Sorting (ORDER BY, DESC)  
- Grouping (GROUP BY, HAVING)  
- Comparison operators  
- Arithmetic  

Assume a table called `students` with columns such as:  
`id, name, inter_dom, region, gender, academic, age, stay, japanese_cate, english_cate, todep, tosc, toas, partner, ...`

---

## 1. Selecting Data

1. Show all columns for all students.
2. Show only name, age, and gender for all students.
3. Show the first 10 rows of the table.
4. Show the last 5 rows of the table (hint: use ORDER BY id DESC and LIMIT).
5. Show all unique regions.
6. Show the total number of students.

---

## 2. Filtering with WHERE, AND, OR

7. Show all international students.
8. Show all female students who are undergraduates.
9. Show all students who are either from 'SEA' or 'EA'.
10. Show all students who are not from 'SEA'.
11. Show all students who are under 22 years old.
12. Show all students from 'SEA' who are graduate students.
13. Show all domestic students who are older than 25.
14. Show all students who are either male or have 'High' Japanese proficiency.
15. Show all students who are not female.

---

## 3. Using BETWEEN, IN

16. Show all students aged between 18 and 25 (inclusive).
17. Show all students whose region is 'SEA', 'EA', or 'SA'.
18. Show all students whose age is NOT between 20 and 30.

---

## 4. Pattern Matching with LIKE, NOT LIKE, %, _

19. Show all students whose name starts with 'A'.
20. Show all students whose name ends with 'i'.
21. Show all students whose academic level contains 'Grad'.
22. Show all students whose region has 'A' as the second character.
23. Show all students whose region does NOT start with 'S'.

---

## 5. NULL Checks

24. Show all students whose 'partner' field is NULL.
25. Show all students whose 'partner' field is NOT NULL.
26. Show all students whose 'english_cate' is NULL.

---

## 6. Aggregate Functions & ROUND

27. Show the average age of all students (rounded to 2 decimals).
28. Show the total number of international students.
29. Show the minimum and maximum PHQ-9 (todep) score.
30. Show the average, sum, and count of 'tosc' for all students.
31. Show the average length of stay for domestic students (rounded to 1 decimal).
32. Show the number of students in each academic level.
33. Show the average todep for each region (rounded to 2 decimals).

---

## 7. Sorting

34. Show all students ordered by age ascending.
35. Show all students ordered by depression score (todep) descending.
36. Show all undergraduates ordered by their length of stay, from longest to shortest.

---

## 8. Grouping (GROUP BY, HAVING)

37. Show the number of students in each region.
38. Show the average todep for each academic level.
39. Show the maximum length of stay for each gender.
40. Show the number of students in each Japanese proficiency category (japanese_cate).
41. Show the number of students grouped by region and gender.
42. Show all regions where there are more than 5 students.
43. Show the average toas (acculturative stress) for each region where the average is above 20.
44. Show all academic levels with more than 10 students.

---

## 9. Comparison Operators

45. Show all students whose todep is greater than 10.
46. Show all students whose stay is less than or equal to 2.
47. Show all students whose age is not equal to 21.

---

## 10. Arithmetic

48. Show each student's age plus 2 as 'age_plus_2'.
49. Show each student's todep multiplied by 3 as 'triple_todep'.
50. Show each student's stay divided by 2 as 'half_stay' (rounded to 2 decimals).
51. Show the difference between tosc and toas for each student as 'scs_minus_asiss'.

---

## 11. Combined & Challenge

52. Show, for each region, the number of international students who are older than 25.
53. Show the top 3 regions with the highest average todep score.
54. Show, for each academic level, the average stay and number of students, only for those levels with more than 5 students.
55. Show the number of female graduate students in each region who have a depression score above 10.
56. Show the average todep for each region and academic combination, ordered by average todep descending.
57. Show all students whose todep is above the average todep for all students (use a subquery).
58. Show all students whose age is exactly twice their length of stay.
59. Show the percentage of students in each region (as a decimal, not percentage).
60. Show the average toas for students who have 'High' proficiency in both Japanese and English.

---

**TIP:**  
- Use `SELECT DISTINCT` to get unique values.  
- Use `GROUP BY` for aggregation by groups.  
- Use `HAVING` to filter groups.  
- Use `ORDER BY` for sorting results.  
- Use `ROUND()` to round numeric results.

---

Happy practicing!  
Feel free to add your own answers or solutions to each.
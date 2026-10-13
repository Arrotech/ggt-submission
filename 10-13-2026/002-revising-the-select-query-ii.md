# Revising the Select Query II

> **Topic:** SELECT QUERY<br>
> **Difficulty:** Easy<br>
> **HackerRank:** <https://www.hackerrank.com/challenges/revising-the-select-query-2/problem?isFullScreen=false>

## Intuition / Approach

Approach: Three questions.

Table: CITY
Columns: only NAME (the problem says “the NAME field”, so no *)
Rows: COUNTRYCODE = 'USA' and POPULATION > 120000, joined with AND

## My Solution

```sql
SELECT NAME
FROM CITY
WHERE COUNTRYCODE = 'USA'
  AND POPULATION > 120000;
```

## Reflection

<!-- Note what you learned or what you would revisit. -->

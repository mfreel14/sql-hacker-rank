All Problems Solved On MS SQL Server

## Weather Observation 3

Query a list of CITY names from STATION for cities that have an even ID number. Print the results in any order, but exclude duplicates from the answer.

![1449345840-5f0a551030-Station](https://user-images.githubusercontent.com/691355/157987090-3e60ea3f-e856-47c0-87e9-519392be024c.jpg)

```sql
select distinct CITY from STATION where id%2=0;
```

## Weather Observation 4

Find the difference between the total number of CITY entries in the table and the number of distinct CITY entries in the table.

![1449345840-5f0a551030-Station](https://user-images.githubusercontent.com/691355/157988149-257848f1-afb8-401f-9fa3-9d10c839861f.jpg)

```sql
select count(CITY)-COUNT(DISTINCT CITY) as cityDifference from STATION;
```

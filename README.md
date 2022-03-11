# sql-hacker-rank

Server: MS SQL Server
SQL - Basic Select: Weather Observation 3

Query a list of CITY names from STATION for cities that have an even ID number. Print the results in any order, but exclude duplicates from the answer.

![1449345840-5f0a551030-Station](https://user-images.githubusercontent.com/691355/157987090-3e60ea3f-e856-47c0-87e9-519392be024c.jpg)

```sql
select distinct CITY from STATION where id%2=0;
```

# SQL BOLT EXERCISE 15
### 01 This database is getting too big, lets remove all movies that were released before 2005.

~~~sql
DELETE FROM movies
where year < 2005;
~~~

### 02 Andrew Stanton has also left the studio, so please remove all movies directed by him.

~~~sql
DELETE FROM movies
where director = "Andrew Stanton";
~~~

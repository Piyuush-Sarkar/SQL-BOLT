# SQLBolt - Lesson 2 Answers

## Exercise 1: Find the movie with a row id of 6 ✓


``` sql
SELECT * FROM movies WHERE ID=6;
```

------------------------------------------------------------------------

## Exercise 2: Find the movies released in the years between 2000 and 2010 ✓


``` sql
SELECT * FROM movies WHERE year BETWEEN 2000 AND 2010;
```

------------------------------------------------------------------------

## Exercise 3: Find the movies not released in the years between 2000 and 2010 ✓


``` sql
SELECT * FROM movies WHERE year NOT BETWEEN 2000 AND 2010;
```

------------------------------------------------------------------------

## Exercise 4: Find the first 5 Pixar movies and their release year ✓

``` sql
SELECT * FROM movies LIMIT 5;
```

------------------------------------------------------------------------



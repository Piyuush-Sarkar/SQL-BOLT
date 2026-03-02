# SQLBolt - Lesson 4 Answers

## Exercise 1: List all directors of Pixar movies (alphabetically), without duplicates


``` sql
SELECT DISTINCT director FROM movies
ORDER BY director ASC;
```

------------------------------------------------------------------------

## Exercise 2: List the last four Pixar movies released (ordered from most recent to least)


``` sql
SELECT title, year FROM movies
ORDER BY year DESC
LIMIT 4;
```

------------------------------------------------------------------------

## Exercise 3: List the last four Pixar movies released (ordered from most recent to least)


``` sql
SELECT title FROM movies
ORDER BY title ASC
LIMIT 5;
```

------------------------------------------------------------------------

## Exercise 4: List the next five Pixar movies sorted alphabetically


``` sql
SELECT title FROM movies
ORDER BY title ASC
LIMIT 5 OFFSET 5;
```

------------------------------------------------------------------------

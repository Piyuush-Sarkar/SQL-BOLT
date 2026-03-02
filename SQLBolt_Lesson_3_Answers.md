<<<<<<< HEAD
# SQLBolt - Lesson  3 Answers

## Exercise 1: Find all the Toy Story movies 


``` sql
SELECT title, director FROM movies 
WHERE title LIKE "Toy Story%";
```

------------------------------------------------------------------------

## Exercise 2: Find all the movies directed by John Lasseter


``` sql
SELECT title, director FROM movies 
WHERE director = "John Lasseter";
```

------------------------------------------------------------------------

## Exercise 3: Find all the movies (and director) not directed by John Lasseter


``` sql
SELECT title, director FROM movies 
WHERE director != "John Lasseter";
```

------------------------------------------------------------------------

## Exercise 4: Find all the WALL-* movies
``` sql
SELECT * FROM movies 
WHERE title LIKE "WALL-_";
```

------------------------------------------------------------------------


=======
# SQLBolt - Lesson  3 Answers

## Exercise 1: Find all the Toy Story movies 


``` sql
SELECT title, director FROM movies 
WHERE title LIKE "Toy Story%";
```

------------------------------------------------------------------------

## Exercise 2: Find all the movies directed by John Lasseter


``` sql
SELECT title, director FROM movies 
WHERE director = "John Lasseter";
```

------------------------------------------------------------------------

## Exercise 3: Find all the movies (and director) not directed by John Lasseter


``` sql
SELECT title, director FROM movies 
WHERE director != "John Lasseter";
```

------------------------------------------------------------------------

## Exercise 4: Find all the WALL-* movies
``` sql
SELECT * FROM movies 
WHERE title LIKE "WALL-_";
```

------------------------------------------------------------------------


>>>>>>> a45d2946e0ce6cf08359eb59579f9e908e306bc9

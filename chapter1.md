---
title: 'Why descriptive statistics?'
description: 'Descriptive statistics are the foundation for all statistical analysis, no matter how complex. '
---

## Example coding exercise

```yaml
type: NormalExercise
key: 2bafef99a3
lang: r
xp: 100
skills: 1
```

Many of us learn descriptive statistics when we are in school, often starting fairly young. However, we often learn more about how to calculate them than what they actually mean.  Because we rely on R to do the  calculating for us, we can focus more on the concepts. 

`@instructions`
Let's start with "measures of central tendency" which are often the statistics people know.  For example you may remember the three Ms: mean, median and mode.  Let's review the versions of these that you probably learned in the past.   

To get started we need to create a small set of data called a vector.  Let's call the vector **my_data**  and include the numbers  10, 5, 6, 12, 10, 7, 16.  We create this using the assignment operator <- and the function c().

`@hint`


`@pre_exercise_code`
```{r}

```

`@sample_code`
```{r}
my_data <- c(10, 5, 12, 10, 7, 16)
```

`@solution`
```{r}
my_data <- c(10, 5, 12, 10, 7, 16)
```

`@sct`
```{r}

```

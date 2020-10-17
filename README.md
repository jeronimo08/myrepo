# myrepo


---
title: "BST 625: Assignment 4 (R portion, 5 points in total)"
author: "Jeronimo Alexander Maradiaga"
date: "Due date 10/21/2020"
output: pdf_document
---

```{r setup, include=FALSE}
knitr::opts_chunk$set(echo = TRUE, cache = TRUE)
```

# Question 1 (1 point)

First I wrote down 

```{r}
data <- read.csv("http://courses.washington.edu/b517/Datasets/shoulder.csv")
```

then there is an object created in my environment. Can you guess what I am doing? (1 point) If your answer is no, you still get your point since we have not covered this yet.

```{r}
## write down your answer after "## ---|" in the next line. Provide code as you will
## ----| 
 Read.csv instructs R to read the comma seperated values (.csv) file, which is in table form from the website: 
http://courses.washington.edu/b517.Datasets/shoulder.csv in to the object "data". 

```
# Question 2 (2 points)

Then I wrote

```{r}
Pain_long <- data$pain
```

What is *Pain_long*? (2 points)

```{r echo = TRUE}
## write down your answer after "## ---| in the next line". Provide code as you will
## ----|


```
# Question 3 (2 points)

Conduct some operation on *Pain_long*. In other words, provide any function using *Pain_long* as an input (1 point). Hint: a function is in the format of *function.name()*. Describe your operation in English  (1 point) 

```{r}
## Tell R what you want to do in the next line

## write down your answer after "## ---|" in the next line. Provide code as you will
## ----|
```
# Bonus 

Share something with me about what you learned by yourself **beyond** what we have covered so far (1 point)

```{r}
## Tell R what you want to do in the next line

## write down what is the above command(s) about
## ----|
```

---
title: "LHS R, Practice Questions"
author: "Sandra Nwankwo"
date: "`r Sys.Date()`"
output:
  html_document: default
  pdf_document: default
---

```{r setup, include=FALSE}
knitr::opts_chunk$set(echo = TRUE)
```

```{r}
#load dataset
lhs<-read.csv(file = "C:\\Users\\nwank\\Documents\\PUBH 6450\\Week 1\\lhs.csv", header = TRUE)

#view the first few rows of the data
head(lhs)
```


### Question 1: What is the age of the participant in the third row of the data set?

```{r}
# Access the age column in the third row
age_third_row <- lhs$age[3]

# Print the age
print(age_third_row)

```
### Q2: What data type did R put for the race variable, race? For the clinical center code variable, ACLINIC? For the BMI variable, bmi?

Race is given as an integer
Aclinic is given as a character
BMI is given as a number
```{r}
# summary of dataset
summary(lhs)
```

```{r}

```

```{r}

```

```{r}

```

```{r}

```

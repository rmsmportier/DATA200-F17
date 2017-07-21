---
title       : DATA200 Homework 1
description : What Is Data Science?
attachments :
  slides_link : https://s3.amazonaws.com/assets.datacamp.com/course/teach/slides_example.pdf


--- type:MultipleChoiceExercise lang:r xp:50 skills:1 key:f64165f28a
## What Is Data Science?

Which of the following are critical elements in a data science definition?
*** =instructions
- Complex
- Product
- Extract
- Data
- All of the above

*** =sct
```{r}
# SCT written with testwhat: https://github.com/datacamp/testwhat/wiki

msg_bad1 <- "Partially; Data Science is critical in a complex data world."
msg_bad2 <- "Partially; creating a usable product is the outcome."
msg_bad3 <- "Partially; extracting data from a variety of sources is critical."
msg_bad4 <- "Arguably the most important, but not complete description."
msg_success <- "Correct! Data Science is process to extract complex data sources, gain insight, and create product."
test_mc(correct = 5, feedback_msgs = c(msg_bad1, msg_bad2, msg_bad3, msg_bad4, msg_success))
```

--- type:MultipleChoiceExercise lang:r xp:50 skills:1 key:b317628b08
## Data Science Lifecycle

Put the following into correct lifecycle order
*** =instructions
- Tidy, Import, Communicate, Exploratory Data Analysis
- Communicate, Tidy, Exploratory Data Analysis, Import
- Import, Tidy, Exploratory Data Analysis, Communicate
- Import, Exploratory Data Analysis, Tidy, Communicate
*** =hint

*** =pre_exercise_code
```{r}

```

*** =sct
```{r}
# SCT written with testwhat: https://github.com/datacamp/testwhat/wiki

msg_bad <- "That is not correct"
msg_success <- "Correct!"
test_mc(correct = 3, feedback_msgs = c(msg_bad, msg_bad, msg_success, msg_bad4))

```

--- type:MultipleChoiceExercise lang:r xp:50 skills:1 key:f0c95f0fa1
## Internet of Things (IoT)

Which of the following is *not* an IoT device example?
*** =instructions
- Kitchen appliances
- Cell phone
- Shoe
- Game systems
- None of the above
*** =hint

*** =pre_exercise_code
```{r}

```

*** =sct
```{r}
# SCT written with testwhat: https://github.com/datacamp/testwhat/wiki

msg_bad1 <- "Many kitchen appliances are Wi-Fi enabled."
msg_bad2 <- "Cell phones are one of the early Wi-Fi enabled devices."
msg_bad3 <- "There are smart shoes to point you in right direction."
msg_bad4 <- "Most modern game systems are Wi-Fi enabled."
msg_success <- "Correct!  Each of the above is an example of IoT device, and the list continues to grow daily."
test_mc(correct = 5, feedback_msgs = c(msg_bad1, msg_bad2, msg_bad3, msg_bad4, msg_success))


```

--- type:MultipleChoiceExercise lang:r xp:50 skills:1 key:906f04005f
## "Datafication"

Which of the following accurately describes the concept of "datafication"?
*** =instructions
- Creating a database of your music files
- Creation of a data footprint from moment of our birth
- Tracking student's course progress
- Medical charts to track patient history


*** =hint

*** =pre_exercise_code
```{r}

```

*** =sct
```{r}
# SCT written with testwhat: https://github.com/datacamp/testwhat/wiki

msg_bad <- "That is not correct"
msg_success <- "Correct!"
test_mc(correct = 2, feedback_msgs = c(msg_bad, msg_success, msg_bad, msg_bad4))


```

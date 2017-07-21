---
title       : DATA200 Homework 1
description : What Is Data Science?
attachments :
  slides_link : https://s3.amazonaws.com/assets.datacamp.com/course/teach/slides_example.pdf


--- type:MultipleChoiceExercise lang:r xp:50 skills:1 key:f64165f28a
## What Is Data Science?

Which of the following are part of data science definition?
*** =instructions
- Complex
- Product
- Extract
- Data
- All of the above

*** =sct
```{r}
# SCT written with testwhat: https://github.com/datacamp/testwhat/wiki

msg_bad <- "That is not correct!"
msg_success <- "Correct! Data Science is process to extract complex data, gain insight, and create product."
test_mc(correct = 5, feedback_msgs = c(msg_bad, msg_bad, msg_bad, msg_bad, msg_success))
```

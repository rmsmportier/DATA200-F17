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
test_mc(correct = 3, feedback_msgs = c(msg_bad, msg_bad, msg_success, msg_bad))

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
msg_success <- "Correct! 'Datafication' is a phrase coined in *The Rise of Big Data* that describes how our society has shifted in our cultural acceptance of technology.  No aspect of our lives is left untouched."
test_mc(correct = 2, feedback_msgs = c(msg_bad, msg_success, msg_bad, msg_bad))

```

--- type:MultipleChoiceExercise lang:r xp:50 skills:1 key:523fe644f1
## *Big Data*

Which of the following is not an example of *Big Data*?
*** =instructions
- Large number that requires scientific notation
- Satellite images
- Scientific measurements collected from a sensor at nanosecond intervals
- Amazon website "click history" logs

*** =hint

*** =pre_exercise_code
```{r}

```

*** =sct
```{r}
# SCT written with testwhat: https://github.com/datacamp/testwhat/wiki

msg_bad1 <- "Satellite images store significant quantities of complex data and are an example of *Big Data*."
msg_bad2 <- "This would likely be an incredible quantity of data and precision and is an example of *Big Data*."
msg_bad3 <- "Data is gathered and stored for every click for every user for every second.  This is an example of *Big Data*."
msg_success <- "Correct! The level of precision is significant, but the quantity of information is not as this is only one data value."
test_mc(correct = 1, feedback_msgs = c(msg_success, msg_bad1, msg_bad2, msg_bad3))

```

--- type:MultipleChoiceExercise lang:r xp:50 skills:1 key:8d9b4e0293
## Computer Speak

What mathematical *language* is foundational to digital computers?
*** =instructions
- Base 10 (decimal)
- Base 16 (Hexadecimal)
- Base 2 (Binary)
- Base 8 (Octal)

*** =hint

*** =pre_exercise_code
```{r}

```

*** =sct
```{r}
# SCT written with testwhat: https://github.com/datacamp/testwhat/wiki

msg_bad <- "Incorrect.  Computers can interpret this language, but not foundational."
msg_success <- "Correct! At the heart of the computer is the binary language."
test_mc(correct = 3, feedback_msgs = c(msg_bad, msg_bad, msg_success, msg_bad))

```

--- type:MultipleChoiceExercise lang:r xp:50 skills:1 key:22d1d455d6
## Types of Computer Data

987.356 in a computer is an example of which data type?
*** =instructions
- Boolean
- Alphanumeric or Character
- Numeric
- Date/Time

*** =hint

*** =pre_exercise_code
```{r}

```

*** =sct
```{r}
# SCT written with testwhat: https://github.com/datacamp/testwhat/wiki

msg_bad <- "That is not correct."
msg_success <- "Correct! We know it is numeric because of the digits, decimal point, and no other punctuation."
test_mc(correct = 3, feedback_msgs = c(msg_bad, msg_bad, msg_success, msg_bad))

```

--- type:MultipleChoiceExercise lang:r xp:50 skills:1 key:d3b6422247
## Types of Computer Data Take 2

"987.356" in a computer is an example of which of the following data types?
*** =instructions
- Boolean
- Alphanumeric or Character
- Numeric
- Date/Time

*** =hint

*** =pre_exercise_code
```{r}

```

*** =sct
```{r}
# SCT written with testwhat: https://github.com/datacamp/testwhat/wiki

msg_bad <- "That is not correct."
msg_bad1 <- "That is not correct.  Notice the quotes around the numbers."
msg_success <- "Correct! We know it is alphanumeric because even though it seems to be a number there are quotes around value."
test_mc(correct = 2, feedback_msgs = c(msg_bad, msg_success, msg_bad1, msg_bad))

```

--- type:NormalExercise xp:100 skills:1 key:15d729634a
## How it works

In the editor on the right you should type R code to solve the exercises. When you hit the 'Submit Answer' button, every line of code is interpreted and executed by R and you get a message whether or not your code was correct. The output of your R code is shown in the console in the lower right corner.

R makes use of the `#` sign to add comments, so that you and others can understand what the R code is about. Just like Twitter! Comments are not run as R code, so they will not influence your result. For example, _Calculate 3 + 4_ in the editor on the right is a comment.

You can also execute R commands straight in the console. This is a good way to experiment with R code, as your submission is not checked for correctness.

*** =instructions
- In the editor on the right there is already some sample code. Can you see which lines are actual R code and which are comments?
- Add a line of code that calculates the sum of 6 and 12, and hit the 'Submit Answer' button.

*** =hint
Just add a line of R code that calculates the sum of 6 and 12, just like the example in the sample code!

*** =pre_exercise_code
```{r}
# no pec
```

*** =sample_code
```{r}
# Calculate 3 + 4
3 + 4

# Calculate 6 + 12

```

*** =solution
```{r}
# Calculate 3 + 4
3 + 4

# Calculate 6 + 12
6 + 12
```

*** =sct
```{r}
test_output_contains("18", incorrect_msg = "Make sure to add `6 + 12` on a new line. Do not start the line with a `#`, otherwise your R code is not executed!")
success_msg("Awesome! See how the console shows the result of the R code you submitted? Now that you're familiar with the interface, let's get down to R business!")
```

--- type:NormalExercise xp:100 skills:1 key:720745eda5
## Arithmetic with R

In its most basic form, R can be used as a simple calculator. Consider the following arithmetic operators:

- Addition: `+`
- Subtraction: `-`
- Multiplication: `*`
- Division: `/`
- Exponentiation: `^`
- Modulo: `%%`

The last two might need some explaining:

- The `^` operator raises the number to its left to the power of the number to its right: for example `3^2` is 9.
- The modulo returns the remainder of the division of the number to the left by the number on its right, for example 5 modulo 3 or `5 %% 3` is 2.

With this knowledge, follow the instructions below to complete the exercise.

*** =instructions
- Type `2^5` in the editor to calculate 2 to the power 5.
- Type `28 %% 6` to calculate 28 modulo 6.
- Click 'Submit Answer' and have a look at the R output in the console.
- Note how the `#` symbol is used to add comments on the R code.

*** =hint
Another example of the modulo operator: `9 %% 2` equals `1`.

*** =pre_exercise_code
```{r}
# no pec
```

*** =sample_code
```{r}
# An addition
5 + 5 

# A subtraction
5 - 5 

# A multiplication
3 * 5

 # A division
(5 + 5) / 2 

# Exponentiation


# Modulo

```

*** =solution
```{r}
# An addition
5 + 5

# A subtraction
5 - 5 

# A multiplication
3 * 5

 # A division
(5 + 5) / 2 

# Exponentiation
2 ^ 5

# Modulo
28 %% 6
```

*** =sct
```{r}
msg = "Do not remove the other arithmetic examples!"
test_output_contains("2^5", incorrect_msg = "The exponentiation example is not correct. Write `2 ^ 5` on a new line.")
test_output_contains("28 %% 6", incorrect_msg = "There seems to be an issue with the modulo example. Write `28 %% 6` on a new line.")
success_msg("Great! You have completed Homework 1.")
```

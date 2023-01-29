# Welcome to the R Debugging GitHub Repository!

This repository is dedicated to providing resources and tools to help users debug and troubleshoot their R code. Some helpful links are listed below!

## **Debugging Techniques:** A collection of common techniques and best practices for debugging R code.

- Debugging Guide From Hadley Wickham - https://adv-r.hadley.nz/debugging.html

- Debugging Guide from Data Flair - https://data-flair.training/blogs/debugging-in-r-programming/

- Debugging Zine (paid, but very cool). - https://wizardzines.com/zines/debugging-guide/

- A useful rant about working directories - https://www.tidyverse.org/blog/2017/12/workflow-vs-script/

## **Error Codes and Solutions:** A list of common R error messages and their explanations, as well as solutions to fix them.

Chat GPT suggested this section, which I otherwise wouldn't have written! So I asked ChatGPT to fill out it's own section. Here's what it gave (with slight edits from me). 

Here is a list of some common R error messages and explanations, along with solutions to fix them:

 - "Error: object 'x' not found" - This means that R cannot find the object 'x' in the current environment. The solution is to check the spelling of the object, and make sure it has been defined or loaded properly.

 - "Error in if (x) { : missing value where TRUE/FALSE needed" - This means that the if (or any conditional) statement is trying to evaluate a missing value. The solution is to check the values passed to the if statement and ensure that they are not missing.

 -   "Error in x[y] : object of type 'closure' is not subsettable" - This means that the object being indexed is a function, not a vector or data frame. The solution is to check the object being indexed and make sure it is a vector or data frame, or use the appropriate function to extract the desired information.

 -   "Error in library(x) : there is no package called 'x'" - This means that the R interpreter cannot find the specified package. The solution is to check the spelling of the package name and make sure it is installed on your system.

  -  "Error in file(file, ifelse(append, "a", "w")) : cannot open the connection" - This means that R cannot open the specified file. The solution is to check the file path and permissions, and make sure that the file is accessible by R.

  -  "Error: unexpected symbol in: "x <- c(1, 2, 3) +" - This means that there is an unexpected symbol, such as a typo, in the R code. The solution is to check the code for typos and correct them, most commonly this is a missing comma or parentheses, or providing the wrong arguments to a function call.

 -   Warning: In x + y : longer object length is not a multiple of shorter object length - This means that the vectors being added have different lengths, and R is recycling the shorter vector to match the length of the longer vector. This can cause unexpected results and it is recommended to check the lengths of the vectors and make sure they match before performing any operations.

  -  Error in parse(text = x) : <text>:1:0: unexpected end of input - This means that there is a problem with the R code being parsed, often due to a missing parenthesis or bracket. The solution is to check the code for any missing or extra characters and correct them.

  -  Warning: NAs introduced by coercion - This means that R is introducing missing values (NA) due to a type coercion. This can happen when trying to combine different types of data, such as characters and numerics. The solution is to check the data types of the variables and make sure they are compatible before performing any operations.

  -  Error in x[y == z] : invalid subscript type 'list' - This means that the subscript used to index the object 'x' is not a valid type, such as a list. The solution is to check the type of the object being used to index 'x' and make sure it is a valid type such as a logical vector, numeric vector or character vector.

  -  Error in x[y] <- z : replacement has length zero - This means that the object being used to replace the values in 'x' has a length of zero. The solution is to check the object being used for replacement and make sure it has the same length as 'x' or the corresponding index.

  -  Warning: Non-ASCII characters are being interpreted as ASCII - This means that R is interpreting non-ASCII characters as ASCII characters. This can cause unexpected results and it is recommended to check the encoding of your data and make sure it is in the correct format before performing any operations.


This is just a few of the most common errors in R, but there are many other types of error messages that can occur in R. Keep in mind that the best way to troubleshoot R errors is to read the error message carefully and look for clues about where the error is occurring in your code.

## **Code Examples:** A collection of example R scripts that demonstrate various debugging techniques and common error scenarios.

These include just two RMarkdown files

1. 1_raw_gpt_output.Rmd - A Rmd produced as a collaboration with ChatGPT, that was recorded for the videos (link here soon). 

2. 2_debug_existing_code.Rmd - A Rmd with intentionally broken chunks of code. 

3. 3_debugging_ChatGPT.Rmd


# Contributing

We welcome contributions from the community! If you have a debugging technique, error code explanation, or example script that you would like to share, please submit a pull request.
Support

If you have any questions or need help with debugging your R code, please feel free to open an issue in the repository. We will do our best to respond in a timely manner.

Happy debugging!

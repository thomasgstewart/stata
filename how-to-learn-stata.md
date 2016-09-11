---

layout: default
title: How to learn STATA

---

## HOW (General purpose advice for learning any software)

>**KEY CONCEPT**: Powering up your computer will not magically endow you with understanding of your task.

1. Understand your task *before turning on the computer*.

   * Calculate sample size.
   * Generate descriptive tables.
   * Calculate an association.
   * Develop a predictive model.
   * Run a simulation.

1. Identify the inputs of your task *before turning on the computer*.

   * What is your data source? (file, url, etc)
   * What is the file format of your data? (.csv, .xlsx, .tsv, .dta, .sas7bdat)
   * How are your data organized?
      * Do rows represent observations or variables?
      * What do the columns represent?
      * Does each row contain data from a unique observation?
      * Are there multiple rows for each observation?
      * Are longitudinal variables in the long or wide format?
      * etc.

1. Identify the specific output of your task *before turning on the computer*.

   * What information will you include in the descriptive table?
   * What data will you plot?
   * What characteristics of the predictive model will you report?
   * etc


## YOUR FIRST HOUR LEARNING STATA

>**KEY CONCEPT**: In your first hour learning STATA, focus on the big picture.  Don't worry about specific tasks, rather familiarize yourself with the organization of STATA documentation and other STATA resources.

1. Read and work the examples in [Introducing Stata—sample session](http://www.stata.com/manuals14/gsu1.pdf) which is the first chapter of [Getting Started with Stata](http://www.stata.com/bookstore/getting-started-unix/)

1. Become familiar with the list of topics in [Getting Started with Stata](http://www.stata.com/bookstore/getting-started-unix/) and [STATA documentation](http://www.stata.com/features/documentation/).  Make a mental note of the various resources available to you.

1. Become familiar with the topics available at [idre UCLA](http://www.ats.ucla.edu/stat/stata/).  Excellent site with many examples.  Often called "the UCLA site" among STATA users.


## YOUR SECOND HOUR LEARNING STATA

>**KEY CONCEPT**: For your second hour learning STATA, be hands on.  Pick a simple, everyday task to learn.  I recommend a task in [Introducing Stata—sample session](http://www.stata.com/manuals14/gsu1.pdf).

1. Choose a simple task to learn that has an example
1. Identify the inputs of the task
1. Run the code in the example, line by line
1. For each new command, skim the documentation.  Type `help` `command-name`.
1. Skim the different command options. Re-run the command with different options to see how the output changes.
1. Identify the output.  Confirm that the task is complete.


## RESOURCES FOR A SPECIFIC TASK (UNKNOWN COMMAND)

1. Type `help` `task` into STATA
1. Google


## RESOURCES FOR UNDERSTANDING THE DOCUMENTATION FOR A SPECIFIC COMMAND

1. Type `help` `command` into STATA, for example, `help correlate`
1. Note:
   * In the title, `correlate` is a hyperlink to more extensive documentation.
   * In the syntax, the output is a `correlation matrix`
   * Menu will show you how to navigate to the menu.
   * If you know the command, you can always type `db command` as in `db correlate` to open the command menu.  db stands for "Dialogue Box".
   * Options are explained in greater detail after the description
   * **ALWAYS LOOK AT THE EXAMPLES**
   * Many help documents include links to YouTube help vides.  Look near the end of the documentation.

   ##
   [*BACK TO FRONT PAGE*](index.html)

## Working with databases

The resources in this repository are intended to help instructors and students move from working with data in files and R data frames to working with data in databases.

### Getting Started

[SQLite-GettingStarted.Rmd](SQLite-GettingStarted.Rmd) will walk you through 

 * installing and loading the necessary R packages
 * creating  a simple SQLite database (containing four tables) on your local machine.  
 
The data are a subset of a much larger database of airline delays.
Each of these tables is stored as a CSV.  The result is a modestly sized data base
with which one can learn basic data base operations in R.  By default, 
this will be created in the directory where the Rmd file is located, but you can
edit the code (or move the file) if you prefer to have this located in a different
directory.

**Note:** Compiling this file will take some time because of the data retrieval.
When successfully compiled, an sqlite data base file will be created locally.
Additional work with the data base only requires this one file, so there is no reason
to reknit this file unless you need to recreate the datase file.

## Some additional SQLite examples

Knitting the Getting Started RMarkdown file will download [an additional Rmd file](SQLite-Testing.Rmd) that can 
be used to test the SQLite data base that was created or to see more examples of accessing data from
a data base.

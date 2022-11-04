# Text Data Partitioning

This assigmnent is "HomeWork" of Data Science Applications to manipulate the data ("Gutenberg's couple of digital books") and serialize them.

## Instructions
Take a sufficient sample of Gutenberg's couple of digital books of your choice.
Create (random?!) samples of 200 partitions of the book. 
Make sure each partition or record has 100 words. 
Generalize the program so that you can replicate that for multiple books. 
Maintain the label for each of the text segments or records or document, label them as a, b and c etc. as per the book they belong to. 
Use Regular Expressions and Pandas to manipulate the data and serialize them.

## Installation

Use the package manager [pip]


```bash
pip install Pandas
```



##  Solution (myTextDataPartitioning_Done.ipynb)
### This contains a series of steps to create a model to manipulate the data ("Gutenberg's couple of digital books") and serialize them:
       1. Select two books in the displayed list.
       2. Return all data of books in a string variable.
       3. Find all required samples in these books by using sampleRegex and return the result in list.
       4. Drop "NaN" and 'Unnamed' from this list.
       5. Divide List into 200 partitions, each partition contains 100 random samples.
			- Use randint() function that takes random number in variable from particular range.
			- Cancel repeating same partition.
       6. Create object dataframe from pandas library to put partitions.
## Thank You
Ahmed Abdo Amin Abdo
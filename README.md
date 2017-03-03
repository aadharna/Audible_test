# Audible Test

##### Reads in two files. 
First file:
(each row in a unique person)

| Cust_ID | Book1  | Book2 | Book3 | . | . |   |   | Book10  |
|---------|--------|-------|-------|---|---|---|---|---------|
| 1       | asdf   | .     | .     | . | . | . | . | kjladsf |
| 2       | .      | .     | .     | . | . | . | . | .       |
| .       | .      | .     | .     | . | . | . | . | .       |
| .       | .      | .     | .     | . | . | . | . | .       |
| n       | aze131 | .     | .     | . | . | . | . | klj181  |

##### Second file:
(allows for repetition of person buying books)

| Cust_ID | Bought Book |
|---------|-------------|
| 1       | saf23       |
| .       | .           |
| .       | .           |
| n       | .           |
| 3       | .           |
| 51      | .           |

##### The program then calculates:

### 1.       Proportion of customers who had purchased at least one recommendation
### 2.       Precision (number of purchased recommendations / number of given recommendations)
### 3.       Recall (number of purchased recommendations / number of purchases)
 
 
Each customer is given 10 recommendations each, the columns in that file are rank ordered, 
i.e., recommendation 1 is more strongly recommended than recommendation 10.  
calculate the above numbers for each customer if we showed them only the:
first rec, the first two, first three, etc.  

### The output should look something like this:
 
| Recs_Given | Metric1 | Metric2 | Metric3 |
|------------|---------|---------|---------|
| 1          |         |         |         |
| .          |         |         |         |
| .          |         |         |         |
| .          |         |         |         |
| 10         |         |         |         |
 

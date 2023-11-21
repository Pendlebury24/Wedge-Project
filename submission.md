
# Applied Data Analytics

## Wedge Project

<!-- Any general commentary you'd like to say about the project. --> 

I'm going for a B so there's no data cleaning. 
Task 2 and 3 are fully done. Task 1 I was able to get the data in GBQ but am struggling with specifing the data types. So there are two files. One that works and uploads the data but has some issues in GBQ and one that is a mess. I will keep trying to get it to work.


### Task 1

* Files for this task: 
<!--  Task 1 Baseline  --> 

Loads all data into GBQ data set. letting GBQ decide the column data type

`Task 1 baseline upload.ipynb`: 
Description of what this file does.

<!--  Task 1 upload  --> 

Loads the data into GBQ trying to specify the data types I could not get this to work before the deadline. 
`Task 1 upload.ipynb`: 

### Task 2

* Files for this task: 
<!--  Task 2  --> 

Pulls all data from 80 random owners in GBQ and saves it to an CSV file.

`Task 2.ipynb`: 
Description of what this file does.


	

### Task 3

* Files for this task: 
<!--  Task 3  --> 

Runs multiple queries in GBQ and puts the data into a local database.

`Task 3.ipynb`: 
Description of what this file does.




## Query Comparison Results

Fill in the following table with the results from the 
queries contained in `gbq_assessment_query.sql`. You only
need to fill in relative difference on the rows where it applies. 
When calculating relative difference, use the formula 
` (your_results - john_results)/john_results)`. 



|  Query  |  Your Results  |  John's Results | Difference | Rel. Diff | 
|---|---|---|---|---|
| Total Rows  | 85760139  |  85760139 |  0 | 0  |
| January 2012 Rows  | 1070907  | 1070907  | 0  |  0 |
| October 2012 Rows  | 1042287  |  1042287 |  0 | 0  |
| Month with Fewest  | Feb  | Feb  | No  | NA  |
| Num Rows in Month with Fewest  | 6556770  |  6556770 | 0  | 0  |
| Month with Most  |  May | May  | No  | NA  |
| Num Rows in Month with Most  | 7578372  | 7578372  |  0 | 0  |
| Null_TS  | 7123792 |  7123792 |  0 |  0 |
| Null_DT  |  0 | 0  |  0 |  0 |
| Null_Local  |  234843 | 234843  | 0  | 0  |
| Null_CN  |  0 |  0 |  0 | 0  |
| Num 5 on High Volume Cards  | 14987  |  14987 | No  | NA  |
|  Num Rows for Number 5 | 460630  | 460630  | 0  |  0 |
| Num Rows for 18736  |  12153 | 12153  | 0  | 0  |
| Product with Most Rows  | bananas organic  | bananas organic  | No  | NA  |
| Num Rows for that Product  |  908639 | 908639  | 0  | 0  |
| Product with Fourth-Most Rows  | avocado hass organic  |  avocado hass organic | No  | NA  |
| Num Rows for that Product  |  456771 |  456771 | 0  |  0 |
| Num Single Record Products  |  2769 |  2769 | 0  |  0 |
| Year with Highest Portion of Owner Rows  |  2014 | 2014  | No  | NA |
| Fraction of Rows from Owners in that Year  | .7591  | .7591  | 0  |  0 |
| Year with Lowest Portion of Owner Rows  |  2011 |  2011 | No  | NA |
| Fraction of Rows from Owners in that Year  |  .7372 | .7372  |  0 | 0  |

## Reflections

<!-- I'd love to get 100-200 words on your experience doing the Wedge Project -->
I'm going to be honest and say my biggest take away from the wedge project is that I've probably been relying on chatgpt to much for python. It has been super helpfull and it's helped me a lot but I've leaned to heavily into it. 

Besides the struggling with some of it overall I thought it was a great project. It was nice to work through so many areas all in one assignment instead of partially over many. Even with chatgpt it was still a difficult in areas. 
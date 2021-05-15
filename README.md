# Green Stock Analysis
## Overview
Steve is looking to analyze a set of green energy stocks.  He has a spreadsheet that contains information from 12 different company stocks that ranges from the years 2017 and 2018.  After doing some calculations and formatting with the data, he is planning on providing his parents some recommendations as to which stocks to purchase.
## Task Descriptions
This particular task required the programmer to complete code that would decrease the run time of the initial program.  When I first went through the module, the code was effective in providing the correct information, but was not as speedy as it needed to be.  This may not cause problems now, but could be an issue with larger amounts of data.  In order to speed up the process I used 4 different arrays.  The first array was declared as a string and named tickers.  This was used in the original module.  The second array was declared as a long as was labeled as tickerVolumes.  This array was used to help add up the total amount of trading from a company (ticker) in a given year.  The third and fourth arrays were set up to keep track of the staring and ending ticker prices.  This was used to help determine if the stock price increased or decreased and by what percent.  I also used a counter to help keep track of which part of the array was being indexed.
### Array Purpose
The purpose of the arrays in this instance was to save data to variables while only counting through every row of data one time.  In the module, the program was set up to read through every row of data for each of the different ticker symbols.  By using arrays, I was able to only run through the entire set of data once, thereby significantly decreasing the run time.   
##Results
My program run time went from somewhere around 0.8 - 0.9 seconds to .08 - .09 seconds.  This would be expected after the refactoring that was completed.
Images for Each Part 

## Summary
The main advantage for refactoring this particular code is that we can create language that speeds up the process.  Steve may want to use this code again with a larger data set and a faster run speed will be very beneficial.  The main struggle I had with refactoring code is determining the logic that the original user was using.  As I went through each line of code I had to pay close attention to what the code had already done.  My thought process may not be the same as the original coder and refactoring code based on his or her thought process took some getting used to.

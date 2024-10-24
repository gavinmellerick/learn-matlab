
# Medical Technology Maths for Clinical Technology MATLAB

**Practical 3**  

**10th October 2024**  

1. Electricity data is stored in an excel file named usage.xlsx. There are three columns of data (residential, commercial and industrial usage). Import this excel file (usage.xlsx) into matlab. (It is on moodle). Use the `importdata("usage.xlsx")` function. Remember to save the excel file into your MATLAB folder and enclose the filename in quotes. What kind of data structure is the data stored in? Look at the workspace
2. One of the elements in the usage variable has a value of NaN (Not a Number). Replace this value with the value 2.74 in matlab. Use row and column indexing to refer to the specific element you want to change e.g. ***usage (4,2)*** refers to the fourth row and the second column of the usage data.  To change or update a variable, the variable must be on the left hand side of the equals sign. Verify that you have changed the data.  
3. The residential data is stored in the first column. Create a variable ***res*** that contains the first column of ***usage***. Use the : to indicate that you want all the rows e.g. ***usage(:,2***) refers to all rows, 2nd  column.  
4. The commercial data is stored in the second column. Create a variable ***comm*** that contains the second column of ***usage***.
5. The industrial data is stored in the third column. Create a variable ***ind*** that contains the third column of ***usage***.
6. Find the total residential usage; add all the elements in the ***res*** array and store the answer in a new variable. You can use the function ***sum()*** to find the total of an array. Verify that the answer is correct. Put a comment in your matlab file to describe how you verified it.  
7. Find the total commercial usage; add all the elements in the ***comm*** array and store the answer in a single variable. You can use the function ***sum()*** to find the total of an array. Verify that the answer is correct. Put a comment in your matlab file to describe how you verified it.  
8. Find the total industrial usage; add all the elements in the ***ind*** array and store the answer in a single variable. You can use the function ***sum()*** to find the total of an array. Verify that the answer is correct. Put a comment in your matlab file to describe how you verified it.  
9. Find which has the largest total usage (residential, industrial or commercial) and print a message to say which is the largest. You can use an if statement.
10. Find the average of residential usage. Use the function ***mean()***.
11. Find the average of commercial usage. Use the function ***mean()***.
12. Find the average of industrial usage. Use the function ***mean()***.
13. If the rows 1 to 23 represent days in a billing period, find the total usage for each day in the period. You can create a new array to store these values e.g. dailyUsage = []. Use a loop for this problem. Start by looking at the original excel. Ask yourself:
    - how many times do you want your loop to execute?
    - How many elements will be in dailyUsage[]??  
    - How will you verify that your result is correct? Find the expected answer before you start coding.  

Put a comment in your matlab file describing how you verified your results were correct.

## Challenge Task

Without using the function max(), determine which is the largest element of the ***res*** array. Hint: use a variable to store the biggest element and use a loop to compare each element with the biggest element. Before you start, make the first element in the array the biggest and then compare each element in the array to this element. If you find an element that is bigger than ‘biggest’, make this element the biggest and continue.  

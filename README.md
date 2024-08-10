# Python-Patterns-
## Hi! Here I will upload a regular Python pattern program.

### <li> Steps to Print a Pattern in Python
<ol>
<li> <h4>Decide the Number of Rows:</h4> 
Before you begin, could you determine the pattern size, usually based on the number of rows?</br>
You can accept the number of rows from the user using the input() function.
        
<li><h4>Outer Loop for Rows:</h4> 
The outer loop controls the number of rows in the pattern.</br>
If there are n rows, the loop will run n times.

<li> <h4>Inner Loop for Columns:</h4>
The inner loop is responsible for each row's number of elements (stars, numbers, etc.).</br>
The number of columns typically depends on the current row number, which the outer loop controls.

<li> <h4>Print the Pattern Symbol:</h4>
Inside the inner loop, use the print() function to display the symbol (like *, #, or a number).</br>
Use print() with the end=" " parameter to keep printing on the same line.
Move to the Next Line After Each Row:

</ol>

After completing a row, use print() without arguments to move the cursor to the next line.
This ensures the next set of symbols is printed on a new line.
# ----------------------------------------------------------------------------

<h3><b>Square Pattern</b></h3>

        *****                            row = 5                         - We want 5 rows of stars
        *****                            for i in range(1,row+1):        - This loop will run 5 times (once for each row) 
        *****                               for j in range(1,row+1):     - This loop will also run 5 times for each row (to print 5 stars) 
        *****                                   print('*',end=' ')       - printing * to print one single line we are using the end keyword
        *****                               print()                      - Move to the next line after printing 5 stars    
        
        
        
        
        




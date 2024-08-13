# Python-Patterns-
## Hi! I will upload a regular Python pattern program here.

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

### All code should be created to be dynamic, taking input from the user and replacing it with the row.
        n = int(input("Enter the number of rows: "))
        row = n

<h3><b>Square Pattern</b></h3>

        *****                          row = 5                         - We want 5 rows of stars
        *****                          for i in range(1,row+1):        - This loop will run 5 times (once for each row) 
        *****                             for j in range(1,row+1):     - This loop will also run 5 times for each row (to print 5 stars) 
        *****                                 print('*',end=' ')       - printing * to print one single line we are using the end keyword
        *****                              print()                      - Move to the next line after printing 5 stars    
        

<h3><b>Right-Angled Triangle</b></h3>

        *                              row = 5;                        - we want 5 rows of stars
        **                             for i in range(1,row+1)         - this loop will run 5 times
        ***                                 print('* ' * i );          - Printing * for a single line with the respective 'i', i.e. when i=1, print one *, when i=2, print two *s, when i=3, print three *s, and so on."
        ****
        *****
        
<h3><b>Inverted Right-Angled Triangle</b></h3>        

        *****                         row = 5                          - we want 5 rows of stars
        ****                          for i in range(row):             - this loop will run 5 times
        ***                                for j in range(i,row):      - this will go in reverse like i-1 
        **                                      print('*', end=' ')    - Printing * for a single line with the respective i.
        *                                  print()                     - for next line


<h3><b>Pyramid</b></h3> 

            *                        row = 4                             - Number of rows
           ***                       for i in range(1, n + 1):  
          *****                           print(' ' * (n - i), end='')   - Print leading spaces to center the pyramid
         *******                          print('*' * (2 * i - 1))       - Print asterisks for the current row
        *********  
           
          
          
     







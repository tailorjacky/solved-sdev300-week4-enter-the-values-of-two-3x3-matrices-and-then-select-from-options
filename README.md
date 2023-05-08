Download Link: https://assignmentchef.com/product/solved-sdev300-week4-enter-the-values-of-two-3x3-matrices-and-then-select-from-options
<br>
The first exercise allows a user to enter the values of two, 3×3 matrices and then select from options including, addition, subtraction, matrix multiplication, and element by element multiplication.  You should use numpy.matmul() for matrix multiplication (e.g. np.matmul(a, b) ). The program should computer the appropriate results and return the results, the transpose of the results, the mean of the rows for the results, and the mean of the columns for the results.

When entering data you should check that each value is numeric for the matrices. The user interface should continue to run until the user indicates they are ready to exit.

A user interface might look similar to this:

***************** Welcome to the Python Matrix Application***********

Do you want to play the Matrix Game?

Enter Y for Yes or N for No:

Y

Enter your first 3×3 matrix:

1 2 4

4 2 1

3 8 9

Your first 3×3 matrix is:

1 2 4

4 2 1

3 8 9

Enter your second 3×3 matrix:

3 2 1

7 2 5

5 2 1

Your first 3×3 matrix is:

3 2 1

7 2 5

5 2 1

Select a Matrix Operation from the list below:

<ol>

 <li>Addition</li>

 <li>Subtraction</li>

 <li>Matrix Multiplication</li>

 <li>Element by element multiplication a</li>

</ol>

You selected Addition. The results are:

4 4 5

11 4 6

8 10 10 The Transpose is:

4 11 8

<ul>

 <li>4 10</li>

 <li>6 10</li>

</ul>

The row and column mean values of the results are:

Row: 4.33, 7, 9.33 Column: 7.66, 6, 7 Do you want to play the Matrix Game?

Enter Y for Yes or N for No:

N

*************** Thanks for playing the Matrix Game **********




If an inappropriate entry is detected, the program should prompt for a correct value and continue to do so until a correct value is entered.

Hints:

<ol>

 <li>Use numpy and associated functionality</li>

 <li>Create and use functions as often as possible</li>

 <li>Use comments to document your code</li>

 <li>Both integers and float values are acceptable</li>

</ol>




For the second exercise use Python Panda, Regular Expressions, .map() and other functions as appropriate to format existing address records and eliminate records with missing critical fields. Critical fields include FirstName, Lastname, Zipcode+4, and Phone number for customers.  For this exercise, create an array to hold data with these 4 fields containing at least 25 records.

The Zipcode field should contain either traditional 5-digit Zipcode (e.g. 21801) or Zip+4 format (e.g 21801-1101). The phone numbers should contain 10-digit (e.g. 5555555555) or formatted 10-digit (e.g. 555-555-5555). Some records might be corrupt so the data needs to be munged. At this point, we assume only U.S data will be present therefor country code is not needed.

A few records, data might look like this:

Jim, Robertson, 21801,555-555-5555

John, Adams, 223211143, 4444444444

Helen, Cooper, edskd-2134,323232

,Franklin,234511, 323-333-2211

…

You python code should label each column, properly format the Zip code to be either 11111 or 111111111 formats, properly format the phone numbers to always be 111-111-1111 format, and replace incorrect values with a blank string.

For example, after processing the above file, the returned results would be:







Firstname   Lastname      Zipcode           Phone

Jim  Robertson        21801    555-555-5555

John      Adams   22321-1143    444-444-4444

Helen     Cooper

Franklin                 323-333-2211




Notice invalid data was removed and formatting was applied as required. Commas can be left if desired. Default alignment with the column labels is acceptable.

Hints:

<ol>

 <li>Hardwire the 25 records. (i.e. the user doesn’t have to enter this)</li>

 <li>Review the code in the textbook examples to simplify this work</li>

 <li>Use comments to document your code</li>

</ol>

<strong> </strong>

3. Document your results for each application within the AWS Cloud9 classroom environment.  Provide screen captures and descriptions for each test cases you provide for each of your applications. Be sure to go through each possible user interface combination in your test cases
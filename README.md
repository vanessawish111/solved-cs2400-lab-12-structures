Download Link: https://assignmentchef.com/product/solved-cs2400-lab-12-structures
<br>
Work with structures, vector of structures, files, and formatting.

A company keeps its employee records in a file. Each line in the file includes a single employee record (id, first name, last name, &amp; salary). Write a C++ program that prints a report of employee data. You are asked to process the data in the file by storing the records in a <em>vector</em> of structures. Your program must print the following report.

<ul>

 <li>All employee records.</li>

 <li>Find and print the total payroll.</li>

</ul>

Create a directory called <strong>Lab6</strong> inside your <strong>2400/Labs</strong> directory. Download the data file and store it in Lab6 directory.

<strong>Hints: </strong>

<ul>

 <li>Write a function to load the vector of structures.</li>

 <li>Write a function to print the report. Consider using <em>setw</em>.</li>

</ul>

o Combine the first and last name into a single string. This will make it easier to use setw.

<ul>

 <li>Write a function to calculate and return the total payroll.</li>

</ul>

<strong>Sample input: </strong>

1000 George Washington 10000

2000 John Adams 15000

1212 Thomas Jefferson 34000

1313 Abraham Lincoln 45000

1515 Jimmy Carter 78000

1717 George Bush 80000

Sample output:

Sorted by name

ID      Name                Salary

————————————

1000    George Washington   $10000.00

2000    John Adams          $15000.00

1212    Thomas Jefferson    $34000.00

1313    Abraham Lincoln     $45000.00

1515    Jimmy Carter        $78000.00

1717    George Bush         $80000.00

Total Payroll: $262000.00



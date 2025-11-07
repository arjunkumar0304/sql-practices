# sql-practices

# (04.11.25)
# TABLE - 1 (PRACTICES_EMP)

<img width="953" height="962" alt="Screenshot 2025-11-04 142823" src="https://github.com/user-attachments/assets/49c9abf8-22b4-4beb-8a06-c47a7d48fb13" />


1. Write a query to display all columns from the table.

<img width="953" height="962" alt="Screenshot 2025-11-04 142823" src="https://github.com/user-attachments/assets/05462db5-5426-4200-abd1-6a36141ee15f" />


2. Display the names of employees who work in the IT department.
<img width="536" height="317" alt="Screenshot 2025-11-04 143011" src="https://github.com/user-attachments/assets/c2cbde85-52ee-4b64-b59e-57ad65ae9705" />



3. Display the employees with a salary greater than 45,000.
<img width="426" height="249" alt="Screenshot 2025-11-04 143031" src="https://github.com/user-attachments/assets/93dd6ed6-dc41-4a1d-9e01-0281f5a15e33" />


4. Find the total number of employees in each department.
<img width="518" height="320" alt="Screenshot 2025-11-04 143245" src="https://github.com/user-attachments/assets/1f2bcf9e-9f8e-47b0-9a46-88d427388d1d" />


5. Display employees ordered by salary in descending order.
<img width="511" height="367" alt="Screenshot 2025-11-04 143308" src="https://github.com/user-attachments/assets/a803c53e-2cf7-429c-8340-0331b2418d95" />



6. Display the average salary of all employees.
<img width="396" height="278" alt="Screenshot 2025-11-04 143324" src="https://github.com/user-attachments/assets/8b576617-2b06-4d30-aa6d-189dd84d266b" />



7. Find the youngest employee in the company.

<img width="608" height="296" alt="Screenshot 2025-11-04 143337" src="https://github.com/user-attachments/assets/ec262cf3-9ea7-4630-916b-3135eeaf0fe8" />

8. Rename the column “salary” as “employee_salary” in output.

<img width="431" height="445" alt="Screenshot 2025-11-04 143354" src="https://github.com/user-attachments/assets/c5ef11b1-fa77-468c-9a0d-9bbeb9a6a4e7" />


# TABLE 2 - (PRACTICES_ORDER) (where, groupby, having) (aggregate function)

<img width="1085" height="623" alt="Screenshot 2025-11-04 144334" src="https://github.com/user-attachments/assets/5ca14dd7-8cdf-4cae-acde-9c76946c32f7" />


1. Find the total order amount per customer.

<img width="553" height="339" alt="Screenshot 2025-11-04 144726" src="https://github.com/user-attachments/assets/52fb0165-f7f4-40c8-857a-c041b1b1ab87" />


2.Retrieve customers who have made more than one order.

<img width="697" height="453" alt="Screenshot 2025-11-04 144739" src="https://github.com/user-attachments/assets/5ae3eb8c-5b26-4d9c-9443-dcdbd7f24844" />


3.Get the highest and lowest order amount.

<img width="445" height="256" alt="Screenshot 2025-11-04 144843" src="https://github.com/user-attachments/assets/5c58047a-fcb1-4dc2-9915-0fbb602c45da" />


4.Display all orders placed in May 2024.

<img width="677" height="405" alt="Screenshot 2025-11-04 144854" src="https://github.com/user-attachments/assets/218f5c13-41ff-4094-8416-e226aea983c1" />


5.Calculate the average order amount for each customer.

<img width="443" height="418" alt="Screenshot 2025-11-04 144905" src="https://github.com/user-attachments/assets/2a0a6493-ebaf-4b5c-9ca9-ea29fd474a6a" />


6.Find the top 1 customer based on total order value.

<img width="464" height="354" alt="Screenshot 2025-11-04 145042" src="https://github.com/user-attachments/assets/67d1bf6a-5794-49d8-94f6-f141665bc532" />


7.Find orders where amount > average order amount.

<img width="603" height="298" alt="Screenshot 2025-11-04 145054" src="https://github.com/user-attachments/assets/f2ce5a7f-c1b6-46ce-b3e8-166412b45b2b" />



# table 4(departments) & table 5(employees)

<img width="1167" height="973" alt="Screenshot 2025-11-04 175157" src="https://github.com/user-attachments/assets/f1aa53dc-a8d3-4e16-a310-c88b6ced595f" />


1.Display employee names along with their department names.

<img width="477" height="363" alt="Screenshot 2025-11-04 175212" src="https://github.com/user-attachments/assets/4ee8b44e-3e97-47fb-8dbb-a7b10358829e" />


2.Find the average salary per department.

<img width="659" height="346" alt="Screenshot 2025-11-04 175226" src="https://github.com/user-attachments/assets/06f20d1f-7aaa-4cf8-8382-86bb652fa527" />



3.Display departments where average salary > 45,000.

<img width="673" height="440" alt="Screenshot 2025-11-04 175249" src="https://github.com/user-attachments/assets/29815896-a14b-4529-a04c-1124720038a2" />



4.Use a window function to rank employees based on salary.

<img width="757" height="473" alt="Screenshot 2025-11-04 175300" src="https://github.com/user-attachments/assets/0ca7021a-1019-48bf-869c-967e5f7d90d5" />



5.Find the second highest salary using RANK().

<img width="636" height="458" alt="Screenshot 2025-11-04 175314" src="https://github.com/user-attachments/assets/ba1c8860-c242-4695-9f45-13b3528c1267" />



6.Display employees who earn more than the department average.

<img width="819" height="387" alt="Screenshot 2025-11-04 175345" src="https://github.com/user-attachments/assets/0679ba5c-64a1-42ad-becb-4a23a78008b4" />



7.Create a view to show employee name, dept_name, and salary.

<img width="602" height="461" alt="Screenshot 2025-11-04 175412" src="https://github.com/user-attachments/assets/0958cb6d-7db2-4cdd-992f-fc6949cdf01a" />


# (05.11.25)
sql practices

Show departments where average salary is greater than ₹45,000.

<img width="496" height="410" alt="Screenshot 2025-11-05 160544" src="https://github.com/user-attachments/assets/7973b4d8-6758-4432-b81f-b050f8dccd52" />

Find departments that have more than 1 employee.

<img width="480" height="583" alt="Screenshot 2025-11-05 162419" src="https://github.com/user-attachments/assets/7b80357b-0229-42d8-be56-2db95482eab3" />


Show departments where total salary is above ₹1,00,000.

<img width="506" height="486" alt="Screenshot 2025-11-05 162920" src="https://github.com/user-attachments/assets/5fb19517-b88c-4f3c-8436-4a5cdc8fe8a0" />


Display department(s) where the maximum salary is greater than ₹50,000.

<img width="504" height="437" alt="Screenshot 2025-11-05 163038" src="https://github.com/user-attachments/assets/ce0b393a-5f64-4e5c-a193-9dec5f47c3bf" />



Find departments where the minimum salary is less than ₹45,000.

<img width="502" height="388" alt="Screenshot 2025-11-05 163129" src="https://github.com/user-attachments/assets/9b2630c4-88b8-4fce-941b-4c53ab36f01e" />


Display departments in order of highest average salary.

<img width="483" height="396" alt="Screenshot 2025-11-05 163540" src="https://github.com/user-attachments/assets/600f035e-94d1-4347-9a56-0e56a29fc8f4" />


Display the department with the highest total salary.

<img width="634" height="510" alt="Screenshot 2025-11-05 165857" src="https://github.com/user-attachments/assets/407bf473-d2b7-4e1b-8632-1577ba2826ae" />



# py(lambda function)

Write a lambda function to add two numbers.

<img width="566" height="437" alt="Screenshot 2025-11-05 182714" src="https://github.com/user-attachments/assets/d04204c8-bbdb-4e28-8106-d065c300d274" />

Write a lambda to find the square of a number.

<img width="618" height="485" alt="Screenshot 2025-11-05 182746" src="https://github.com/user-attachments/assets/88c7e424-0afa-44ee-ada4-1b9c7731880e" />



Write a lambda to check whether a number is even or odd.

<img width="572" height="281" alt="Screenshot 2025-11-05 182827" src="https://github.com/user-attachments/assets/2ad02e9f-5c2a-4dc2-a6ee-48c9a523fc1c" />

Write a lambda to get the maximum of two numbers

<img width="635" height="574" alt="Screenshot 2025-11-05 182929" src="https://github.com/user-attachments/assets/6c9ae7d9-cacc-474d-8f5b-59020bd8a465" />


Write a lambda that returns the length of a given string.

<img width="586" height="562" alt="image" src="https://github.com/user-attachments/assets/43335d5b-35ff-44aa-8897-8c26ac9d1856" />




Using map() and lambda, double each number in a list.

<img width="723" height="541" alt="Screenshot 2025-11-05 184348" src="https://github.com/user-attachments/assets/32c2228d-0c32-44e1-aeb4-630cff8147c5" />


Using map(), convert all strings to uppercase.

<img width="715" height="620" alt="Screenshot 2025-11-05 184610" src="https://github.com/user-attachments/assets/f058a003-c71e-480d-9b7b-951e5b75212f" />


Using map(), find the cube of each number in a list.

<img width="656" height="719" alt="Screenshot 2025-11-05 184743" src="https://github.com/user-attachments/assets/486eb032-08c5-400a-acbd-31081cb33782" />



Using filter(), get only even numbers from a list.


<img width="630" height="646" alt="Screenshot 2025-11-05 190225" src="https://github.com/user-attachments/assets/5f58ff3b-dabd-4c49-b04d-ce3c8601f48b" />


Using filter(), get numbers greater than 10.

<img width="704" height="685" alt="Screenshot 2025-11-05 190203" src="https://github.com/user-attachments/assets/ea21d6d6-09d9-46fd-a724-e382f41b6ddb" />



Using filter(), get all strings that start with “a”.



<img width="837" height="714" alt="Screenshot 2025-11-05 185701" src="https://github.com/user-attachments/assets/88d20d77-3545-41e0-8510-54340558db4c" />


# SQL PRACTICES (WINDOW FUNCTION)

06.11.25




Find total salary of each department (but show all employees).

<img width="711" height="397" alt="Screenshot 2025-11-06 145305" src="https://github.com/user-attachments/assets/ccc7079f-c428-4f0c-ae58-e99d48af550d" />


Find average salary of each department.


<img width="744" height="436" alt="Screenshot 2025-11-06 145328" src="https://github.com/user-attachments/assets/a5c15c0d-08f6-4ee9-a1f4-d6fdd8195905" />


Give each employee a rank based on salary within their department.


<img width="876" height="464" alt="Screenshot 2025-11-06 145353" src="https://github.com/user-attachments/assets/b0db1e73-a21f-40eb-82f7-b36dcd962de9" />


Assign a unique row number to each employee in each department.

<img width="850" height="397" alt="Screenshot 2025-11-06 145412" src="https://github.com/user-attachments/assets/17a0b7af-0a04-4463-b283-7d72df4fc62d" />



Find cumulative (running) total of salaries when ordered by emp_id.

<img width="742" height="457" alt="Screenshot 2025-11-06 145428" src="https://github.com/user-attachments/assets/04393673-e7f5-4db4-914b-9269dff9cdd5" />




Find the highest salary in each department.

<img width="672" height="441" alt="Screenshot 2025-11-06 145443" src="https://github.com/user-attachments/assets/63e8987e-ab5e-401c-ac00-966dbd8d3a39" />



Compare each employee’s salary with the previous employee’s salary (based on emp_id).

<img width="784" height="450" alt="Screenshot 2025-11-06 145505" src="https://github.com/user-attachments/assets/b5bca535-ce52-492d-9958-33b377fd213e" />

|

Show each employee’s salary and the next employee’s salary.

<img width="674" height="348" alt="Screenshot 2025-11-06 145520" src="https://github.com/user-attachments/assets/4d948636-fb41-416d-93bd-ebeb829f6e14" />



Divide all employees into 3 groups based on salary.

<img width="584" height="408" alt="Screenshot 2025-11-06 145600" src="https://github.com/user-attachments/assets/fff0571c-cb40-45f3-b511-98472158ecad" />


# python practice

Create a list of 5 numbers and print their sum.
<img width="523" height="412" alt="Screenshot 2025-11-06 181155" src="https://github.com/user-attachments/assets/e049c55b-052f-4366-a9f1-6170f5e5b562" />


Find the maximum and minimum values from a list.

<img width="513" height="643" alt="Screenshot 2025-11-06 181349" src="https://github.com/user-attachments/assets/c8fd97f7-30b5-40b0-a146-e988e33db6b7" />

Reverse a list without using reverse() function.

<img width="559" height="497" alt="Screenshot 2025-11-06 181638" src="https://github.com/user-attachments/assets/d9b9a16c-34dd-4d38-9c76-26f3e8966dee" />


Count how many times an element appears in a list.
<img width="589" height="566" alt="Screenshot 2025-11-06 181712" src="https://github.com/user-attachments/assets/53c4c957-f24a-470e-adb0-1f6b5f55be5c" />


Remove duplicates from a list.

<img width="558" height="608" alt="Screenshot 2025-11-06 182039" src="https://github.com/user-attachments/assets/fd475e0d-ff32-4b55-a6bb-c5f55c6f9819" />



 Print only the even numbers from a list.

<img width="588" height="793" alt="Screenshot 2025-11-06 182052" src="https://github.com/user-attachments/assets/e5b44b4b-94b6-4ad7-a8eb-e3127b331ccb" />




count the number of vowels in a given string

<img width="417" height="586" alt="image" src="https://github.com/user-attachments/assets/cf4c9080-f4d2-4faa-a05f-c552f5ec3340" />


palindrome

<img width="516" height="541" alt="image" src="https://github.com/user-attachments/assets/6a29bf4d-adbf-4dd2-8025-8bfe546822cc" />


palindrome without slicing method

<img width="402" height="582" alt="image" src="https://github.com/user-attachments/assets/69ab91f2-d27c-4824-9159-5a4344954b57" />


*************



Find employees who earn more than the average salary of all employees.
<img width="887" height="411" alt="Screenshot 2025-11-07 185509" src="https://github.com/user-attachments/assets/38eb6393-c1f4-4311-8cab-d675a6325aaf" />




Find employees whose salary is greater than the minimum salary in the IT department.
<img width="1060" height="488" alt="Screenshot 2025-11-07 185529" src="https://github.com/user-attachments/assets/bc152d52-0b4f-4e24-b247-f58dfe8a74b3" />



Find the second highest salary in the company.
<img width="1023" height="417" alt="Screenshot 2025-11-07 185544" src="https://github.com/user-attachments/assets/c385fe8a-4436-4e4f-8363-c665c390f7fb" />


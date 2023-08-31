## 28-Aug-23 CW
1) Write the algorithm to find the average of 'n' numbers.
	- Solution:
		1) begin
		2) get user input for the value of n
		3) create a variable: sum = 0
		4) for n numbers
			1) repeat
			2) get number
			3) add the number to sum
		6) divide the sum by n
		7) display the result
		8) end

2) Write a sequential algorithm to add 2 numbers.
	- Solution:
		1) begin
		2) get the first number
		3) get the second number
		4) calculate the sum of both the numbers
		5) display the sum
		6) end

3) Write an algorithm to calculate the area of a circle.
	- Solution:
		1) begin
		2) get the radius of the number
		3) calculate the area using 3.14 * radius * radius and store in area
		4) display area
		5) end

4) Write an algorithm to find the average marks of 3 subjects for a student. Also check if the student passed or failed. To pass the average marks shouldn't be less than 65.
	- Solution:
		1) begin
		2) get the marks for the first subject
		3) get the marks for the second subject
		4) get the marks for the third subject
		5) add the marks and store it in sum
		6) divide sum by 3 and store it in average
		7) display average
		8) if the value of average is lesser than 65
			1) display "failed"
		9) otherwise
			1) display "passed"
		10) end

## 28-Aug-23 HW
1) Write an algorithm to find the factorial of a number.
	- Solution:
		1) start
		2) get user input for the number
		3) create a variable: factorial = 1
		4) while number is greater than 0
			1) repeat
			2) multiply number to factorial
			3) subtract 1 from number
		5) display factorial
		6) end

## 30-Aug-23
1) Write an algorithm to find the odd numbers within a range.
	- Solution:
		1) start
		2) get user input for the start of the range and store in u
		3) get user input for the end of the range and store in v
		4) while u is lesser than or equal to v
			1) repeat
			2) if the remainder on dividing u by 2 is 1
				1) display u
			3) increase the value of u by 1
		5) end

2) Write an algorithm to display the values of y = x$^2$ from x = 5 to x = 12.
	- Solution:
		1) start
		2) create a variable x = 5
		3) while x is lesser than or equal to 12
			1) repeat
			2) display x * x
		4) end

## 31-Aug-23
1) Given the unit price of a product and quantity of the product sold, draw a flowchart to calculate and print the total sale.
	- Solution:
		- Algorithm:
			1) start
			2) get user input for unit_price
			3) get user input for quantity
			4) calculate total_sale = unit_price * quantity
			5) display total_sale
			6) end
		- Flowchart:
			![[Pasted image 20230831082608.png]]

2) Draw a flowchart to calculate the average of 3 numbers.
	- Solution:
		![[Pasted image 20230831082840.png]]

3) Assume you are calculating pay at an hourly rate, and overtime pay (over 40 hours) at 1.5 times the hourly rate.
	- Solution:
		- Algorithm:
			1) start
			2) get user input for hours
			3) get user input for rate
			4) if hours > 40
				1) calculate pay = rate * 40 + rate * 1.5 * (hours - 40)
			5) otherwise
				1) calculate pay = rate * hours
			6) display pay
			7) end
		- Flowchart:
			![[Pasted image 20230831093312.png]]

4) Given the salary, pay type and hourly rate and hours worked. If the pay type is "HOURLY" then calculate hourly pay otherwise give salary. If the pay type is hourly and the hours worked is greater than 40, pay 1.5 times the normal rate for the overtime.
	- Solution:
		- Algorithm:
			1) start
			2) get user input for salary
			3) get user input for pay_type
			4) get user input for rate
			5) get user input for hours
			6) if pay_type = "HOURLY"
				1) then if hours <= 40
					1) calculate pay = rate * hours
				2) otherwise
					1) calculate pay = rate * (40 + 1.5 * (hours - 40))
				3) display pay
			7) otherwise
				1) display salary
			8) end
		- Flowchart:
			![[Pasted image 20230831100825.png]]
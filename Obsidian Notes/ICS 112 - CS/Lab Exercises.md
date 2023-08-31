## 28-Aug-23
#### Sequential

1) Algorithm to subtract two numbers.
	- Solution:
		1) start
		2) get the first number
		3) get the second number
		4) subtract the second number from the first number and store it in result
		5) display result
		6) end
	- ![[Pasted image 20230828142108.png]]

2) Algorithm to find the roots of the quadratic equation ax$^2$ + bx + c = 0.
	- Solution:
		1) start
		2) get the value of a
		3) get the value of b
		4) get the value of c
		5) calculate the value of the discriminant using: (b * b) - (4 * a * c) and store in d
		6) if d is lesser than 0
			1) display "imaginary roots"
		7) otherwise
			1) calculate the square root of the discriminant and store in sqrt
			2) calculate the first root using: (-b + sqrt) / (2a) and store in root1
			3) calculate the first root using: (-b - sqrt) / (2s) and store in root2
			4) display root1
			5) display root2
		8) end
	- ![[Pasted image 20230828143306.png]]

3) Algorithm to find the volume and surface area of a sphere.
	- Solution:
		1) start
		2) get the value of the radius
		3) calculate the volume using: (4/3) * 3.14 * radius * radius * radius and store in volume
		4) display volume
		5) calculate the surface area using: 4 * 3.14 * radius * radius and store in surface_area
		6) display surface_area
		7) end
	- ![[Pasted image 20230828144108.png]]

4) Algorithm to convert distance in kilometers to meters.
	- Solution:
		1) start
		2) get the distance in kilometers
		3) multiply distance by 1000
		4) display distance
		5) end
	- ![[Pasted image 20230828144417.png]]

5) Algorithm to calculate simple interest.
	- Solution:
		1) start
		2) get the principle amount and store in principal
		3) get the rate of interest and store in rate
		4) get the duration and store in years
		5) calculate the interest using: principal * interest * years and store in interest
		6) display interest
		7) end
	- ![[Pasted image 20230828144332.png]]

6) Algorithm to find displacement, given initial velocity, acceleration and time.
	- Solution:
		1) start
		2) get the initial velocity and store in u
		3) get the acceleration and store in a
		4) get the time and store in t
		5) calculate the displacement using: u * t + (1/2) * a * t * t and store in S
		6) display S
		7) end
	- ![[Pasted image 20230828144630.png]]

7) Algorithm to convert measurement given in feet to centimeters.
	- Solution:
		1) start
		2) get the measurement and store in length
		3) multiply length 30.48
		4) display length
		5) end
	- ![[Pasted image 20230828144754.png]]

#### Selective

1) Algorithm to find the largest among 3 numbers.
	- Solution:
		1) start
		2) get the first number and store in a
		3) get the second number and store in b
		4) if a is greater than b
			1) display b
		5) otherwise
			1) display a
		6) end

2) Algorithm to find the largest among 3 numbers.
	- Solution:
		1) start
		2) get the first number and store in a
		3) get the second number and store in b
		4) get the third number and store in c
		5) if a is greater than b and c
			1) display a
		6) otherwise if b is greater than c
			1) display b
		7) otherwise
			1) display c
		8) end

3) Algorithm to find if the number is even or odd.
	- Solution:
		1) start
		2) get the number and store in num
		3) calculate the remainder on dividing by 2 using: num % 2 and store in remainder
		4) if the remainder is equal to 1
			1) display "odd"
		5) otherwise
			1) display "even"
		6) end

4) Write an algorithm give the scenario. In a company worker efficiency is determined on the bases of the time taken by the worker to complete a particular job. If the time taken by the worker is between 2 - 3 hours, then the worker is highly efficient. If the time required by the worker is between 3 - 4 hours, then the worker is ordered to improve speed. If the time taken is between 4 -5 hours, the worker is given training to improve. If the time is greater than 5 hours the worker is asked to leave.
	- Solution:
		1) start
		2) get the time taken by the worker and store it in time
		3) if time is lesser than 2
			1) display "faster than 2 hours"
		4) otherwise if time is greater than or equal to 2 and if the time is lesser than 3
			1) display "highly efficient"
		5) otherwise if time is greater than or equal to 3 and if the time is lesser than 4
			1) display "ordered to work faster"
		6) otherwise if time is greater than or equal to 4 and if the time is lesser than or equal to 5
			1) display "give training to work faster"
		7) otherwise
			1) display "ask to leave the company"
![[Lab Exercises 2023-08-28 21.35.46.excalidraw]]

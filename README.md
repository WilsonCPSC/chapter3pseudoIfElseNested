# chapter3pseudoIfElseNested

Chapter 3: Pseudocode, if/else, & Nested

1. Each square on a chess board can be described by a letter and number.

 
The following pseudocode describes an algorithm that determines whether a square with a given letter and number is dark (black) or light(white).

If the letter is an a, c, e, or g
	If the number is odd
		Color = “black”
	Else
		Color = “white”
Else
	If the number is even
		Color = “black”
	Else
		Color = “white”

Use the pseudocode above to code a program that takes in an input from the user, and tells the user whether the square is black or white.

Example Results:
Please enter your square (letter followed by number): d3
That is a white square.


2. Explain the difference between an if/else if/else sequence and nested if statements. Give a short example for each.


3. The following algorithm yields the season (Spring, Summer, Fall, or Winter) for a given month and day.

If month is 1, 2, or 3, season = “Winter”
Else if month is 4, 5, or 6, season = “Spring”
Else if month if 7, 8, 9, season = “Summer”
Else if month is 10, 11, 12, season = “Fall”
If month is divisible by 3 and day >= 21
	If season is “Winter”, season = “Spring”
	Else if season is “Spring”, season = “Summer”
	Else if season is “Summer”, season = “Fall”
	Else season = “Winter”

Write a program that prompts the user for a month and day and then prints the season, as determined by this algorithm.

4. The original U.S. income tax of 1913 was quite simple. The tax was:
•	1 percent on the first $50,000.
•	2 percent on the amount over $50,000 up to $75,000.
•	3 percent on the amount over $75,000 up to $100,000.
•	4 percent on the amount over $100,000 up to $250,000.
•	5 percent on the amount over $250,000 up to $500,000.
•	6 percent on the amount over $500,000.

There was no separate schedule for single or married taxpayers. Write a program that computes the income tax according to this schedule.
 



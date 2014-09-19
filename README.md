Problem 1 – Exam Schedule
At SoftUni we have a new trainee Stamat, who is assigned to make schedules for the entrance exams. Since today is his first day at work he is a little bit nervous and he is not working very fast. Unfortunately, it seems that he will not have enough time to make the schedule for the next exam and there is no one else to do the job … except you of course. You will be given exam starting time in the standard 12-hour clock (hours, minutes and part of the day) and exam duration (hours and minutes). Your job is to write a program that calculates at what time the exam ends.
* Note that the standard 12-hours clock uses the following arrangements of the hours of the day: 12AM (midnight), 1AM, 2AM, 3AM, 4AM, 5AM, 6AM, 7AM, 8AM, 9AM, 10AM, 11AM, 12PM (noon), 1PM, 2PM, 3PM, 4PM, 5PM, 6PM, 7PM, 8PM, 9PM, 10PM, 11PM, 12AM, 1AM, … (learn more at http://en.wikipedia.org/wiki/12-hour_clock).
Input
The input data should be read from the console. The input data consists of exactly 5 lines:
•	The first three lines are holding the exam start time: hour, minutes and part of the day (AM or PM).
•	The last two lines are holding two integer number: the exam duration hours and minutes.
The input data will always be valid and in the format described. There is no need to check it explicitly.
Output
You have to print the time the exam ends in format HH:MM:PartOfDay.
Constraints
•	The starting hour will be an integer number in the range [1…12] inclusive.
•	The starting minutes will an integer number in the range [0…59] inclusive.
•	The part of the day will consist of exactly two capital letters: AM or PM.
•	The duration hours will be an integer number between [0…23] inclusive.
•	The duration minutes will be an integer number between [0…59] inclusive.
•	Allowed work time for your program: 0.1 seconds.
•	Allowed memory: 16 MB.
Examples
Input	Output						
9
30
AM
6
00	  03:30:PM
Input	Output		
2
0
PM
2
30	04:30:PM	
Input	Output
11
30
AM
2
0	   01:30:PM		
Input	Output
11
59
PM
0
3	  12:02:AM

Problem 2 – Odd / Even Elements
You are given N numbers. Calculate the sum, min and max of its odd elements and sum, min and max of its even elements. Consider that the first element is odd, the second is even, etc.
Input
The input data should be read from the console. It will consists of exactly one line.
•	At the first line N numbers will be given, separated one from another by a single space.
The input data will always be valid and in the format described. There is no need to check it explicitly.
Output
You have to print the output in a single line at the console in the following format:
•	OddSum=…, OddMin=…, OddMax=…, EvenSum=…, EvenMin=…, EvenMax=…
Print the numbers in the output without any unneeded trailing zeroes (i.e. print 1.5 instead of 1.50; 1 instead of 1.00). In case the sum, the minimal or the maximal element cannot be calculated (due to missing data), print "No".
Constraints
•	All numbers in the input will be in the range [-1 000 000 … 1 000 000], with no more than 10 digits (total, before and after the decimal point). The decimal separator in the non-integer numbers will be '.' and the numbers will have up to 2 digits after the decimal separator.
•	The count N of the numbers in the input is in the range [0 … 1000].
•	All numbers in the output should be formatted without unneded trailing zeroes.
•	Allowed work time for your program: 0.1 seconds.
•	Allowed memory: 16 MB.
Examples
Input              Output
2 3 5 4 2 1	       OddSum=9, OddMin=2, OddMax=5, EvenSum=8, EvenMin=1, EvenMax=4
3 -2 8 11 -3	     OddSum=8, OddMin=-3, OddMax=8, EvenSum=9, EvenMin=-2, EvenMax=11
1	                 OddSum=1, OddMin=1, OddMax=1, EvenSum=No, EvenMin=No, EvenMax=No
1.5 -2.5	         OddSum=1.5, OddMin=1.5, OddMax=1.5, EvenSum=-2.5, EvenMin=-2.5, EvenMax=-2.5
1.5 1.75 1.5 1.75	 OddSum=3, OddMin=1.5, OddMax=1.5, EvenSum=3.5, EvenMin=1.75, EvenMax=1.75


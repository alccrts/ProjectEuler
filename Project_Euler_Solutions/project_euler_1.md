**Project Euler Problem 1** 

Please note: I am solving these problems as I teach myself Python, therefore these earlier solutions will not be as advanced or efficient as my later solutions.
***
<em>If we list all the natural numbers below 10 that are multiples of 3 or 5, we get 3, 5, 6 and 9. The sum of these multiples is 23. Find the sum of all the multiples of 3 or 5 below 1000.</em>

The solution below uses a **while** loop to generate a program that finds the sum of all multiples of 3 and 5 below any number entered. 

````
num = 1
sum = 0

limit = int(input("Enter Limit:" ))
while num < limit: 
    if num % 3 == 0 or num % 5 == 0:
     sum += num 
     num += 1
    else:
     num+=1

print(sum)


**Output: 
Enter Limit:1000
233168**
````

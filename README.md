# Experiment-7
# Aim
To study while loops in python.
# Theory
1. A while loop is a control structure in Python that allows a set of statements to be executed repeatedly based on a condition. It is mainly used when the number of iterations is not known in advance and depends on a condition being true.
2. A while loop repeatedly executes a block of code as long as the given condition evaluates to True.
3. The condition is checked before every iteration.If the condition is True, the loop body executes.When the condition becomes False, the loop stops.
4. Flow of Execution- Start, Check the condition, If the condition is True, execute the loop body, Update the loop variable, Go back to step 2 and If the condition becomes False, exit the loop.
5. Key Characteristics- It is an entry-controlled loop (condition is checked first), It can execute zero or more times depending on the condition, Used when the number of repetitions is unknown, The loop must contain a change in condition (like increment/decrement), otherwise it may result in an infinite loop.
6. Types of while loops-
   Simple while loop- Repeats until the condition becomes false.
   Infinite while loop- Runs forever when the condition never becomes false.
   Nested while loop- A while loop inside another while loop.
7. Control Statements used with while loop
   break- Terminates the loop immediately.
   continue-Skips the current iteration and continues with the next.
   else- The else block executes when the loop ends normally (not terminated by break).
# Algorithm-7.1
1. Start.
2. Initialise a variable with 1.
3. To check condition i<=5  using while statement.
4. If condition true then it prints i.
5. To increase i by by 1 using i+=1.
6. To repeat steps 3-5 until the condition becomes false.
7. End.
# Algorithm-7.2
1. Start.
2. To take the input(n) from the user.
3. To initialise the variable with 1.
4. To check condition i<=n using while statement.
5. If condition true it prints i.
6. To increase i by by 1 using i+=1.
7. To repeat steps 3-5 until the condition becomes false.
8. End
# Algorithm-7.3
1. Start.
2. To take input from the user.
3. To initaialise fact by 1.
4. To check condition if n>0 using while statement, if true multiply fact=fact*n.
5. To decrease the value of n in each term by 1 using n=n-1.
6. To repeat steps from 4-6 until n becomes 0.
7. To display the result(factorial).
8. End.
# Algorithm-7.4- Method 1
1. Start
2. To input the number of terms(n).
3. To intialise a=0, b=1 and i=1.
4. To check condition i<=n using while statement, if true print a.
5. To calculate the nwxt term using the formula c=a+B.
6. To Update the values from a=b and b=c.
7. To increase the number of i by 1.
8. To repeat steps 4-8 until condition becomes false.
9. End.
# Algorithm-7.4 Method 2-Using Limit
1. Start
2. To input the limit till which number you want.
3. To initialise a=0 and b=1.
4. To check the condition a<=limit using while statement, if true prints a.
5. To calculate the next terms using a, b=b and a+b.
6. To repeat the steps from 4-6 until a becomes greater than the limit.
7. End.
# Algorithm-7.5
1. Start.
2. To take the input num from the user.
3. To initaialise rev=0.
4. To check the condition if num>0, if true to find the last digit using digit=num%10.
5. To update the reversed numberusing rev=rev*10+digit.
6. To remove the last digit from the oringinal number using num=num//10.
7. To repeat from steps 4-7 until num becomes 0.
8. To display the result(rev).
9. End.
# Algorithm 7.6- Part 1
1. Start
2. To take input(num) from the user.
3. To store it in another variable temp.
4. To intialise rev = 0.
5. To repeat while num > 0 using while statement.
6. To find last digit if digit = num % 10.
7. To add it to reverse it using rev = rev * 10 + digit.
8. To remove last digit using num = num // 10.
9. To compare temp and rev,if equal then prints Palindrome.
10. Else it prints Not Palindrome
11. End.
# Algorithm 7.6- Part 2
1. Start
2. To take input of string s from the user.
3. To set two variables:i = 0 (start index) and j = len(s) - 1 (end index)
4. To set is_palindrome = True
5. To repeat using while statement,if s[i] != s[j]
6. To set is_palindrome = False using break loop.
7. To increment i and decrement j by value of 1
8. If is_palindrome == True print Yes using if statement.
9. Else print No using else statement.
10. End.
# Algorithm- 7.6 Part 3
1. Start
2. To input a string and store it in variable st.
3. To reverse the string and create a new variable rev such that rev = reverse of st.
4. To compare both strings and if st == rev then it print "Palindrome" uisng if statement.
5. Else it prints "Not a Palindrome" using else statement.
# Algorithm-7.7
1. Start.
2. To input a number and store it in variable num.
3. To initialize a variable count with 0.
4. To repeat while num > 0 using while statement.
5. To increase count by 1 using count = count + 1.
6. To remove the last digit of the number using num = num // 10.
7. To display the result(number of digits).
8. End
# Algorithm-7.8
1. Start
2. To initialize variable i = 1.
3. To repeat while i < 6 until statement false using while statement.
4. To print the value of i
5. To check condition:if i == 3 using if then exit the loop using break and increment i by 1 using i = i + 1.
6. End.
# Algorithm 7.9
1. Start
2. To initialize the list
3. To input the element to search and store it in key
4. To initialize index variable i = 0 and to to repeat while i < length of nums using while statement.
5. If nums[i] == key then it prints "Element found at index" by i+1 and to exit loop using break.
6. Else it increments i by 1,if loop ends without break (element not found) and prints "Element not found".
7. End.
# Algorithm 7.10
1. Start
2. To initialize variable i = 0 and repeat while i < 10 using while statement.
3. To increment i by 1 using i = i + 1
4. To check if i is even and if i % 2 == 0 using if statement under while.
5. To skip the remaining steps using continue otherwise it print the value of i using continue.
6. End.
# Conclusion
The while loop in Python is used to execute a block of code repeatedly as long as a given condition is true. It is an entry-controlled loop, meaning the condition is checked before each iteration. It is especially useful when the number of repetitions is not known in advance. Proper updating of the condition is important to avoid infinite loops.


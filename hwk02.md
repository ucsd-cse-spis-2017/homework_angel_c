
1. Guttag discusses variables and names at some length on pages 12 and 13 (section 2.1.2) What are the four most important points that you would take away from this section? A variable is just a name in python. An assignment is associated with the name to the left of the "=" and the expression on the right of the "=" as well. Variable names can have uppercase and lowercase letters, digits and the character _ as well. However, variables can't be any of the reserved words in Python such as elif, else, etc.  

2. In Python, indentation and nesting are signficant concepts. Guttag offers an explanation of these, with some examples. If you feel like you understand these from his explanation, my question is: how would YOU explain these concepts to someone new to the Python language? That is: use your own words, not Guttag’s. If you feel like your understanding is still not firm, what questions would you ask about indentation and nesting, after reading Guttag’s explanation? Indentation and nesting are significant concepts in Python specifically because it shows the structure on how Python will read the code such as if the indentation was not in the else or elif then that code will be used after the else or elif.   

3. Suppose you want a Python program to ask the user a question (e.g. “What is your name”?) and store the answer in a variable called “users_name”. How do you do that? 
    users_name = input('What is your name?')

4. Guttag discusses iteration in Section 2.4. A while loop continues while its condition is true, and ends when its condition is false. If it’s condition is false the first time it is encountered, the body of the loop is never even executed once.

    These leaves us with three possibilities:
        A while loop that is never executed
        A while loop that will be executed a finite number of times (e.g. 3)
        A while loop that will never terminate (a so-called “infinite loop”)

      Write an example of each of these kinds of while loops in Python. Try them in IDLE and see what happens.
        -A while loop that is never executed
            x = 0
            while x < 0:
                x += 1
            print(x)
        -A while loop that will be executed a finite number of times
            x = 0 
            while x < 10:
                x += 1
            print(x)
        -A while loop that will never terminate
            x = 0
            while x > 0;
                x += 1
            print(x) 

5. Try the first “finger exercise” on p. 24.
         numXs = int(input('How many times should I print the letter X? '))
         toPrint = ''
         while x < nums:
            x += 1 
         print(toPrint)
       

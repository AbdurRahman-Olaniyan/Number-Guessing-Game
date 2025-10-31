# Number-Guessing-Game
An algorithm (as pseudocode or a list of steps) for a simple number guessing game
## Project Author: Abdur-Rahman Olaniyan
## Project Title: Number Guessing Game Algorithm
## Project Reviewer: Abiodun L. Bakare

## Algorithm
* Step 1: Start

* Step 2: Num_Range = [1, 2, 3, 4, 5, 6, 7, 8, 9, 10]

* Step 3: Secret_num = Select random i from Num_Range

* Step 4: WHILE guess_num IS NOT EQUAL TO Secret_num

    -- prompt user to input their guess
    * Step 5: guess_num = INPUT number from Num_Range

    
    -- check user's guess against the secret number
    * Step 6: IF guess_num IS EQUAL TO Secret_num THEN
        * PRINT('Congratulations, Your guess is correct.')
        * BREAK_LOOP 
        
        -- Exit the WHILE loop
        
    * Step 7: ELSE IF guess_num IS LESS THAN Secret_num THEN

        * PRINT('Your guess is too low, try again')
        
    * Step 8: ELSE IF guess_num IS GREATER THAN Secret_num THEN

        * PRINT('Your guess is too high, try again')
        
    * Step 9: END IF
    
* Step 10: END WHILE 

-- The loop terminates here once the guess is correct

* Step 11: END 

-- Program finishes execution
# Number-Guessing-Game
An algorithm (as pseudocode or a list of steps) for a simple number guessing game
## Project Author: Abdur-Rahman Olaniyan
## Project Title: Number Guessing Game Algorithm
## Project Reviewer: Abiodun L. Bakare

## Algorithm
Step 1: Start

// Define the range of possible numbers
Step 2: Num_Range = [1, 2, 3, 4, 5, 6, 7, 8, 9, 10]

// Select a secret number randomly from the range
Step 3: Secret_num = Select random i from Num_Range

// Begin a continuous loop that only ends when the user guesses correctly
Step 4: WHILE guess_num IS NOT EQUAL TO Secret_num
    // Prompt the user for input
    Step 5: guess_num = INPUT number from Num_Range
    
    // Check the user's guess against the secret number
    Step 6: IF guess_num IS EQUAL TO Secret_num THEN
        // If correct, print a success message and stop the loop
        PRINT('Congratulations, Your guess is correct.')
        BREAK_LOOP // Exit the WHILE loop
        
    Step 7: ELSE IF guess_num IS LESS THAN Secret_num THEN
        // If too low, print feedback and the loop continues to the next iteration
        PRINT('Your guess is too low, try again')
        
    Step 8: ELSE IF guess_num IS GREATER THAN Secret_num THEN
        // If too high, print feedback and the loop continues
        PRINT('Your guess is too high, try again')
        
    Step 9: END IF
    
Step 10: END WHILE // The loop terminates here once the guess is correct

Step 11: END // Program finishes execution
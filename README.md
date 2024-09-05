# Love Calculator

This Python script calculates a "love score" between two names based on the frequency of letters in the words "TRUE" and "LOVE."

## How It Works
1. The user inputs two names.
2. The script combines these names and calculates the frequency of each letter in "TRUE" and "LOVE."
3. It computes the score by concatenating the counts from "TRUE" and "LOVE," then evaluates the score to give a relationship status.

## Steps

1. **Input Names:** 
   - The user is prompted to enter two names.
   
2. **Count Letters:**
   - Count occurrences of each letter in "TRUE" and "LOVE."
   - Compute the sum of counts for each word.

3. **Calculate Score:**
   - Concatenate the counts for "TRUE" and "LOVE" to form a score.

4. **Evaluate Score:**
   - If the score is less than 10 or greater than 90: Print a message saying "you go together like coke and mentos."
   - If the score is between 40 and 50 (inclusive): Print a message saying "you are alright together."
   - Otherwise, just print the score.

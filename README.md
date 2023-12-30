# assignment5
1. Initialize variables: length = 0, wordCount = 0, vowelCount = 0
2. Read the first character from the input.
3. Repeat the following steps until the input character is a point ('.'):
   a. Increment length by 1.
   b. If the current character is an alphabet letter (A-Z or a-z), check if it's a vowel (a, e, i, o, u).
      - If it's a vowel, increment vowelCount by 1.
   c. If the current character is a space, increment wordCount by 1.
   d. Read the next character from the input.
4. Increment wordCount by 1 (considering the last word after the point).
5. Output the results: length, wordCount, and vowelCount.

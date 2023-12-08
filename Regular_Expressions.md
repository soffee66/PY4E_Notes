# We can go our whole lives without using Regular Expressions...
(an old school language)
1. Matching and Extracting Data
   - re.search() resturns a T/F depending on whether the string matches the regex
   - for the matching strings to be extracted, we use re.finall()
     - *Greedy* matching
       - the *repeat* characters (* and +) push *outward* in both directions (greedy) to match the largest possible string
       - non-greedy matching: just add a "?" character
2. Fine-tuning String Extraction
   - refine the match for re.findall()
   - parentheses are not part of the match - but they tell where to start and stop what string to extract
3. String parsing examples
   -  the Double Split Pattern
     - we split a line one way and the grab one piece and split it again

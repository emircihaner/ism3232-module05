# debug_log.md
# Author: Emir Cihaner

## Bug 1
Error type: KeyError
File + line: week8_buggy.py line 11
What the error means: Python tried to find the key 'amount' and couldn't because it doesnt exist.
What I told the duck: First dictionary has it spelled 'amout' so Python is struggling to find 'amount' so it can not even get past the first loop.
What I tried: seeing what line has the error.
How I fixed it: by correcting the misspelling.

## Bug 2
Error type: TypeError
File + line: week8_buggy.py line 16
What the error means: The ">" operater can not be used for the comparison of str and int.
How I fixed it: Change '1000' string to an integer 1000.

## After Fixing Both Bugs
Final output: Total: $5150.00 across 3 records
True
Did pytest pass? Yes
## AI Literacy Reflection
Did I use AI? Yes
If yes -- exact prompt I used: "Why do I get a KeyError on line 11"
What AI explained: It explained that you get KeyError when the dictionary has a key missing.
What I changed myself: I went to the line with the error and located the typo and fixed it.
Can I explain every fixed line? Yes.

## What I learned
I learned how to locate errors by reading tracebacks. I also learned even a slight typo in dictionary keys cause errors and the comparison of a string to an integer is not possible.
# second-order-conditional-sequences
Second order conditional sequences for behavioral experiments and other purposes

This is a list of second order conditional sequences of length eight in a javascript array friendly format. They all fulfill these criteria:

-the digits 1 through 4 appear exactly twice
-each digit is preceded by exactly two different digits once
-there are no sequences of 1234 or 4321 if you repeat it

These are useful for certain types of sequence learning experiments, as you cannot predict the next digit based on the current digit only - you have to take the previous digit into account, too. 1234 and 4321 are excluded here because they might be too easy to chunk up in memory - just drag your finger/hand/face across the keyboard - doubling as an example of embodied cognition.

With all these criteria its a mere 11 sequences. Sadly I did not write the code to find them in a manner that is easily extensible, but maybe some day I will rewrite it and spam variants.

[[2,1,4,3,2,3,4,1],[2,1,4,3,2,4,1,3],[2,3,4,1,2,4,1,3],[2,4,1,3,2,3,4,1],[2,4,1,3,2,4,1,3],[3,1,4,2,3,1,4,2],[3,1,4,2,3,4,2,1],[3,4,1,2,3,1,4,2],[3,4,2,1,3,1,4,2],[3,4,2,1,3,4,2,1],[4,3,1,2,4,3,1,2]] 

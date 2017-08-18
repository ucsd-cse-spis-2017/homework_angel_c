Problem 1: Making Change
An algorithm that finds the smallest set of coins of value exactly n is first set n/8 equal to the number of octals and take the remainder and equal it to n. Second, set n/5 equal to the number of nickels and take the remainder and equal it to n. Third, set n/1 equal to the number of pennies and don't take the remainder because this will allow it to be the smallest set of coins.

Problem 2: Least Expensive Path 




Problem 3: Longest Common Subsequence 
An algorithm that finds a longest common subsequence of two strings, ch as AGCGTAG and GTCAGC,is first putting one on top of the other. Second, look at the first two numbers in both sequences and if they are the same then keep them for the longest common subsequence and if not like in this case then look from the bottom to the next one on top. In this case it matches with the G so then A in the first subseqence can be removed. Keeping the Gs, moving on to the next two repeat the steps, so in this case C and T don't match, so from T looking to the next one in the subsequence above it looks to the next one which again doesn't match so it repeats the same thing and looks to the next which does match. This gets rid of all the non-matching ones and moves to the next ones in both sequences which is C but in this case it doesn't match with any from the top so that one is removed and the others are kept. Then it is repeated where it looks at the next two from both and in this case both match twice so they are kept and the C is removed. This provides the longest common subsequence of GTAG.

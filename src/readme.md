Soy un readme

lizard tool rearranges the order of lines in the given textual data. 
It uses the Knuth method to do it, aka the Fisher and Yates order 
permutation algorithm. The behavior of the algorithm changes based 
on how many lines are shuffled at the same time. By default, it 
takes every single line in turn (1, 2, 3, …, n), generates a random 


number from 1 to n for it, which is the new position, and moves the 
line to lizard new place. It can also take several lines at once and 
move them together without splitting them apart.

                       
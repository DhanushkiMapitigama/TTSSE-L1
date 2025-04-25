# TTSSE-L1

This is a dummy repo for TTSSE lab work on version control

Here we have a python script to find the prime numbers in a given range

Algorithm is improved using sieve of eratosthenes method!

Algorithm: 

-Create a list of numbers from 2 to n. 

-Start with the first number in the list (which is 2). It is prime. 

-Cross out all the multiples of 2 (e.g., 4, 6, 8, 10, etc.). 

-Move to the next uncrossed number in the list. It is 3. Mark it as prime. 

-Cross out all the multiples of 3. 

-Repeat this process: 

-Go to the next uncrossed number (e.g., 5, 7, etc.). 

-Cross out all its multiples. 

-Continue until you reach the square root of n. 

-The remaining uncrossed numbers are all the prime numbers up to n.

t consumes a lot of memory, especially for large values of n, and becomes inefficient as n grows very large. The algorithm also doesn’t take advantage of parallel processing, which can be a drawback for huge ranges. Additionally, it’s not the best choice for testing individual large numbers for primality, or when dealing with very large numbers (e.g., in cryptography), where other methods like the Miller-Rabin test or AKS primality test may be more appropriate.

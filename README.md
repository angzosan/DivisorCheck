# DivisorCheck
This program finds the possibility of a number with bit length n, having a integer divisor d with bit length betweet [n/2-1,n2+1]

The implementation is quite is and the main goal of this script is the familiarity with finding the divisors of a number.

The script consists of two parts. First, finding the divisors of a given number, and second the percentage of those divisors, whose value is between 
(n/2)-1 and (n/2)+1 where n is the bt=it length of the given number.

The function divisors(arg) is responsible for the first part. By simply checking whether the number mod i( = every number between one and n)  equals to zero, and then 
appening an array which by the end will include all the divisors ( including 1 -> if that's not desired, change the range of the loop from range(1,m) to range(2,m) ).

Second to last, there's a counter that measures the numbers in the divisors array that are within the limits set earlier. Last but not lest, this number is divided by the 
total length of the array and we have the percentage.

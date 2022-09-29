# Donuts
You sell donuts but only in boxes of 7 or 13 donuts. Some customer makes an order of n donuts, n being a random variable between 0 and 100. What is the probability that you can fulfill their order?

I wrote a function that solves this problem by simply finding all the multiples of 7 and 13 between 0 and 100. Then you can divide that number by 101 to find the ratio of orders between 0 and 100 that I can take, which is effectively the probability I'm looking for if n is a random variable.

We can then perform analog computations for different multiples and different ranges. The bigger the range, the higher the probability, since higher numbers can be constructed in many more different ways that smaller numbers. 

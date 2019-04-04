# Assignment 1 
Do Exercise 1.10 in *Learning from Data*.  The problem is restated below:

Write a program to flip 1000 fair coins.  Flip each coin 10 times, then select three coins as follows:

* select the first coin flipped (c_1)
* Select the first coin with the minimum number of heads (c_min)
* Select another coin completely at random (c_rand)

Let nu_1, nu_min, nu_rand be the fraction of heads for the three selected coins.  Let mu be the actual probability of heads.

a.  What is mu for the coins?

b.  repeat the experiment a great number of times (e.g., 100,000 times).  collect nu_1, nu_min, nu_rand for each experiment.  Plot histograms of nu_1, nu_min, nu_rand to see what the distribution looks like.  Note that the coin for c_rand and c_min will be probably different for each run.

c. plot the hoeffding bound 2*exp(-2*epsilon^2*N)along with the P(|nu-mu| > epsilon) for different values of epsilon.  N is the number of training examples (10 in this case), and number of hypotheses is M = 1000.

d. Which coins obey Hoeffding bound?  which do not?  why?

e. Explain how the model described here compares to the bin model described in the book and the lecture.
# People You Might Know #
This a Spark program that implements a simple “People You Might Know” social network friendship recommendation algorithm. The key idea is that if two people have a lot of mutual friends, then the system should recommend that they connect with each other.

We use the resilient distributed dataset (RDD).
### Algorithm: 
Let us use a simple algorithm such that, for each user U, the algorithm rec- ommends N = 10 users who are not already friends with U, but have the most number of mutual friends in common with U.

### Requirement: 
PySpark 3.1.2

### Author: 
Yang Lin


How to run Project:

Download code from https://github.com/RugShrub/MachineLearning

ABAGAIL program

1 open up Abagail folder in cmd 
2 "ant" to compile project (download ant?)
3 Run algorithms!


Randomized Hill Climbing
java -cp ABAGAIL.jar project2.SpambaseTest ./wine-goodness.arff rhc 10 <ITERATIONS>

Simulated Annealing
java -cp ABAGAIL.jar project2.SpambaseTest ./wine-goodness.arff sa 10 <ITERATIONS> <INITIAL_TEMP> <COOLING_FACTOR>

Genetic Algorithm
java -cp ABAGAIL.jar project2.SpambaseTest ./wine-goodness.arff sa 10  <ITERATIONS> 400 <MATES_PER_ITERATION> <MUTATIONS_PER_ITERATION>


java -cp ABAGAIL.jar opt.test.TravelingSalesmanTest 


java -cp ABAGAIL.jar opt.test.KnapsackTest 

java -cp ABAGAIL.jar opt.test.FlipFlopTest 


# Maps-GPS
### A heuristic based search algorithm for finding the shortest path between any two cities in the United States.

This program supports various **algorithms** for search such as :
* __Breadth First Search__ - convenient for finding locations that are close by
* __Depth First Search__ - convenient for distant locations
* __Uniform Search__ - Assumes all highways allow for 55mph
* __A-star Search__ - A heuristic based implementation of the algorithm that takes into account the Great Circle Distance between the two nominated cities.

As part of the program, there are various **modes** you may choose to use along with your choice of algorithm :
* __segments__ - finds a route with the fewest turns
* __distance__ - finds a route with the shortest distance
* __time__ - finds a route with the shortest time (*assumes that the car always travels at the speed limit*) 

#### Note
The Astar algorithm supports two extra modes :
* _longtour_ - finds the longest driving distance path that doesn't visit the same city twice
* _statetour_ - finds the shortest path between two cities while visiting exactly one city in every state.

To run the program enter the following on your command line (terminal):

python route.py __\<start-city> \<end-city> \<routing-algorithm>__ __\<mode-choice>__

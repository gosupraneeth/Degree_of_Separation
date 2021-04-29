# Degree_of_Separation

## Description
This project is used to find the degree of separation and the separation path between any two actors using the BFS or DFS algorithm.<br/>
i.e By finding the shortest path between any two actors by choosing a sequence of movies that connects them.
For example, the shortest path between Jennifer Lawrence and Tom Hanks is 2: 
>Jennifer Lawrence is connected to Kevin Bacon by both starring in “X-Men: First Class,” and Kevin Bacon is connected to Tom Hanks by both starring in “Apollo 13.”

large and small folders contains the data set which has the actors and movies names wuth connections between them

## Execution
Run the below command to start the code.
>Run this for small dataset
````
python degrees.py small
````
>Run this for large dataset
````
python degrees.py large
````

utils.py contains algorithm for the BFS and DFS.<br/>
degrees.py manages the dataset and algorithm

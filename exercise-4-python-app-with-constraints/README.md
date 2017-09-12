# Exercise 4
Transform a simple python/redis compose app to a swarm application stack. 

Make one of your swarm nodes a database node and the rest webserver nodes. Ensure that redis is only run on the database node and also ensure that 3 replicas of the python webserver are running on the webserver nodes.
Start this stack and verify that every container is running on the expected node and that the application is answering at port 80.

Hint: 
You need to build the python image and then push it to the Docker hub. Afterwards you can reference it in your swarm application stack.


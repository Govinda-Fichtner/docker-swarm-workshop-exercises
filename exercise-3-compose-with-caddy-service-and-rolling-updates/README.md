# Exercise 3

Create a Docker Compose file which defines one service based on Caddy version 0.10.4 with 3 replicas listening on port 80. 
Add an update policy that defines a rolling update with a timespan of 5s between each update. 

Then update the service with the “docker service” command to use version 0.10.8 of Caddy. Ensure that everything is working afterwards.

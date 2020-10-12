# simple-docker-compose
Run multiple docker containers/services using docker-compose and check the number of visits to a site.

# Run the following command to spin up container for NodeJs server as well as Redis:
docker-compose up

# Go to the following url, and keep checking number of visits on it, by reloading the browser url or opening it in different tabs:
http://localhost:4001

# To stop all the containers spinned up by docker-compose, run the following command from within the location where that corresponding docker-compose.yml file exists:
docker-compose down

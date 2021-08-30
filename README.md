# liferay_trial

Once checked out run the following from the root of this repo:

docker-compose up -d

This will create the application containers as well as the volumes.  Run the following to stop the instance:

docker-compose down

Add the -v flag to destroy the volumes if a fresh instance is required.

docker-compose down -v

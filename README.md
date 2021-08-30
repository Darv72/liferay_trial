# liferay_trial

Once checked out run the following from the root of this repo:

docker-compose up -d

This will create the application containers as well as the volumes.  Run the following to stop the instance:

docker-compose down

Add the -v flag to destroy the volumes if a fresh instance is required.

docker-compose down -v

This project was created following the instructions found here https://liferay.dev/blogs/-/blogs/dockerizing-a-liferay-bundle-part-2 further details can be found there for importing an already existing database.

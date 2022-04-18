# docker-microservices

This code was implemented following a course about dotnet and microservices.

It is based on docker containers and docker-compose orchestration.

To run it, you should have installed on your system, docker and docker-compose.

Then, you can go to the root folder and run the following from the command line:

docker-compose -f docker-compose.yml -f docker-compose.override.yml up -d

It'll take some minutes to build all images and get the services up.

After that, you can go to browser and navigate to:

http://localhost:9000

It'll open the Portainer service and you'll be asked to create a password.
After password creation, please do refresh your browser so you will be able to see the containers running.

The Web UI application is the aspnetrunbasic service.
Also, you can take a look at any API running, just click to open the service and append to the end of URL "/swagger".

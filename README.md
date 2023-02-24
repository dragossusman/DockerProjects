# DockerProjects
# Project 1 - Simpleweb
\
Created a Node js app displaying a text

Created a docker file

Building the image: docker build -t dragossusman/simpleweb . 

Running the container by specifying the port: docker run -p 5000:8080 dragossusman/simpleweb

# Project 2 - Visits
Created a Node js app displaying the number of visits to it with redis and node-app

Created docker file

Used docker-compose to build the image and run the container

# Project 3 - frontend

Created react app

Created docker file

Created Travis CI chain, containing .travis.yml for configuring the app to be build using travis: build image, run docker container, run tests

Created AWS Elasticbeanstalk for deploying the app to AWS

One the flow is completed: code change in github with a pull request being merged, then travis builds image, runs docker container, runs tests, deploys app to AWS

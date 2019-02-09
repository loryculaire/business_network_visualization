# docker-business-network-visualization
docker image for web scraping and data science using Anaconda 

to build image run command:

`docker build -t docker-business-network-visualization .`

to run notebook run command:

`docker run --name docker-business-network-visualization -p 8888:8888 -v "$PWD/notebooks:/opt/notebooks" -d docker-business-network-visualization`

to access notebook:

go to http://localhost:8888/ and enter `root`

to stop running the container:

`docker rm -f docker-business-network-visualization`


# Build the image
$ docker build -t <your username>/<appname> .

# Run the image
$ docker run -p <target-port>:8080 -d <your username>/<appname>

# Get container ID
$ docker ps

# Print app output
$ docker logs <container id>

# See all running images
$ docker ps

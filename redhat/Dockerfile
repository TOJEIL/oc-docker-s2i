# simple dockerfile to test OCP s2i using Dockerfile 

FROM registry.access.redhat.com/ubi7:latest

# Running Module 1A Updating the App ppt pg 37: commentign infinity and removing comment for sleep 30

# CMD ["/bin/bash", "-c", "sleep infinity"]
CMD ["/bin/bash", "-c", "--", "while true; do sleep 30; done;"]

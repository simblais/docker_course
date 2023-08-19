# Use an existing docker image as base
FROM alpine

# Download and install a dependancy
RUN apk add --update redis

# Tell the what to do when it starts as a container
CMD ["redis-server"]
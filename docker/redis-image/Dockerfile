#Use an existing docker image as a base
FROM alpine

#Download and install dependency
RUN apk add --update redis

#Start-up action for image
CMD ["redis-server"]

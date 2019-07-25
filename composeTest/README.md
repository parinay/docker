
Dockerfile - builds docker image \
    FROM starting from Python:3.7 alpine image \
    WORKDIR set working dir to /code \
    ENV set environment vars used \
    RUN command inside container to install necessary packages \
    COPY file inside container
    RUN command
    COPY the currenty dir in the workdir
    CMD set default command for the container to run.


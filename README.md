# docker_flask_app

Dockerfile contents
• FROM defines the base image used to start the build process
• MAINTAINER defines a full name and email address of the image creator
• COPY copies one or more files from the Docker host into the Docker image
• EXPOSE exposes a specific port to enable networking between the container and the outside
world
• RUN runs commands while image is being built from the dockerfile and saves result as a new
layer
• VOLUME is used to enable access from the container to a directory on the host machine
• WORKDIR used to set default working directory for the container
• CMD command that runs when the container starts
• ENTRYPOINT command that runs when the container starts

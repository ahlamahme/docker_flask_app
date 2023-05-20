# docker_flask_app

Dockerfile contents <br>
•  ! FROM defines the base image used to start the build process <br>
• MAINTAINER defines a full name and email address of the image creator <br>
• COPY copies one or more files from the Docker host into the Docker image <br>
• EXPOSE exposes a specific port to enable networking between the container and the outside 
world <br>
• RUN runs commands while image is being built from the dockerfile and saves result as a new
layer <br>
• VOLUME is used to enable access from the container to a directory on the host machine <br>
• WORKDIR used to set default working directory for the container <br>
• CMD command that runs when the container starts <br>
• ENTRYPOINT command that runs when the container starts <br>

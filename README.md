# Getting started

This repository is a sample application for users following the getting started guide at https://docs.docker.com/get-started/.

The application is based on the application from the getting started tutorial at https://github.com/docker/getting-started

# Key Lessons Learned

- I learned how to containerize an application by creating a Dockerfile, building an image, and running it as a container.
- The lab also showed how to update the application by modifying the source code, rebuilding the image, and replacing older containers with the updated version.
- I learned how to share images through Docker Hub, which involves creating a repository and pushing my images so they can be accessed by others. I also tried pulling my image in KodeKloud as well.
- Another key topic was data persistence, where I explored how volumes keep application data intact even when containers are removed.
- The section on bind mounts was especially useful, as it demonstrated how local files can sync with a running container to support real-time development.
- The lab then moved into multi-container concepts, explaining how a custom Docker network allows different containers, like an app and a database, to communicate with each other.
- I also learned how Docker Compose simplifies managing multi-container applications by defining all services in a single configuration file and controlling them with one command.
- Finally, the lab covered image-building best practices, including understanding layers, taking advantage of cached builds, and using multi-stage builds to create smaller, efficient production images.
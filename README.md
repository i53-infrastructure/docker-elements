# docker-elements
Collection of Docker Web Components. This project is currently in progress and our aim is to have custom elements that can be used to interact with Docker API.

## Install

Install the docker elements using bower:

```
bower install docker-elements
```

## Elements in Progress
* `docker-commit` : Commit container
* `docker-container` : UI element to manage a container from a single element that aggregates all container operations

## Docker Host Elements Implemented
* `docker-events`: List events in docker hosts
* `docker-info`: Docker info on the host
* `docker-version`: Docker version on the host
* `docker-ping`: Ping the docker server

## Docker Container Elements Implemented
* `docker-create`: Provides API for creating container
* `docker-ps`: Provides API with listing docker containers
* `docker-attach`: Provides Web Socket connections to docker container using the Docker API
* `docker-attach-terminal`: UI Terminal Element that uses docker-attach
* `docker-changes`: Analyze file changes within the container
* `docker-exec` : Exec Create and Start. Exec-start won't work with CORS for now due to Docker API limitation
* `docker-inspect`: Inspect a container
* `docker-kill`: Kill a container
* `docker-logs`: Get container log, stream is now supported
* `docker-pause`: Pause a container
* `docker-remove` : Remove/delete a container
* `docker-rename` : Rename a container
* `docker-resize` : Resize container TTY
* `docker-restart` : Restart a container
* `docker-start` : Start a container
* `docker-stats` : Get container stats, Stream is now supported
* `docker-stop` : Stop docker container
* `docker-top` : Get Processes info in a container
* `docker-unpause` : Unpause a container
* `docker-wait` : Block until a container exits

## Docker Image Elements implemented
* `docker-images`: Provides a list of docker images on the host
* `docker-pull` : Docker pull image from a registry
* `docker-inspect-image`: Inspect docker image
* `docker-history`: Show container history
* `docker-tag`: Tag an image
* `docker-remove-image`: Docker rmi, remove/delete image
* `docker-search`: Docker Search image

## Elements not yet implemented
* `docker-copy` : Copy files from a container that returns a tar stream
* `docker-archive` : Get an tar archive of a resource in the filesystem of container
* `docker-push`: Push Container to the registry

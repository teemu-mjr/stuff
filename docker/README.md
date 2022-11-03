# Docker installation

### Docker Engine

Docker Engine can only be used from the command line and does not have a GUI

[CentOS Installation](https://docs.docker.com/engine/install/centos/)

[Debian Installation](https://docs.docker.com/engine/install/debian/)

[Fedora Installation](https://docs.docker.com/engine/install/fedora/)

[Ubuntu Installation](https://docs.docker.com/engine/install/ubuntu/)

### Docker Desktop

Docker Desktop uses the docker engine in the back-end but includes a GUI

[Mac Installation](https://docs.docker.com/desktop/install/mac-install/)

[Windows Installation](https://docs.docker.com/desktop/install/windows-install/)

## Test that docker is working after installation

Linux/Mac
```sh
sudo docker run --rm hello-world
```

Windows
```sh
docker run --rm hello-world
```

Expected output:

```sh
Hello from Docker!
This message shows that your installation appears to be working correctly.

To generate this message, Docker took the following steps:
 1. The Docker client contacted the Docker daemon.
 2. The Docker daemon pulled the "hello-world" image from the Docker Hub.
    (amd64)
 3. The Docker daemon created a new container from that image which runs the
    executable that produces the output you are currently reading.
 4. The Docker daemon streamed that output to the Docker client, which sent it
    to your terminal.

To try something more ambitious, you can run an Ubuntu container with:
 $ docker run -it ubuntu bash

Share images, automate workflows, and more with a free Docker ID:
 https://hub.docker.com/

For more examples and ideas, visit:
 https://docs.docker.com/get-started/
```

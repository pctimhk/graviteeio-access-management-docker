# graviteeio-access-management-docker
Gravitee Docker Compose for Red Hat Enterprise Linux 8.x

Hosts all Dockerfiles to build Gravitee.io access Management images.

== How to launch AM environment
You must have 
  https://podman.io/getting-started/installation.html
installed on your machine:

```
$ podman --version
$ podman-compose --version
```

Install via curl
```
$ curl -L https://raw.githubusercontent.com/pctimhk/graviteeio-access-management-docker/master/launch.sh | bash
```

> To change default http port, launch previous command with -s parameter

```
$ curl -L https://raw.githubusercontent.com/pctimhk/graviteeio-access-management-docker/master/launch.sh | bash -s <port>
```

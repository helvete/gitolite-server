## `gitolite-server`: Dockerized Gitolite + Gitweb

This project consists of the docker image definitions that provide repository server + web GUI

### Features

- repositories and ACL stored in volumes (obvious requirement)
- intialization on the first run
- gitweb webserver provides IP whitelist OR basic auth access

### TODO

- improve variable delegation through `fcgiwrap`
- run `fcgiwrap` as a background service instead of part of container `CMD`
- gitweb customizations

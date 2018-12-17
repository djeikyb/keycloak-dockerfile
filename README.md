This is sort of a fork of:

https://github.com/jboss-dockerfiles/keycloak/tree/3.0.0.Final/server-postgres

The official docker image for Keycloak 3.0.0.Final is kind of a mess.
First, the docker hub page — appropriately — has instructions for the current version.
But even pulling the image is a problem.
When it was published, there were separate images for the different backing stores.
If you wanted postgres, you'd use `jboss/keycloak-postgres`.
That image is no longer on docker hub.
No problem right?
Just clone the github repo and build it yourself.
But the docs are wrong.
The examples don't work.

SO.
This repo has:
- a buildable docker image
- working example via docker compose


### AWX with Docker Swarm


run with:  `docker stack deploy -c docker-stack.yaml awx`


There is no support for postgres persistent storage as this is a proof of concept. For production use I recommend external postgres instance.

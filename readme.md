Expose Docker API via port 2375

Start with:
`docker run -p 2375:2375 -v /var/run/docker.sock:/var/run/docker.sock jarkt/docker-remote-api`

Inspired by: https://github.com/jarkt/docker-remote-api

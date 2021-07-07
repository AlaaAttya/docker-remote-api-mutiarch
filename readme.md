Expose Docker API via port 2375

Start with:
`docker run -p 2375:2375 -v /var/run/docker.sock:/var/run/docker.sock alaaattya/docker-remote-api-mutiarch:latest`


Inspired by: https://github.com/jarkt/docker-remote-api


#### Warning
This is not a secure way to do it. Recommended only if you want to try it within your home/local network

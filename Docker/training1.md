# Docker Training #1

Notes taken from [A Hands-On Introduction To Docker Containers](https://linuxconfig.org/a-hands-on-introduction-to-docker-containers)

Docker trade-offs:
- Unable to run windows guests
- Resource sharing
- Doesn't replace virtualization

```Each container should run only one application.```

> docker images: ```list cached docker images```
	
> docker stop <image_alias>: ```stops the container```
	
```
docker run:
* -d # detaches the container and keeps it in background
* -p 8000:80 # maps host 8000 door to guests 80 door
* -v <host_folder>:<guest_folder> # maps the host folder to a guest folder; changes are applied automatically```

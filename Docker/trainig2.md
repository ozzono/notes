# Docker training #2

Notes taken from [How To Interact With Docker Containers](https://linuxconfig.org/how-to-interact-with-docker-containers)

* docker run
    * -it     # allocates a terminal, aka, attaches the used terminal
        * it can be used later with docker exec command

useful packages to install on debian container: `apt install curl aptitude vim tmux bash-completion gnupg gnupg1 gnupg2 -y`
	
> docker rmi <image_id> # forces the exclusion of the given image
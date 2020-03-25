# jitsi-docker

This repository is a list of some docker compose that will work as jitsi server. All of services that own by jitsi is reformed as container in this repository. So we will using [docker-compose] to deploy this server. 

It look like this repository has been supported to deploy in production. For further reading or guide to install it using docker-compose you can take a look at [quick-start readme]

## What we do with this repo 
In this list we write down what change we made to this repository. We write it refering to license of this original repository. List of what we change :

* Disable P2P feature
* Enable local video recording, it will need jibri they said
* Enable recording button in top-bar

## Disclaimer 
This repo is forked from [official jitsi/docker-jitsi-meet]

## License 
This repository using [Apache License 2.0]

## to-do
* add some badge
* automated build and testing if possible. Because the easiest way to build docker image is using [docker automated test & build]
* write something about it on a blog maybe?

## Timeline Progress
* [25032020] this repo created
* [26032020] Update README.md and try docker-compose SUCCESS

[docker-compose]:https://docs.docker.com/compose/ 
[official jitsi/docker-jitsi-meet]:https://github.com/jitsi/docker-jitsi-meet
[quick-start readme]:https://github.com/scen-git/jitsi-docker/blob/master/SOURCE.md#quick-start
[Apache License 2.0]:https://github.com/scen-git/jitsi-docker/blob/master/LICENSE
[docker automated test & build]:https://docs.docker.com/docker-hub/builds/advanced/
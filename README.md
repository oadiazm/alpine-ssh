# alpine-ssh

A minimal Docker image based on Alpine Linux with a complete package index and only 5 MB in size!

I have prepared this Dockerfile to enable SSH on the alpine docker container.
That is completely working good. 
The above Dockerfile has root enabled in the ssh server as well as run ssh on the time of docker 
container creation.

# How to run the docker container with ssh ?

I have exposed the port 22 in the Dockerfile. You can use the below command to run the docker container.

```bash
$ docker run -d -p 2222:22 oscard/alpine-ssh
```

To connect the docker container via ssh.

```bash
ssh root@localhost -p 2222
```
Use Password: **root**
> Use Password: **root**

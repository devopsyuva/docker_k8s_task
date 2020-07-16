Docker task:

1. change docker root directory from default “/var/lib/docker” to any other location.
2. Configure docker0 bridge interface subnet with different CIDR like “172.30.20.0/24”.
3. Change the default docker0 bridge to any other bridge network for containers created.
4. Connect Docker host (daemon) from remote server (docker client).
5. Investigate on --ink option.
6. Build your own custom image for nginx with below options covered in your Dockerfile:
    FROM
    RUN
    MAINTAINER
    COPY
    ADD
    ENTRYPOINT
    CMD
    ARG
    ENV
    HEALTHCHECK
    EXPOSE
    VOLUME

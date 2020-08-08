Docker task:

1. change docker root directory from default “/var/lib/docker” to any other location.
2. Configure docker0 bridge interface subnet with different CIDR like “172.30.20.0/24”.
3. Change the default docker0 bridge to any other bridge network for containers created.
4. Connect Docker host (daemon) from remote server (docker client).
5. Investigate on --link option.
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
7. Intigrate NFS storage to backend volume mount in Docker
8. Use disk (Example: /dev/sdb) as backend storage for volume mount.
9. Deploy local-registry with TLS (443) certs.
10. Deploy web application (Wordpress) and DB (MariaDB). We need to create a simple web site with the wordpress from browser and verify that details are stored in wordpress DB.
11. Deploy Jenkins CICD with custom parameters mentioned below:
Jenkins should have docker and kubernetes plugin installed as a prerequesit.(Should not be done through jenkins dashboard) --> Dockerfile
Setup jenkins with skipWizard and we should login with our username and password defined in Dockerfile. So that I can login to dashboard directly when I access URL.

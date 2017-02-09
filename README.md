# docker-maven-plugin-bugdemo1

```
[INFO] 
[INFO] --- docker-maven-plugin:0.19.0:start (default-cli) @ docker-maven-plugin-bugdemo1 ---
[INFO] DOCKER> [nginx] "nginx1": Start container 61c1f320ae99
[INFO] DOCKER> [nginx] "nginx1": Waiting for ports [80] directly on container with IP ().
nginx1> 172.23.0.2
[ERROR] DOCKER> [nginx] "nginx1": Timeout after 10017 ms while waiting on tcp port '[localhost/127.0.0.1:80]'
[INFO] DOCKER> [ubuntu] "ubuntu-nginx-tester": Start container 0879f5f08a4c
[ERROR] DOCKER> Error occurred during container startup, shutting down...
[INFO] DOCKER> [ubuntu] "ubuntu-nginx-tester": Stop and removed container 0879f5f08a4c after 0 ms
[INFO] DOCKER> [nginx] "nginx1": Stop and removed container 61c1f320ae99 after 0 ms
[INFO] ------------------------------------------------------------------------
[INFO] BUILD FAILURE
[INFO] ------------------------------------------------------------------------

```

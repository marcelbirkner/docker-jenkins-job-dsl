## Description

Docker Container with Jenkins Job DSL examples. For more details see blog article:

- https://blog.codecentric.de/en/2015/10/using-jenkins-job-dsl-for-job-lifecycle-management/

### Getting started using Image from Docker Hub

```
docker run --publish=8080:8080 mbirkner/docker-jenkins-job-dsl
```

### Run Docker Container using GitHub repository

```
git clone git@github.com:marcelbirkner/docker-jenkins-job-dsl.git
cd docker-jenkins-job-dsl
docker build -t docker-jenkins-job-dsl .
docker run -p=8080:8080 docker-jenkins-job-dsl
```

Once Jenkins is up and running go to http://192.168.59.103:8080

I am using MacOS and Boot2Docker. If you are running Linux or on Windows the IP will be different.

### Links

- Job DSL API https://jenkinsci.github.io/job-dsl-plugin/

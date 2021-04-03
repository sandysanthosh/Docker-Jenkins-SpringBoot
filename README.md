Eclipse-> github -> jenkins-> docker


java -jar Jenkins.war

build a docker image using jenkins step by step

->open broswer:

localhost:8080

### create new job

jenkins docker intergration

freestyle project->click ok



### github project:

add the project URL

source code management:

### GIT:

copy from GIT clone

### Build Triggers:

select Poll SCM:

  Schedule-> *****

->5 start for cron expression each commit

### Build:

invoke top level maven targets

goals => install


### apply and save ..

->To test now:

### BUILD NOW:

 open console output check the build status ->  success or fail


### Jenkins with Docker:

-- Manager Jenkins: do down

-- Manage Plugin:

-- available -> filter type docker

-- cloudbees dockr build ad publish plugin & docker plugin & docker pipeline & docker build step

-- add all the credentials

-- build now and check after success docker image is created or not

### Open docker terminal:

--  docker images


# Template repository for developing workflows for Backstage with Sonataflow

## Description

Use this repository to start developing a new workflow that will eventually be deployed and used from Backstage, using swf plugins[swf-plugins] 



[janus-idp]: https://github.com/janus-idp
[swf-plugins]: https://github.com/janus-idp/backstage-plugins/
[kubesmarts]: start.kubesmarts.io



## Installing and Running

### Prerequisites
 
You will need:
  - Java 11+ installed
  - Environment variable JAVA_HOME set accordingly
  - Maven 3.8.1+ installed

### Compile and Run in Local Dev Mode

```sh
mvn clean package quarkus:dev
```

### Execute the flow using curl

```sh
curl -H "Content-Type: application/json" http://localhost:8080/starter -d '{"key": "value"}'
```


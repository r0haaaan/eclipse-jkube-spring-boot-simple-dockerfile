# Eclipse JKube Spring Boot sample with Dockerfile

This is a simple Spring Boot application which demonstrates how to build
container image for your Java application with a custom Dockerfile with
the help of Eclipse JKube

## How to Build
```
mvn clean install
```

## How to Build Container Image
```
mvn k8s:build
```

## How to Deploy to Kubernetes
```
mvn k8s:resource k8s:apply
```

## How to Undeploy from Kubernetes
```
mvn k8s:undeploy
```

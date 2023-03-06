# Openshift Deployment

The easiest way to deploy this application is to navigate into this folder (java-version or native-version) and then issue :
(you can use a different project name if you want)

```
oc new-project quarkus-java
oc apply -f .
```

After the build process has completed, the application will be running and connected to a postgres deployment.

You can now connect to the deployment service with these endpoints :

http://quarkus-book:8080/api/books
http://quarkus-book:8080/api/publishers

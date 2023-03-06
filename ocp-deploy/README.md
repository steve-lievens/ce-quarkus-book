# Openshift Deployment

The easiest way to deploy this application is to navigate into this folder and then issue :

```
oc new-project <any name you want>
oc apply -f .
```

After the build process has completed, the application will be running and connected to a postgres deployment.

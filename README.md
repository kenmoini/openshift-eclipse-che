# openshift-eclipse-che

Quickly deploy single-user Eclipse Che on OpenShift

This Template can be applied or created to a namespace/project to give developers access to the cloud IDE Eclipse Che.

```
$ oc create -f https://raw.githubusercontent.com/kenmoini/openshift-eclipse-che/master/template-deployer.yml
$ oc new-app openshift-eclipse-che
```
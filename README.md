# openshift-eclipse-che

Quickly deploy single-user Eclipse Che on OpenShift

This Template can be applied or created to a namespace/project to give developers access to the cloud IDE Eclipse Che.

```bash
# HTTP Route
$ oc create -f https://raw.githubusercontent.com/kenmoini/openshift-eclipse-che/master/template-deployer.yml
# HTTPS Edge TLS Route
$ oc create -f https://raw.githubusercontent.com/kenmoini/openshift-eclipse-che/master/template-deployer-secure.yml
$ oc new-app openshift-eclipse-che
```

***Suggested package:*** Makes use of [openshift-icons](https://github.com/kenmoini/openshift-icons)

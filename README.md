## Deploy and manage a simple helm chart

To create the helm chart:
```
helm create health
```

Modify resource files in health/templates directory appropriately. Change values in values.yaml to override the ones in resources files of template directory. These values are references in resource files using jinja2 notation.

To install the helm chart:
```
helm install healthify health
```

To list the helm chart installed:
```
helm list
```

To delete the helm chart:
```
helm delete healthify
```

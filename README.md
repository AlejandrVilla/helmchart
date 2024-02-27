# A host chart using github pages

- To add the chart to your repositories use
```
helm repo add [name] https://alejandrvilla.github.io/helmchart/
helm search repo [name]
```

- To install the package
```
helm install [release] [chart name]
```

- Check the resources created
```
kubectl get all
```

- To uninstall a realease
```
helm uninstall [release]
```

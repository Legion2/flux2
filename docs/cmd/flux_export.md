---
title: "flux export command"
---
## flux export

Export resources in YAML format

### Synopsis

The export sub-commands export resources in YAML format.

### Options

```
      --all    select all resources
  -h, --help   help for export
```

### Options inherited from parent commands

```
      --context string      kubernetes context to use
      --kubeconfig string   absolute path to the kubeconfig file
  -n, --namespace string    the namespace scope for this operation (default "flux-system")
      --timeout duration    timeout for this operation (default 5m0s)
      --verbose             print generated objects
```

### SEE ALSO

* [flux](/cmd/flux/)	 - Command line utility for assembling Kubernetes CD pipelines
* [flux export alert](/cmd/flux_export_alert/)	 - Export Alert resources in YAML format
* [flux export alert-provider](/cmd/flux_export_alert-provider/)	 - Export Provider resources in YAML format
* [flux export helmrelease](/cmd/flux_export_helmrelease/)	 - Export HelmRelease resources in YAML format
* [flux export image](/cmd/flux_export_image/)	 - Export image automation objects
* [flux export kustomization](/cmd/flux_export_kustomization/)	 - Export Kustomization resources in YAML format
* [flux export receiver](/cmd/flux_export_receiver/)	 - Export Receiver resources in YAML format
* [flux export source](/cmd/flux_export_source/)	 - Export sources


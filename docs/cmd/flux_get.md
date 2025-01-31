---
title: "flux get command"
---
## flux get

Get the resources and their status

### Synopsis

The get sub-commands print the statuses of Flux resources.

### Options

```
  -A, --all-namespaces   list the requested object(s) across all namespaces
  -h, --help             help for get
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
* [flux get alert-providers](/cmd/flux_get_alert-providers/)	 - Get Provider statuses
* [flux get alerts](/cmd/flux_get_alerts/)	 - Get Alert statuses
* [flux get helmreleases](/cmd/flux_get_helmreleases/)	 - Get HelmRelease statuses
* [flux get images](/cmd/flux_get_images/)	 - Get image automation object status
* [flux get kustomizations](/cmd/flux_get_kustomizations/)	 - Get Kustomization statuses
* [flux get receivers](/cmd/flux_get_receivers/)	 - Get Receiver statuses
* [flux get sources](/cmd/flux_get_sources/)	 - Get source statuses


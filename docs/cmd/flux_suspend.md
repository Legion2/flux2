---
title: "flux suspend command"
---
## flux suspend

Suspend resources

### Synopsis

The suspend sub-commands suspend the reconciliation of a resource.

### Options

```
  -h, --help   help for suspend
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
* [flux suspend alert](/cmd/flux_suspend_alert/)	 - Suspend reconciliation of Alert
* [flux suspend helmrelease](/cmd/flux_suspend_helmrelease/)	 - Suspend reconciliation of HelmRelease
* [flux suspend image](/cmd/flux_suspend_image/)	 - Suspend image automation objects
* [flux suspend kustomization](/cmd/flux_suspend_kustomization/)	 - Suspend reconciliation of Kustomization
* [flux suspend receiver](/cmd/flux_suspend_receiver/)	 - Suspend reconciliation of Receiver
* [flux suspend source](/cmd/flux_suspend_source/)	 - Suspend sources


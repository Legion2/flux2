---
title: "flux resume command"
---
## flux resume

Resume suspended resources

### Synopsis

The resume sub-commands resume a suspended resource.

### Options

```
  -h, --help   help for resume
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
* [flux resume alert](/cmd/flux_resume_alert/)	 - Resume a suspended Alert
* [flux resume helmrelease](/cmd/flux_resume_helmrelease/)	 - Resume a suspended HelmRelease
* [flux resume image](/cmd/flux_resume_image/)	 - Resume image automation objects
* [flux resume kustomization](/cmd/flux_resume_kustomization/)	 - Resume a suspended Kustomization
* [flux resume receiver](/cmd/flux_resume_receiver/)	 - Resume a suspended Receiver
* [flux resume source](/cmd/flux_resume_source/)	 - Resume sources


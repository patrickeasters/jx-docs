---
date: 2019-07-17T23:41:08Z
title: "jx gc pods"
slug: jx_gc_pods
url: /commands/jx_gc_pods/
---
## jx gc pods

garbage collection for pods

### Synopsis

Garbage collect old Pods that have completed or failed

```
jx gc pods [flags]
```

### Examples

```
  # garbage collect old pods of the default age
  jx gc pods
  
  # garbage collect pods older than 10 minutes
  jx gc pods -a 10m
```

### Options

```
  -a, --age duration       The minimum age of pods to garbage collect. Any newer pods will be kept (default 1h0m0s)
  -h, --help               help for pods
  -n, --namespace string   The namespace to look for the pods. Defaults to the current namespace
  -s, --selector string    The selector to use to filter the pods
```

### Options inherited from parent commands

```
  -b, --batch-mode                Runs in batch mode without prompting for user input (default true)
      --config-file string        Configuration file used for installation
      --install-dependencies      Enables automatic dependencies installation when required
      --no-brew                   Disables brew package manager on MacOS when installing binary dependencies
      --skip-auth-secrets-merge   Skips merging the secrets from local files with the secrets from Kubernetes cluster
      --verbose                   Enables verbose output
```

### SEE ALSO

* [jx gc](/commands/jx_gc/)	 - Garbage collects Jenkins X resources

###### Auto generated by spf13/cobra on 17-Jul-2019

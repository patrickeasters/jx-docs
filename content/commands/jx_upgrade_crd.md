---
date: 2019-07-17T23:41:08Z
title: "jx upgrade crd"
slug: jx_upgrade_crd
url: /commands/jx_upgrade_crd/
---
## jx upgrade crd

Upgrades the Jenkins X Custom Resource Definitions in the Kubernetes Cluster

### Synopsis

Upgrades the Jenkins X Custom Resource Definitions in the Kubernetes Cluster

```
jx upgrade crd [flags]
```

### Examples

```
  # Upgrades the Custom Resource Definitions
  jx upgrade crd
```

### Options

```
  -h, --help   help for crd
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

* [jx upgrade](/commands/jx_upgrade/)	 - Upgrades a resource

###### Auto generated by spf13/cobra on 17-Jul-2019

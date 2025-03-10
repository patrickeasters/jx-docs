---
date: 2019-07-17T23:41:08Z
title: "jx diagnose"
slug: jx_diagnose
url: /commands/jx_diagnose/
---
## jx diagnose

Print diagnostic information about the Jenkins X installation

### Synopsis

Print diagnostic information about the Jenkins X installation

```
jx diagnose [flags]
```

### Options

```
  -h, --help               help for diagnose
  -n, --namespace string   The namespace to display the kube resources from. If left out, defaults to the current namespace
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

* [jx](/commands/jx/)	 - jx is a command line tool for working with Jenkins X

###### Auto generated by spf13/cobra on 17-Jul-2019

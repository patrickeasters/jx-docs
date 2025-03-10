---
date: 2019-07-17T23:41:08Z
title: "jx scan cluster"
slug: jx_scan_cluster
url: /commands/jx_scan_cluster/
---
## jx scan cluster

Performs a cluster security scan

### Synopsis

Performs a cluster security scan

```
jx scan cluster [flags]
```

### Options

```
  -h, --help            help for cluster
  -o, --output string   output format is one of: yaml|plain (default "plain")
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

* [jx scan](/commands/jx_scan/)	 - Perform a scan action

###### Auto generated by spf13/cobra on 17-Jul-2019

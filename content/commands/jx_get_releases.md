---
date: 2019-07-17T23:41:08Z
title: "jx get releases"
slug: jx_get_releases
url: /commands/jx_get_releases/
---
## jx get releases

Display the Release or Releases the current user is a member of

### Synopsis

Display one or more Releases

```
jx get releases [flags]
```

### Examples

```
  # List the recent releases done by this team
  jx get release
  
  # Filter the releases
  jx get release -f myapp
```

### Options

```
  -f, --filter string      Filter the releases with the given text
  -h, --help               help for releases
  -n, --namespace string   The namespace to view or defaults to the current namespace
  -o, --output string      The output format such as 'yaml'
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

* [jx get](/commands/jx_get/)	 - Display one or more resources

###### Auto generated by spf13/cobra on 17-Jul-2019

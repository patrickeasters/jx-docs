---
date: 2019-07-17T23:41:08Z
title: "jx context"
slug: jx_context
url: /commands/jx_context/
---
## jx context

View or change the current Kubernetes context (Kubernetes cluster)

### Synopsis

Displays or changes the current Kubernetes context (cluster).

```
jx context [flags]
```

### Examples

```
  # to select the context to switch to
  jx context
  
  # or the more concise alias
  jx ctx
  
  # view the current context
  jx ctx -b
  
  # Change the current namespace to 'minikube'
  jx ctx minikube
```

### Options

```
  -f, --filter string   Filter the list of contexts to switch between using the given text
  -h, --help            help for context
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

---
date: 2019-07-17T23:41:08Z
title: "jx step helm env"
slug: jx_step_helm_env
url: /commands/jx_step_helm_env/
---
## jx step helm env

Generates the helm environment variables

### Synopsis

Generates the helm environment variables

```
jx step helm env [flags]
```

### Examples

```
  # output the helm environment variables that should be set to use helm directly
  jx step helm env
```

### Options

```
      --clone-https git@foo/bar.git   Clone the environment Git repo over https rather than ssh which uses git@foo/bar.git (default true)
  -d, --dir string                    The directory containing the helm chart to apply (default ".")
      --git-provider string           The Git provider for the environment Git repository (default "github.com")
  -h, --help                          help for env
      --remote                        If enabled assume we are in a remote cluster such as a stand alone Staging/Production cluster
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

* [jx step helm](/commands/jx_step_helm/)	 - helm [command]

###### Auto generated by spf13/cobra on 17-Jul-2019

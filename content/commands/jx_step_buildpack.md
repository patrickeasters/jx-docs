---
date: 2019-07-17T23:41:08Z
title: "jx step buildpack"
slug: jx_step_buildpack
url: /commands/jx_step_buildpack/
---
## jx step buildpack

buildpack [command]

### Synopsis

buildpack [command]

```
jx step buildpack [flags]
```

### Options

```
  -h, --help   help for buildpack
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

* [jx step](/commands/jx_step/)	 - pipeline steps
* [jx step buildpack apply](/commands/jx_step_buildpack_apply/)	 - Applies the current teams build pack to the project to add any missing resources like a Jenkinsfile

###### Auto generated by spf13/cobra on 17-Jul-2019

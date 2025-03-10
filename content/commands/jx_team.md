---
date: 2019-07-17T23:41:08Z
title: "jx team"
slug: jx_team
url: /commands/jx_team/
---
## jx team

View or change the current team in the current Kubernetes cluster

### Synopsis

Displays or changes the current team. 

For more documentation on Teams see: https://jenkins-x.io/about/features/#teams

```
jx team [flags]
```

### Examples

```
  # view the current team
  jx team -b
  
  # pick which team to switch to
  jx team
  
  # Change the current team to 'cheese'
  jx team cheese
```

### Options

```
  -h, --help   help for team
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

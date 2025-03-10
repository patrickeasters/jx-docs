---
date: 2019-07-17T23:41:08Z
title: "jx create docs"
slug: jx_create_docs
url: /commands/jx_create_docs/
---
## jx create docs

Creates the documentation files

### Synopsis

Creates the documentation markdown files

```
jx create docs [flags]
```

### Examples

```
  # Create the documentation files
  jx create docs
```

### Options

```
  -d, --dir string   the directory to generate the docs into (default ".")
  -h, --help         help for docs
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

* [jx create](/commands/jx_create/)	 - Create a new resource

###### Auto generated by spf13/cobra on 17-Jul-2019

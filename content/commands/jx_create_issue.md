---
date: 2019-07-17T23:41:08Z
title: "jx create issue"
slug: jx_create_issue
url: /commands/jx_create_issue/
---
## jx create issue

Create an issue on the git project for the current directory

### Synopsis

Creates an issue in a the git project of the current directory

```
jx create issue [flags]
```

### Examples

```
  # Create an issue in the current project
  jx create issue -t "something we should do"
  
  
  # Create an issue with a title and a body
  jx create issue -t "something we should do" --body "
  some more
  text
  goes
  here
  ""
  "
```

### Options

```
      --body string         The body of the issue
      --dir string          The source directory used to detect the Git repository. Defaults to the current directory
  -h, --help                help for issue
  -l, --label stringArray   The labels to add to the issue
  -t, --title string        The title of the issue to create
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

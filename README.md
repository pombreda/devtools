# Sourcegraph devtools

Tools for managing repositories and build processes for the source code that
powers Sourcegraph.com and srclib.

## Usage


### Create a new repository

To create a new repository from
[srclib-template-project](https://github.com/sourcegraph/srclib-template-project),
run:

```bash
$ scripts/github-setup -f $FLOWDOCK_TOKEN -t $GITHUB_TOKEN new-repo $REPO_NAME
$ scripts/init-repo-from-template $REPO_NAME
```


### Update repository hooks

To update repository hooks for all srclib repositories, run:

```bash
$ scripts/github-setup -f $FLOWDOCK_TOKEN -t $GITHUB_TOKEN reset-repo-hooks
```

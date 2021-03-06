## gitkube

Build and deploy docker images to Kubernetes using git push

### Synopsis

Install Gitkube and manage its Remotes on a Kubernetes cluster

### Examples

```
  # Get your application running on Kubernetes in 4 simple steps.

  # Step 1: Install Gitkube on a Kubernetes cluster:
  gitkube install

  # Step 2: Generate a Gitkube Remote spec interactively and save it as 'example-remote.yaml':
  gitkube remote generate -f example-remote.yaml

  # Step 3: Create a Remote defined in 'example-remote.yaml' on the cluster:
  gitkube remote create -f example-remote.yaml
  # outputs the remote url

  # Step 4: Add remote to the git repo and push:
  git remote add example <remote_url>
  git push example master
```

### Options

```
  -h, --help                  help for gitkube
      --kube-context string   kubernetes context to use
```

### SEE ALSO

* [gitkube install](gitkube_install.md)	 - Install Gitkube on a Kubernetes cluster
* [gitkube remote](gitkube_remote.md)	 - Manage Gitkube Remotes on a cluster
* [gitkube uninstall](gitkube_uninstall.md)	 - Uninstall Gitkube components from a cluster
* [gitkube version](gitkube_version.md)	 - Output the cli version

###### Auto generated by spf13/cobra on 26-May-2018

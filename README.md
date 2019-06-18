# ansible-role-repo

Ansible playbook to automate installing
[Google repo](https://code.google.com/p/git-repo/).

## Requirements

None (other than Ansible).

## Role Variables

Available variables are listed below, along with default values (see `defaults/main.yml`):

```yaml
# The URL from which to get the repo utility.
repo_url: https://storage.googleapis.com/git-repo-downloads/repo

# The directory into which to place the repo tool.
# This should be on your PATH as the role does not add the directory thereto.
repo_dir: /usr/local/bin
```

## Example playbook

```
---
- hosts: developers
  roles:
    - repo
```

# License and Copyright
 
Copyright 2015 VMware, Inc.  All rights reserved.

SPDX-License-Identifier: Apache-2.0 OR GPL-3.0-only

This code is Dual Licensed Apache-2.0 or GPLv3

## Author Information

This role was created in 2015 by [Tom Hite / VMware](http://www.vmware.com/).

# ansible-role-repo

Ansible playbook to automate installing Google repo.

## Requirements

None (other than Ansible).

## Role Variables

Available variables are listed below, along with default values (see `defaults/main.yml`):

    repo_url: [https://storage.googleapis.com/git-repo-downloads/repo](https://storage.googleapis.com/git-repo-downloads/repo)

The URL from which to get the repo utility.

    repo_dir: /usr/local/bin

The directory into which to place the repo tool. This should be on your PATH as the role does not add the directory thereto.

## Example playbook
```
---
- hosts: developers
  roles:
    - repo
```

# License and Copyright
 
Copyright 2015 VMware, Inc.

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

    http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.

## Author Information

This role was created in 2015 by [Tom Hite / VMware](http://www.vmware.com/).

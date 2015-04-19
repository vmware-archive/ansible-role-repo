# ansible-role-repo

Ansible playbook to automate installing Google repo.

## Requirements

None (other than Ansible).

## Role Variables

Available variables are listed below, along with default values (see `defaults/main.yml`):

    repo_url: [https://storage.googleapis.com/git-repo-downloads/repo](https://storage.googleapis.com/git-repo-downloads/repo)
    repo_dir: /usr/local/bin

## Example playbook
```
---
- hosts: developers
  roles:
    - repo
```

## License

TBD

## Author Information

This role was created in 2015 by [Tom Hite / VMware](http://www.vmware.com/).

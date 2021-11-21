# ansible-role-elasticsearch
 Install ElasticSearch on CentOS with basic auth enabled.

## Example playbook
```
---
- hosts: all
  roles:
    - role: ansible-role-elasticsearch
```
## todo list
- [x] Auto gen passwords on init
- [x] Add HTTPS/TLS options
- [ ] Add multi node support for clustering
- [ ] Uninstall tag to remove
- [ ] Upgrade tag to control rollouts?

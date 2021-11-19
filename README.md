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
- [ ] Add HTTPS/TLS options
- [ ] Add multi node support for clustering

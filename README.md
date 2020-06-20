# ansible-role-distribution

## Pre-requisite
Check all your distros
```shell script
 ansible all -m setup -a "filter=ansible_distribution"  -i inventory
```
## Use a role for all distros


# sol1-packages_repo
Ansible Role to install packages.sol1.net apt repo.

Add in `roles/requirements`
```
- name: sol1.packages_repo
  src: git+https://github.com/sol1-ansible/sol1-packages_repo
  version: main
```  

## Dependant roles should have the dependancy as `sol1.packages_repo`
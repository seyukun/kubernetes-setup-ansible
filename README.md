# Workspace Setup

```bash
pipenv shell
pipenv install
pipenv run ansible-galaxy-install
```

# Usage
```bash
cd ansible
ansible-playbook -i inventory.yml playbook.yml -CD -l master # check diff only
ansible-playbook -i inventory.yml playbook.yml -D -l master
```

# Пример деплоя Django в различных средах

## Vagrant + Ansible
в Vagrantfile заменить путь к приватным ключам на свой

```
ansible-galaxy install -r ansible/requirements.yml --force
vagrant up
ansible-playbook -i ansible/inventory ansible/provision.yml
```

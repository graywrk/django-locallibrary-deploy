# Пример деплоя Django в различных средах

## Vagrant + Ansible
в Vagrantfile заменить путь к приватным ключам на свой

```
ansible-galaxy install -r requirements.yml
vagrant up
ansible-playbook -i inventory provision.yml
```

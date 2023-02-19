# deploy-config
## Описание
Шаблоны файлов для деплоя, ansible-playbooks
## Деплой
```shell
ansible-playbook -i hosts -l stage deploy.yml -e ci_build_token=token -e ci_user=user -e ci_registry=ci_registry
```
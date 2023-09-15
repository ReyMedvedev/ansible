простий приклад роботи з Ansible<br>
спочатку я терраформом піднімаю інфраструктуру в aws та отримую ip сервера<br>
заношу його у ```hosts``` та ансіблом встановлює докер, гіт клоню проект та піднімаю його:<br>
<br>```ansible-playbook install-docker.yaml```
<br>```ansible-playbook clone-and-deploy.yaml```
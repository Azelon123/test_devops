Инструкция
Вставить в файл inventory.ini username хоста(по дефолту debian)
ip хоста и изменить путь к ссш ключам ansible_ssh_private_key_file
Запускаем плейбук в директории ansible
Команда для запуска ansible-playbook -i inventory.ini playbook.yml

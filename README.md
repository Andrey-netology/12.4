1. Задание 

Запускаем 5 нод с помощью Vagrant 

![alt text](https://github.com/Andrey-netology/12.4/blob/main/Vagrantfile "Logo Title Text 1")

На мастер ноде генерим ключ с помощью команды  ssh-keygen
Потом на каждый ноду копируем ключ ssh-copy-id username@remote_host

Для настройки использовал данную статью: https://rebrainme.com/blog/kubernetes/sozdanie-klastera-kubernetes-na-vps-s-pomoshhyu-kubespray/
Создал необходимый файл hosts.ini 

![alt text](https://github.com/Andrey-netology/12.4/blob/main/host.ini "Logo Title Text 1")

Запустил установку и получил следующий результат: 

![alt text](https://github.com/Andrey-netology/12.4/blob/main/task "Logo Title Text 1")



1. Задание 

Запускаем 5 нод с помощью Vagrant 

Vagrantfile

На мастер ноде генерим ключ с помощью команды  ssh-keygen
Потом на каждой рабочей ноде создаем файл authorized_keys и копируем туда публичный ключ с мастера 

В k8s_cluster установил параметр container_manager: containerd

Создал необходимый файл hosts.ini 

Запустил установку через kubespray



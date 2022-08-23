## Готовый докер

Загрузка образа nginx через команду `docker pull`
![docker_pull](screenshots/docker_pull.png)
Проверка наличия образа через команду `docker images`
![docekr_images](screenshots/docker_images.png)
Запуск образа через комнаду `docker run`
![docker_run](screenshots/docker_run.png)
Проверка наличия процесса через команду `docker ps`
![docker_ps](screenshots/docker_ps.png)
Просмотр информации о контейнере через команду \
`docker inspect %container_id%`
![docker_inspect](screenshots/docker_inspect.png)
Размер докер образа
![docker_shmsize](screenshots/docker_shmsize.png)
Его IP
![docker_ip](screenshots/docker_ip.png)
Замапленый порт\
![docker_port](screenshots/docker_port.png)\
Остановка докер образа и проверка его остановки
![docker_stop](screenshots/docker_stop.png)
Запуск образа с замапленными портами
![docker_map](screenshots/docker_map.png)
Проверка работы сервера
![docker_localhost](screenshots/docker_localhost.png)
Перезагрузка докер образа и проверка наличия процесса
![docker_restart](screenshots/docker_restart.png)

## Операции с контейнером

Вывод содержимого файла nginx.conf
![docker_exec](screenshots/docker_exec.png)

Создание файла nginx.conf и астройка в нем по пути /status отдачу страницы статуса сервера
![docker_nginx_conf](screenshots/docker_nginx_conf.png)
Коприование nginx.conf внутрь докер образа, перезагрузка nginx, проверка статуса сервера
![docker_nginx_conf_cp](screenshots/docker_nginx_conf_cp.png)
Экспорт докер контейнера в файл, остановка контейнера
![docker_export](screenshots/docker_export.png)
Удаление докер образа
![docker_rmi](screenshots/docker_rmi.png)
Удаление остановленного контейнера
![docker_rm](screenshots/docker_rm.png)
Импорт сохраненного контейнера, его запуск и проверка работоспособности
![docker_import](screenshots/docker_import.png)

## Мини веб-сервер

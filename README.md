# Исходники сайта [matematika.net](https://matematika.net)

<br/>

### Запустить matematika.net для разработки

    $ docker-compose up

<br/>

### Запустить matematika.net локально как сервис

<a href="https://sysadm.ru/linux/servers/containers/docker/install/">Docker</a> должен быть установлен.

    # cp matematika.net.service /etc/systemd/system/matematika.net.service

<br/>

    # systemctl enable matematika.net.service
    # systemctl start  matematika.net.service
    # systemctl status matematika.net.service

http://localhost:4018

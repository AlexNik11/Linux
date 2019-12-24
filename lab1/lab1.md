## Отчет по лабораторной работе N 1

## Задание № 1

#Написать сервис, который будет раз в 30 секунд мониторить лог на предмет наличия ключевого слова. Файл и слово должны задаваться в /etc/sysconfig

# создать конфиг. файл 

![](screnshots/sysconf.png)

# Создаем файл /var/log/watchlog.log

![](screnshots/log.png)

# Создадим скрипт

![](screnshots/sh.png)

# Создадим юнит для сервиса

![](screnshots/service.png)

# Создадим юнит для таймера

![](screnshots/timer.png)

# Запустить и убедиться в результате

![](screnshots/start.png)

## Задание № 2

#  Из epel установить spawn-fcgi и переписать init-скрипт на unit-файл. Имя сервиса должно также называться

![](screnshots/comentcos.png)

![](screnshots/start-fcgi.png)

## Задание № 3

# Дополнить юнит-файл apache httpd возможностью запустить несколько инстансов сервера с разными конфигурациями

![](screnshots/httpd.png)

![](screnshots/first.png)
![](screnshots/second.png)
![](screnshots/second1.png)



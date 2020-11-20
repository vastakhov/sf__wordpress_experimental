


# Содержание

1. [Установка Vagrant](##-1.-Установка-Vagrant)
2. [Копирование репозитория](##-2.-Копирование-репозитория)
3. [Запуск виртуальной машины с Wordpress](##-3.-Запуск-виртуальной-машины-с-Wordpress)


## 1. Установка Vagrant

Установка для Debian подобных систем

`sudo apt install -y vagrant`
***

Установка для RHEL подобных систем

`sudo yum install -y vagrant`
***
Установка для Arch подобных систем

`sudo pacman -S Vagrant`
***
## 2. Копирование репозитория

`git clone git@github.com:vastakhov/sf__wordpress_experimental.git`
***
Переходим в папку с репозиторием

`cd sf__wordpress_experimental`

## 3. Запуск виртуальной машины с Wordpress

`vagrant up`

***
WordPress будет доступен по адресу http://192.168.33.11:8080
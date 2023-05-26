# Домашнее задание к занятию «Ansible. Часть 1» Sychugov Konstantin

## **Задание 1**
Ответьте на вопрос в свободной форме.

Какие преимущества даёт подход IAC?

**Решение 1**

Подход IAC даёт преимущество в скорости развёртывания и восстановления и масштабируемости инфраструктуры

## **Задание 2**
Выполните действия и приложите скриншоты действий.

Установите Ansible.
Настройте управляемые виртуальные машины, не меньше двух.
Создайте файл inventory. Предлагается использовать файл, размещённый в папке с проектом, а не файл inventory по умолчанию.
Проверьте доступность хостов с помощью модуля ping.

**Решение 2**

Установили Ansible

![image](https://github.com/SKA1010/hw_Ansible1/assets/125235217/b50a732f-31f2-46bb-a05e-1e813fbfe8cd)


## **Задание 3**
Ответьте на вопрос в свободной форме.

Какая разница между параметрами forks и serial?

**Решение 3**

Forks - количество одновременных подключений в задаче, а Serial - это максимальное обрабатываемых хостов в задаче за один запуск

## **Задание 4**
В этом задании вы будете работать с Ad-hoc коммандами.

Выполните действия и приложите скриншоты запуска команд.

Установите на управляемых хостах любой пакет, которого нет.
Проверьте статус любого, присутствующего на управляемой машине, сервиса.
Создайте файл с содержимым «I like Linux» по пути /tmp/netology.txt.

**Решение 4**

Установили пакет на удалённые хосты

![image](https://github.com/SKA1010/hw_Ansible1/assets/125235217/30ebfc0b-e233-4dcb-bda0-2be9b5b99942)

Создаём файл

![image](https://github.com/SKA1010/hw_Ansible1/assets/125235217/197327c2-a633-400c-80cd-e2f63f6e5d31)

Проверили статус:

![image](https://github.com/SKA1010/hw_Ansible1/assets/125235217/2fe78453-0922-400f-9601-59d77b7fff3a)

University: [ITMO University](https://itmo.ru/ru/)
Faculty: [FTMI](https://ftmi.itmo.ru)
Course: [Cloud platforms as the basis of technology entrepreneurship](https://) ADD link
Year: 2024/2025
Group: U4225
Author: Deyna Anastasia Sergeevna
Lab: Lab1
Date of create: 21.10.2023
Date of finished: 21.10.2023

## Задание 1
Cоздаем service account с ролью Storage Admin
ссылка на скрин
(там тополнительно на следующем этапе как раз выбирается роль Security Admin, просто при создании забыла сделать 

## Задание 2
Создаем минимального compute engine (виртуальную машину) с Machine type e2-micro в режиме spot
скрин 
скрин 
скрин 

## Задание 3
Нахождим бакета lab1-bucket-itmo с помощью утилиты gsutils и копируем файлы в локальную папку на VM
скрин 
скрин 

## Задание 4
Меняем права доступа для вашего service account с Storage Admin на Compute Viewer. Выходит ошибка. Есть предположение, что при изменении с роли администратора на роль просмотра, копирование файлов с бакета будет невозможно 

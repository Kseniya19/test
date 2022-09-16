---
# Front matter
lang: ru-RU
title: Защита лабораторной работы №2. Дискреционное разгарничение прав в Linux. Основныет атрибуты 
author: "Бурдина Ксения Павловна"
group: NFIbd-01-19
institute: RUDN University, Moscow, Russian Federation
date: 2022 Sep 15th

# Formatting
toc: false
slide_level: 2
header-includes: 
 - \metroset{progressbar=frametitle,sectionpage=progressbar,numbering=fraction}
 - '\makeatletter'
 - '\beamer@ignorenonframefalse'
 - '\makeatother'
aspectratio: 43
section-titles: true
theme: metropolis

---

# Результат выполнения лабораторной работы №2

# Цель выполнения лабораторной работы 

## Цель выполнения лабораторной работы

Получение практических навыков работы в консоли с атрибутами файлов, закрепление теоретических основ дискреционного разграничения доступа в современных системах с открытым кодом на базе ОС Linux.

# Результат выполнения лабораторной работы

## Результат выполнения лабораторной работы

Создание учётной записи пользователя guest:

![](screens/1.jpg){width=60%}
![рис 1. Создание учетной записи](screens/2.jpg){width=60%}

## Результат выполнения лабораторной работы

Проверка данных пользователя guest:

![рис 2. Информация о пользователе](screens/5.jpg){width=90%}

## Результат выполнения лабораторной работы

Просмотр атрибутов директорий системы:

![рис 3. Просмотр директорий](screens/10.jpg){width=90%}

## Результат выполнения лабораторной работы

Создание поддиректории dir1, определение прав доступа:

![рис 4. Создание поддиректории и просмотр ls -l](screens/12.jpg){width=60%} 

## Результат выполнения лабораторной работы

Снятие с директории dir1 всех атрибутов:

![рис 5. Снятие атрибутов с директории](screens/14.jpg){width=80%}

## Результат выполнения лабораторной работы

Действия для заполнения таблицы:

![](screens/700.jpg){width=70%}
![рис 6. Действия при атрибутах dir1(700) и file(700)](screens/701.jpg){width=70%}

## Результат выполнения лабораторной работы

Общая таблица прав и разрешений:

![рис 7. Таблица прав и разрешений 1](screens/t1.jpg){width=60%}

## Результат выполнения лабораторной работы

![рис 8. Таблица прав и разрешений 2](screens/t2.jpg){width=60%}

## Результат выполнения лабораторной работы

![рис 9. Таблица прав и разрешений 3](screens/t3.jpg){width=60%}

## Результат выполнения лабораторной работы

Минимальные права, необходимые для совершения каждой из операций:

![рис 10. Таблица минимальных прав для совершения операций](screens/t4.jpg){width=80%}

# Выводы

## Выводы

1. Получили практические навыки работы в консоли с атрибутами файлов.

2. Закрепили теоретические основы дискреционного разграничения доступа в современных системах с открытым кодом на базе ОС Linux.

3. Выполнили действия в командной строке и заполнили таблицу с результатами исследования прав на совершение операций.
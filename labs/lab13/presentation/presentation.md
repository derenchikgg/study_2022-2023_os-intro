---
## Front matter
lang: ru-RU
title: Лабораторная работа 
subtitle: Средства, применяемые при разработке программного обеспечения в ОС типа UNIX/Linux
author:
  - Панченко Д. Д.
institute:
  - Российский университет дружбы народов, Москва, Россия
date: 1 мая 2023

## i18n babel
babel-lang: russian
babel-otherlangs: english

## Formatting pdf
toc: false
toc-title: Содержание
slide_level: 2
aspectratio: 169
section-titles: true
theme: metropolis
header-includes:
 - \metroset{progressbar=frametitle,sectionpage=progressbar,numbering=fraction}
 - '\makeatletter'
 - '\beamer@ignorenonframefalse'
 - '\makeatother'
---

# Информация

## Докладчик

  * Панченко Денис Дмитриевич
  * Студент 1 курса факультета физико-математических наук.
  * Российский университет дружбы народов
  * [derenchikde@gmail.com](mailto:derenchikde@gmail.com)

## Цели и задачи

Приобрести простейшие навыки разработки, анализа, тестирования и отладки приложений в ОС типа UNIX/Linux на примере создания на языке программирования С калькулятора с простейшими функциями.

# Выполнение лабораторной работы

## В домашнем каталоге создадим подкаталог ~/work/os/lab_prog.

![Создание подкаталога](image/1.png){#fig:001 width=70%}

## Создадим в нём файлы: calculate.h, calculate.c, main.c.

![Создание файлов](image/2.png){#fig:002 width=70%}

## Реализуем функцию калькулятора в файле calculate.c.

![Реализация функции](image/3.png){#fig:003 width=70%}

## Реализуем интерфейсный файл calculate.h, описывающий формат вызова функции-калькулятора.

![Реализация интерфейсного файла](image/4.png){#fig:004 width=70%}

## Реализуем основной файл main.c, реализующий интерфейс пользователя к калькулятору.

![Реализация основного файла](image/5.png){#fig:005 width=70%}

## Выполним компиляцию программы посредством gcc.

![Компиляция программы](image/6.png){#fig:006 width=70%}

## Создадим Makefile со следующим содержанием.

![Создание файла](image/7.png){#fig:007 width=70%}

## 

![Содержание файла](image/8.png){#fig:008 width=70%}

## С помощью gdb выполним отладку программы calcul.

![Запуск](image/9.png){#fig:009 width=70%}

## 

![Запуск программы](image/10.png){#fig:010 width=70%}

## 

![Просмотр кода](image/11.png){#fig:011 width=70%}

## 

![Просмотр строк кода](image/12.png){#fig:012 width=70%}

## 

![Просмотр строк неосновного кода](image/13.png){#fig:013 width=70%}

## 

![Установка точки останова](image/14.png){#fig:014 width=70%}

## 

![Вывод информации о точке](image/15.png){#fig:015 width=70%}

## 

![Запуск программы](image/16.png){#fig:016 width=70%}

## 

![Значение переменной](image/17.png){#fig:017 width=70%}

## 

![Сравнение](image/18.png){#fig:018 width=70%}

## 

![Удаление точки останова](image/19.png){#fig:019 width=70%}

# Вывод

Я приобрел простейшие навыки разработки, анализа, тестирования и отладки приложений в ОС типа UNIX/Linux на примере создания на языке программирования С калькулятора с простейшими функциями.

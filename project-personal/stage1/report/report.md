---
## Front matter
title: "Проект. Персональный сайт научного работника"
subtitle: "Первый этап"
author: "Панченко Денис Дмитриевич"

## Generic otions
lang: ru-RU
toc-title: "Содержание"

## Bibliography
bibliography: bib/cite.bib
csl: pandoc/csl/gost-r-7-0-5-2008-numeric.csl

## Pdf output format
toc: true # Table of contents
toc-depth: 2
lof: true # List of figures
lot: false # List of tables
fontsize: 12pt
linestretch: 1.5
papersize: a4
documentclass: scrreprt
## I18n polyglossia
polyglossia-lang:
  name: russian
  options:
	- spelling=modern
	- babelshorthands=true
polyglossia-otherlangs:
  name: english
## I18n babel
babel-lang: russian
babel-otherlangs: english
## Fonts
mainfont: PT Serif
romanfont: PT Serif
sansfont: PT Sans
monofont: PT Mono
mainfontoptions: Ligatures=TeX
romanfontoptions: Ligatures=TeX
sansfontoptions: Ligatures=TeX,Scale=MatchLowercase
monofontoptions: Scale=MatchLowercase,Scale=0.9
## Biblatex
biblatex: true
biblio-style: "gost-numeric"
biblatexoptions:
  - parentracker=true
  - backend=biber
  - hyperref=auto
  - language=auto
  - autolang=other*
  - citestyle=gost-numeric
## Pandoc-crossref LaTeX customization
figureTitle: "Рис."
tableTitle: "Таблица"
listingTitle: "Листинг"
lofTitle: "Список иллюстраций"
lotTitle: "Список таблиц"
lolTitle: "Листинги"
## Misc options
indent: true
header-includes:
  - \usepackage{indentfirst}
  - \usepackage{float} # keep figures where there are in the text
  - \floatplacement{figure}{H} # keep figures where there are in the text
---

# Цель работы

Разместить на Github pages заготовки для персонального сайта.

# Задание

1. Установить необходимое программное обеспечение.
2. Скачать шаблон темы сайта.
3. Разместить его на хостинге git.
4. Установить параметр для URLs сайта.
5. Разместить заготовку сайта на Github pages.

# Выполнение проекта

Устанавливаем hugo (рис. @fig:001).

![hugo](image/1.png){#fig:001 width=70%}

Создаем репозиторий в github с шаблоном сайта (рис. @fig:002).

![Репозиторий](image/2.png){#fig:002 width=70%}

Создаем на нашем компьютере каталог с репозиторием (рис. @fig:003).

![Каталог](image/3.png){#fig:003 width=70%}

Запускаем hugo (рис. @fig:004).

![hugo](image/4.png){#fig:004 width=70%}

Запускаем hugo server (рис. @fig:005).

![hugo server](image/5.png){#fig:005 width=70%}

Переходим на созданный нами сайт (рис. @fig:006).

![Сайт](image/6.png){#fig:006 width=70%}

Создаем параметр URL для сайта в github (рис. @fig:007).

![URL](image/7.png){#fig:007 width=70%}

Создаем на нашем компьютере каталог с данным параметром (рис. @fig:008).

![Каталог](image/8.png){#fig:008 width=70%}

Создаем в этом каталоге ветку main (рис. @fig:009).

![Ветка](image/9.png){#fig:009 width=70%}

Создаем в этом каталоге файл и отправляем его на github, чтобы наш репозиторий заработал (рис. @fig:010).

![Файл](image/10.png){#fig:010 width=70%}

Создаем в каталоге blog папку public (рис. @fig:011).

![public](image/11.png){#fig:011 width=70%}

Запускаем hugo, чтобы загрузить все нужные файлы в эту папку (рис. @fig:012).

![Папка](image/12.png){#fig:012 width=70%}

Отправляем это все на github (рис. @fig:013).

![github](image/13.png){#fig:013 width=70%}

Открываем наш сайт (рис. @fig:014).

![Сайт](image/14.png){#fig:014 width=70%}

# Вывод

Я разместил на Github pages заготовку для персонального сайта.

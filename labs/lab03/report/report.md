---
## Front matter
title: "Лабораторная работа №3"
subtitle: "Markdown"
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

Научиться оформлять отчёты с помощью легковесного языка разметки Markdown.

# Задание

1. Сделать отчёт по предыдущей лабораторной работе в формате Markdown.
2. В качестве отчёта предоставить отчёты в 3 форматах: pdf, docx и md.

# Выполнение лабораторной работы

Откроем шаблон для отчета в формате markdown (рис. @fig:001).

![Шаблон](image/1.png){#fig:001 width=70%}

Записываем цель и задачи работы (рис. @fig:002).

![Цели и задачи](image/2.png){#fig:002 width=70%}

Перейдем к записи выполнения лабораторной работы (рис. @fig:003).

![Выполнение](image/3.png){#fig:003 width=70%}

Напишем вывод (рис. @fig:004).

![Вывод](image/4.png){#fig:004 width=70%}

Ответим на контрольные вопросы (рис. @fig:005).

![Вопросы](image/5.png){#fig:005 width=70%}

Преобразуем наш файл в форматы docx и pdf (рис. @fig:006 - @fig:007).

![Преобразование](image/6.png){#fig:006 width=70%}

![Файлы в других форматах](image/7.png){#fig:007 width=70%}

# Вывод

Я научился оформлять отчёты с помощью легковесного языка разметки Markdown.

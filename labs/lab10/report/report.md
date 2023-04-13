---
## Front matter
title: "Отчет по лабораторной работе №3"
subtitle: "Операционные системы"
author: "Лукина Ирина"

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
lot: true # List of tables
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

Научиться писать скрипты с помощью редактора для посика директорий и вычислений 


# Выполнение лабораторной работы

1. Создаю новый файл в редакторе emacs и пишу нужный скрипт. Он будет делать копию самого себя в другую директорию. Затем ввожу chmod +x для разрешения доступа.

![Скрипт1](image/1.jpeg){#fig:001 width=70%}

![Работа скрипта1](image/2.jpeg){#fig:002 width=70%}

2. Создаю файл для скрипта-командного файла, который обрабатывает любое число до 10.Сохраняю его и разрешаю доступ. Запускаю скрипт и проверяю работу.

![Скрипт2](image/3.jpeg){#fig:004 width=70%}

![Работа](image/4.jpeg){#fig:005 width=70%}

3. Пишу новый скрипт-аналог команды ls , который будет выдавать информацию о нужном каталоге.
Разрешаю доступ и проверяю работу скрипта.

![Скрипт3](image/5.jpeg){#fig:005 width=70%}

![Работа скрипта](image/6.jpeg){#fig:006 width=70%}

4. Данный скрипт будет получать в качестве аргумента командной строки формат файла и вычисляет  кол-во файлов в указанной директориии

![Скрипт4](image/7.jpeg){#fig:007 width=70%}

![Работа скрипта](image/8.jpeg){#fig:008 width=70%}

# Выводы

В ходе выполнения лабораторной работы я научилась писать скрипты через редактор и работать с ними.

# Список литературы{.unnumbered}

::: {#refs}
:::

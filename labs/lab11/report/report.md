---
## Front matter
title: "Отчет по лабораторной работе №11"
subtitle: "Операционные системы"
author: "Лукина Рина"

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

Написание командных файлов в текстовом редакторе с помощью  getops grep.


# Ход работы

1. Пишу командный файл, который анализирует командную строку с ключами.

![скрипт](image/1.jpeg){#fig:001 width=70%}

![не сработал(](image/2.jpeg){#fig:002 width=70%}

2. Пишу скрипт - программу, которая выводит число и определяет, больше, равно или меньше нуля.

![скрипт](image/3.jpeg){#fig:003 width=70%}

![работа скрипта](image/4.jpeg){#fig:004 width=70%}

3. Пишу командный файл, создающий указанное число файлов, пронумерованных последовательно от 1 до Н

![скрипт](image/5.jpeg){#fig:005 width=70%}

![работа скрипта](image/6.jpeg){#fig:006 width=70%}

4. Пишу командный файл, который с помощью команды tar запаковывает в архив все файлы указанной директории

![скрипт](image/7.jpeg){#fig:007 width=70%}

![не работа скрипта](image/8.jpeg){#fig:008 width=70%}

# Выводы

В ходе лабораторной работы я научилась писать командные файлы.


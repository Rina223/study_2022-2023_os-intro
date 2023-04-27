---
## Front matter
title: "Отчет по лабораторной раоте №12"
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

Изучить основы программирования в оболочке ОС UNIX. Научиться писать более сложные командные файлы с использованием логических управляющих конструкций и циклов.


# Ход работы

1. Создаю файл и прописываю скрипт, реализующий упрощенный механизм семафоров и проверяю его работу в терминале.

![Код](image/1.jpeg){#fig:001 width=70%}

![Работа файла](image/2.jpeg){#fig:002 width=70%}

2. Изучаю содержимое каталога /usr/share/man/man1. И пишу командный файл.

![Каталог](image/3.jpeg){#fig:003 width=70%}

![Файл](image/4.jpeg){#fig:004 width=70%}

![Работа файла](image/5.jpeg){#fig:005 width=70%}

3. Используя встроенную переменную $RANDOM, пишу командный файл,генерирующий случайную последовательность букв латинского алфавита

![Код](image/6.jpeg){#fig:006 width=70%}

![Работа файла](image/7.jpeg){#fig:007 width=70%}

# Выводы

В ходе выполнения работы я приобрела практические навыки программирования в системе Линукс

# Список литературы{.unnumbered}

::: {#refs}
:::

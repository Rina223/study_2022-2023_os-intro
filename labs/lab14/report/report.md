---
## Front matter
title: "Отчет по лабораторной работе №14"
subtitle: "Операционные системы"
author: "Рина Лукина"

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

Приобретение практических навыков работы с именованными каналами.

# Ход работы

1. Создаю рабочее пространство. 

![папка](image/1.jpeg){#fig:001 width=70%}

2. Создаю файл и пишу скрипт.

![common.h](image/2.jpeg){#fig:002 width=70%}

3. Создаю второй файл и пишу новый код.

![server.c](image/3.jpeg){#fig:003 width=70%}

4. Создаю третий файл и пишу код.

![client.c](image/4.jpeg){#fig:004 width=70%}

5. Создаю четвертый файл и пишу код.

![Makefile](image/5.jpeg){#fig:005 width=70%}

6. Запускаю сервер и проверяю работу.

![./server](image/6.jpeg){#fig:006 width=70%}

# Выводы
В ходе выполнения лабораторной работы я научилась работать с именованными каналами.

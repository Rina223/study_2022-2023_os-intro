---
## Front matter
title: "Отчет по лабораторной работе №1"
subtitle: "Операционные системы"
author: "Лукина И.О."

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

Целью работы является приобретение практических навыков установки ОС на виртуальную машину. настройки минимально необходимых для дальнейшей работы сервисов



# Выполнение лабораторной работы

1. Сначала я создаю новую виртуальную машину и задаю для нее оптимальные характеристика

![Имя и путь](image/11.jpg){#fig:001 width=90%}

![Настройки памяти](image/22.jpg){#fig:002 width=90%}

2. После запуска выхожу из машины и излекаю диск для дальнейшей работы:

![Изъятие диска](image/44.jpg){#fig:003 width=90%}

3. Снова запускаю созданную виртуальную машину и начинаю загрузку Fedora:

![Fedora](image/33.jpg){#fig:004 width=90%}

4. Начинаю настройку своих данных, которые должны совпадать с соглашением об именовании (задаю имя пользователя как в своем профиле дислейного класса и создаю пароль):

![Настройка Fedora](image/55.jpg){#fig:005 width=90%}

5. Домашнее задание:

![Команды из домашнего задания ](image/6.jpg){#fig:006 width=90%}

# Контрольные вопросы
1. Имя пользователя и пароль
2. ls, du, mkdir, chmod, history
3. Информация и разрешенном доступе, пароль к файлу, владелец файла, создатель файла, максимальный размер файла, длина ключа, признак блокировки, текущий размер файла
4. Команда mount
5. Команда kill 

# Выводы

В ходе лабораторной работы я смогла установить виртуальную машину на систему и настроить ее.
# Список литературы{.unnumbered}

::: {#refs}
:::

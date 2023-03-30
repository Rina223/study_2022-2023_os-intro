---
## Front matter
title: "Отчет по лабораторной работе №2"
subtitle: "Операционные системы"
author: "Лукина Ирина Олеговна"

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

Научиться офоррмлять отчеты с помощью легковесного языка разметки Markdown.




# Выполнение лабораторной работы

1. Создадим каталог в указанном пути командой mkdir:

![Создание каталога](image/1.png){#fig:001 width=90%}

2.Перейдем в созданный каталог:

![В каталог](image/2.png){#fig:002 width=90%}

3. Создадим новый репозиторий (я делала через GH):

![Репозиторий](image/3.png){#fig:003 width=90%}

4. Скопируем ссылку на репозиторий и клонируем его данные в свой каталог через git clone:

![Ссылка](image/4.png){#fig:004 width=90%}
![Git clone](image/5.png){#fig:005 width=90%}

5. Перейдем в каталог os-intro:

![Каталог](image/6.png){#fig:006 width=90%}

6. Выполним ряд команд для настройки каталога курса:
1) rm - удалим лишние файлы;
2) echo - создадим необходимые каталоги;
3) make.

![Настройка каталога курса](image/7.png){#fig:007 width=90%}

7. Отправим файлы на сервер:

![Команды git](image/8.png){#fig:008 width=90%}

# Выводы
test makepdf

# Список литературы{.unnumbered}

::: {#refs}
:::

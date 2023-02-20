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

Научиться оформлять отчеты с помощью легковесного языка разметки Markdown


# Выполнение лабораторной работы

1. Указываю путь каталога до /labs/lаb№/report и ввожу команду gedit report md, которая откроет новое окно с шаблоном отчета

2. В начале делаю оформление, заменяя слова автора6

![Обложка](image/1.png){#fig:001 width=90%}

3. Изменяю изображения согласно шаблону и вставляю свои:

![Работа с изображениями](image/2.png){#fig:002 width=90%}

4. По окончании работы сохраняю документ и ввожу команду make, которая создаст отчет в разных форматах:

![make](image/3.png){#fig:003 width=90%}
![Результат](image/4.png){#fig:004 width=90%}

5. Те же действия проделываю с созданием презентации:

![Презентация](image/5.png){#fig:005 width=90%} 
![Презентация](image/6.png){#fig:006 width=90%} 

# Выводы

В ходе выполнения работы я научилась работать с Markdown, создавать файлы и презентации по шаблонам. 
# Список литературы{.unnumbered}

::: {#refs}
:::

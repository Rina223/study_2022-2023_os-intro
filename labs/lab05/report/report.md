---
## Front matter
title: "Отчет по лабораторной работе №5"
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

Ознакомление с файловой системой Linux, ее структурой , именами и содержанием каталогов. Приобретение практических навыков по применению команд для работы с файлами и каталогами, по управлению процессами (и работами), по проверке использования диска и обслуживанию файловой системы.


# Выполнение лабораторной работы

1. Выполняю примеры команд согласно ходу выполнения работы.

![Выполнение примеров](image/1.png){#fig:001 width=90%}

2. Копирую файл и даю ему название через команду cp.

![equipment](image/2.png){#fig:002 width=90%}

3. Создаю директорию через mksdir.

![ski.plases/](image/3.png){#fig:003 width=90%}

4. Перемещаю файл в каталог командой mv и проверяю.

![Перемещение](image/5.png){#fig:004 width=90%}

5. Создаю новый файл и копирую его в каталог, одновременно даю новое название.

![abc1](image/6.png){#fig:005 width=90%}

6. Создаю новый каталог в ski.plases/

![equipment](image/7.png){#fig:006 width=90%}

7. Перемещаю файлы.

![Перемещение](image/8.png){#fig:007 width=90%}

8. Создаю каталог newdir и перемещаю, дав новое имя.

![Каталог newdir](image/9.png){#fig:008 width=90%}

9. Создаю новые файлы и определяю опции команды chmod.

![chmod](image/10.png){#fig:009 width=90%}

10. Копирую файл в другой файл.

![Копирование](image/11.png){#fig:010 width=90%}

11. Перемещаю каталог play в fun.

![Перемещение](image/12.png){#fig:011 width=90%}

12. Создаю каталог fun и перемещаю его.

![fun](image/13.png){#fig:012 width=90%}

13. Перемещаю в каталог play и даю название games.

![Перемещение](image/14.png){#fig:013 width=90%}

14. Лишаю владельца файла права на чтение.

![chmod 300](image/15.png){#fig:014 width=90%}

15. Через команду cat пробую проверить feathers.

![cat](image/16.png){#fig:015 width=90%}

16. Пробую скопировать.

![ski.plases/](image/17.png){#fig:016 width=90%}

17. Лишаю права на просмотр каталога play.

![chmod 600](image/18.png){#fig:017 width=90%}

18. Просматриваю разные опции команд через man.

![man mount](image/19.png){#fig:018 width=90%}

![man fsck](image/20.png){#fig:019 width=90%}

![man kill](image/21.png){#fig:020 width=90%}



# Выводы

В ходе выполнения работы я приобрела практические навыки в работе с файловой системой Linux.

# Список литературы{.unnumbered}

::: {#refs}
:::

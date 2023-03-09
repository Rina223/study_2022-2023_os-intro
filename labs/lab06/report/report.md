---
## Front matter
title: "Отчет по лабораторной работе №6"
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

Ознакомление с инструментами поиска файлов и фильтрации текстовых данных. Приобретение практических навыков: пл управлению процессами (и заданиями), по проверке использования диска и обслуживанию файловых систем.
# Выполнение лабораторной работы
1. Вхожу в систему.

2. Записываю в файл названия файлов, содержащихся в домашнем каталоге.

![Запись в файл](image/1.png){#fig:001 width=70%}

3. Вывожу имена всех файлов, имеющих расширение .conf.

![Вывод](image/2.png){#fig:002 width=70%}


4. Несколькими способами определяю какие файлы начинаются с "с".

![Нахождение файлов](image/4.png){#fig:003 width=70%}

5. Через find вывожу имена файлов из каталог, начинающиеся в символа "h".

![Вывод](image/5.png){#fig:004 width=70%}

6. Запускаю в фоновом режиме процесс, который будет записывать в файл файлы, начинающиеся с определенных символов.

![logfile](image/6.png){#fig:005 width=70%}

7. Удаляю файл.

![Удаление](image/8.png){#fig:007 width=70%}

8. Запускаю в фоновом режиме gedit.

![Запуск gedit](image/9.png){#fig:008 width=70%}

9. Определяю индентификатор gedit через ps. 

![ps -a](image/9.png){#fig:009 width=70%}

![top](image/10.png){#fig:010 width=70%}

![ps aux grep](image/11.png){#fig:011 width=70%}

10. Открываю справку по команду kill и завершаю gedit, вписывая номер индентификатора.

![man kill](image/12.png){#fig:012 width=70%}

![kill gedit](image/13.png){#fig:013 width=70%}

11. Выполняю команды df и du. Открываю справку по ним.

![df](image/14.png){#fig:014 width=70%}

![du](image/15.png){#fig:015 width=70%}

![du выполнение](image/16.png){#fig:016 width=70%}

12. С помощью find выводу имена всех директорий из домашнего каталога.

![find](image/17.png){#fig:017 width=70%}
# Выводы

В ходе выполнения лабораторной работы я научилась находить и перенаправлять файлы через консоль.


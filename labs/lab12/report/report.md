---
## Front matter
title: "Лабораторная работа №12"
subtitle: "Программирование в командном процессоре ОС UNIX. Командные файлы"
author: "Комягин Андрей Николаевич"

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

Изучить основы программирования в оболочке ОС UNIX/Linux. Научиться писать небольшие командные файлы.

# Выполнение лабораторной работы

Напишем программу для создания бэкапа (рис. [-@fig:001]).

![код 1](image/1.PNG){#fig:001 width=70%}

Проверим работу программы (рис. [-@fig:002]).

![бэкап](image/2.PNG){#fig:002 width=70%}

Напишем программу для выполнения большого кол-ва программ (рис. [-@fig:003])  

![код 2](image/3.PNG){#fig:003 width=70%}

Проверим работу кода (рис. [-@fig:004]).

![Выполнение команд](image/4.PNG){#fig:004 width=70%}

Напишем аналог команды ls (рис. [-@fig:005]).

![код 3](image/5.PNG){#fig:005 width=70%}

Проверим работу программы (рис. [-@fig:006]).

!["ls ~ "](image/6.PNG){#fig:006 width=70%}

Напишем программу, считающую количество файлов с заданным расширением в заданном каталоге (рис. [-@fig:007]).

![код 4](image/7.PNG){#fig:007 width=70%}

Работа программы №4 (рис. [-@fig:008]).

![Счет файлов с расширением](image/8.PNG){#fig:008 width=70%}

# Вывод

В ходе лабораторной работы я Изучил основы программирования в оболочке ОС UNIX/Linux. Научился писать небольшие командные файлы.

# Список литературы{.unnumbered}

[Туис, курс Архитектура компьютера и операционные системы](https://esystem.rudn.ru/course/view.php?id=5790)

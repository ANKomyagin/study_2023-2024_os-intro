---
## Front matter
title: "Индивидуальный проект"
subtitle: "Этап 2"
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

Добавить к сайту данные о себе.

# Задание

* Разместить фотографию владельца сайта.
* Разместить краткое описание владельца сайта.
* Добавить информацию об интересах.
* Добавить информацию от образовании.
* Сделать пост по прошедшей неделе.
* Добавить пост на тему: управление версиями. Git.

# Выполнение лабораторной работы

На втором этапе индивидуального проекта необходимо работать с md файлами (изменять их содержимое под себя).

Суть работы заключается во внимательном изучении файлов глазами. 

Результат работы:


Биография, аватарка, фамилия имя, место учёбы (рис. [-@fig:001]).

![Шапка профиля](image/1.PNG){#fig:001 width=70%}

Недавние посты (недельный и про гитхаб) (рис. [-@fig:002])

![Недавние посты](image/2.PNG){#fig:002 width=70%}

![Недельный пост](image/3.PNG){#fig:003 width=70%}

![Подпись под постами](image/4.PNG){#fig:004 width=70%}

![Пост про Git](image/5.PNG){#fig:005 width=70%}

Отправка данных на сервер (рис. [-@fig:006])

![Отправка на git](image/6.PNG){#fig:006 width=70%}

# Вывод

В ходе выполнения первого этапа проекта я добавил данные о себе на сайт 



---
## Front matter
title: "Лабораторная работа №4"
subtitle: "Markdown"
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

Получение навыков продвинутой работы с репозиториями git.

# Задание

* Выполнить работу для тестового репозитория.
* Преобразовать рабочий репозиторий в репозиторий с git-flow и conventional commits.



# Выполнение лабораторной работы

Установка gitfloy.(рис. [-@fig:001]).

![Установка gitfloy](image/1.PNG){#fig:001 width=70%}

Установим и откроем pnpm, настроим node.js (рис. [-@fig:002]).

![pnpm](image/2.PNG){#fig:002 width=70%}

Далее создаём репозиторий и клонируем его, создаем там файл, делаем коммит  (рис. [-@fig:003]) 

![Настройка репозитория](image/3.PNG){#fig:003 width=70%}

Отправляем изменения на git (рис. [-@fig:004]).

![git](image/4.PNG){#fig:004 width=70%}

Изменяем параметры пакета, меняем лицензию и сформируем формат коммитов (рис. [-@fig:005]).

![Параметры пакета](image/5.PNG){#fig:005 width=70%}

Добавляем файлы, выполняем коммит cz и затем отправляем (рис. [-@fig:006]).

![Коммит](image/6.PNG){#fig:006 width=70%}

Инициализируем git-flow, с префиксом v (рис. [-@fig:007]).

![git-flow](image/7.PNG){#fig:007 width=70%}

Проводим операцию над веткой, релизом и журналом изменений (рис. [-@fig:008]).

![git-flow](image/8.PNG){#fig:008 width=70%}

Отправим изменения на github

Разработаем новую функциональность. Создадим релиз 1.2.3(рис. [-@fig:009]). 

![Релиз 1.2.3](image/9.PNG){#fig:009 width=70%}

Отправляем данные на git, создадим релиз изменений (рис. [-@fig:010]). 

![Отправка](image/10.PNG){#fig:010 width=70%}

# Выводы

В ходе выполнения лабораторной работы я получил навыки правильной работы с репозиториями git.

# Список литературы{.unnumbered}

[Туис, курс Архитектура компьютера и операционные системы](https://esystem.rudn.ru/course/view.php?id=5790)

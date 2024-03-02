---
## Front matter
title: "Индивидуальный проект"
subtitle: "Этап 1"
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

Размеcтить на Github pages заготовку для персонального сайта.

# Задание

* Установить необходимое программное обеспечение.
* Скачать шаблон темы сайта.
* Разместить его на хостинге git.
* Установить параметр для URLs сайта.
* Разместить заготовку сайта на Github pages.



# Выполнение лабораторной работы

Установим hugo для создания сайта. Перейдем в репозиторий и установим файл (рис. [-@fig:001]).

![Репозиторий hugo](image/1.PNG){#fig:001 width=70%}

Распакуем hugo и переместим в usr/local/bin (рис. [-@fig:002])

![Распаковка](image/2.PNG){#fig:002 width=70%}

Создаем новый репозиторий на github на основе шаблона (рис. [-@fig:003])

![Создание репозитория](image/3.PNG){#fig:003 width=70%}

Загружаем репозиторий себе на компьютер (рис. [-@fig:004])

![Загрузка репозитория](image/4.PNG){#fig:004 width=70%}

Устанавливаем go (через dnf) и запускаем hugo (рис. [-@fig:005])

![Запуск hugo](image/5.PNG){#fig:005 width=70%}

Выполняем команду hugo server (рис. [-@fig:006])

![hugo server](image/6.PNG){#fig:006 width=70%}

И открываем локальный сайт (рис. [-@fig:007])

![Локальный сайт](image/7.PNG){#fig:007 width=70%}

Затем создаём специальный репозиторий (особое наименование) (рис. [-@fig:008])

![Создание репозитория](image/8.PNG){#fig:008 width=70%}

Клонируем созданный репозиторий (рис. [-@fig:009])

![Клонирование](image/9.PNG){#fig:009 width=70%}

Активация репозитория (рис. [-@fig:010])

![Активация](image/10.PNG){#fig:010 width=70%}

Синхронизируем папку public с репозиторием (рис. [-@fig:011])

![Синхронизация](image/11.PNG){#fig:011 width=70%}

Запускаем hugo и добавляем данные в удалённый репозиторий (рис. [-@fig:012])

![Синхронизация](image/12.PNG){#fig:012 width=70%}

Проверяем работу сайта (рис. [-@fig:013])

![Хостинг github`a](image/13.PNG){#fig:013 width=70%}


# Вывод

В ходе выполнения первого этапа проекта я научился работать с git ветками. Ознакомился с конструктором hugo 



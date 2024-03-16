---
## Front matter
title: "Лабораторная работа №5"
subtitle: "Настройка рабочей среды"
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

Настроить менеджер паролей pass, научиться с ним работать

# Выполнение лабораторной работы

Установка pass и gopass.(рис. [-@fig:001]).

![Установка pass и gopass](image/1.PNG){#fig:001 width=70%}

Проверим ключи, инициализируем хранилище и синхронизируем с git. (рис. [-@fig:002]).

![инициализация хранилища](image/2.PNG){#fig:002 width=70%}

Далее создаём репозиторий синхронизируемся с ним (рис. [-@fig:003]), (рис. [-@fig:004]). 

![адрес репозитория](image/3.PNG){#fig:003 width=70%}

![синхронизация](image/4.PNG){#fig:004 width=70%}

Установим browserpass (рис. [-@fig:005]).

![browserpass](image/5.PNG){#fig:005 width=70%}

Установим плагин для браузера (рис. [-@fig:006]).

![плагин](image/6.PNG){#fig:006 width=70%}

Добавим пароль, выведем пароль и заменим пароль на сгенерированный (рис. [-@fig:007]).

![Работа с паролями](image/7.PNG){#fig:007 width=70%}

Установим дополнительное ПО и шрифты (рис. [-@fig:008]).

![Доп ПО](image/8.PNG){#fig:008 width=70%}

Установим бинарный файл с wget и создадим репозиторий для конфигурационных файлов на основе шаблона(рис. [-@fig:009]). 

![Создание репозитория](image/9.PNG){#fig:009 width=70%}

Инициализируем chezmoi и репозиторий dotfiles (рис. [-@fig:010]). 

![инициализация](image/10.PNG){#fig:010 width=70%}

Подключим chezmoi на другой машине. Проверим изменения, ничего менять не будем (рис. [-@fig:011]). 

![другая машина](image/11.PNG){#fig:011 width=70%}

Также ознакомимся с ежедневными операциями с chezmoi, добавим возможность автоматически фиксировать изменения в репозитории (рис. [-@fig:012]). 

![синхронизация](image/12.PNG){#fig:012 width=70%}

# Выводы

В ходе выполнения лабораторной работы я получил навыки работы с менеджером паролей pass.

# Список литературы{.unnumbered}

[Туис, курс Архитектура компьютера и операционные системы](https://esystem.rudn.ru/course/view.php?id=5790)

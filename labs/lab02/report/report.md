---
## Front matter
title: "Лабораторная работа №2"
subtitle: "Первоначальная настройка git"
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

# Цель работыЙ

Изучить концепцию и применение средств контроля версий. Приобрести навыки работы с git.

# Задание

* Создать базовую конфигурацию для работы с git
* Создать ключ SSH
* Создать ключ PGP
* Настроить подписи git
* Зарегистрироваться на Github
* Создать локальный каталог для выполнения заданий по предмету



# Выполнение лабораторной работы

Установим необходимое ПО.(рис. [-@fig:001]).

![Установка ПО](image/1.PNG){#fig:001 width=70%}

Настроим git. Зададим имя и почту владельца репозитория, настроим utf-8, зададим имя начальной ветки и настроим параметры отступов рис. (рис. [-@fig:002]).

![Первичная настройка git](image/2.PNG){#fig:002 width=70%}

Далее создадим ssh ключи по двум разным алгоритмам - rsa(4096)(рис. [-@fig:003]) и ed25519(рис. [-@fig:004]).

![алгоритм rsa](image/3.PNG){#fig:003 width=70%}

![алгоритм ed25519](image/4.PNG){#fig:004 width=70%}

Также создадим ключ gpg с необходимыми опциями (рис. [-@fig:005]).

![ключ gpg](image/5.PNG){#fig:005 width=70%}

Далее нееобходимо создать учётную запись на Github. Я пропускаю данный этап, так как Github имеется с первого семестра. 
Выведем список ключей и скопируем отпечаток приватного ключа. Затем ключ в буфер обмена (рис. [-@fig:006]) 

![Копирование pgp ключа](image/6.PNG){#fig:006 width=70%}

Добавим скопированный ключ на Github (рис. [-@fig:007]) 

![Добавление ключа на Github](image/7.PNG){#fig:007 width=70%}

Настроим автоматические подписи коммитов git (рис. [-@fig:008])

![Настройка подписей](image/8.PNG){#fig:008 width=70%}

Затем настроим gh и авторизуемся (рис. [-@fig:009])

![gh авторизация](image/9.PNG){#fig:009 width=70%}

Создадим репозиторий курса на основе шаблона (рис. [-@fig:010])

![создание репозитория](image/10.PNG){#fig:010 width=70%}

Настроим каталог курса, а затем отправим его на Github (рис. [-@fig:011])

![Настройка каталога](image/11.PNG){#fig:011 width=70%}

# Выводы

В ходе выполнения лабораторной работы я повторил правила работы с git, узнал о системе подписей и pgp ключах.

# Список литературы{.unnumbered}

[Туис, курс Архитектура компьютера и операционные системы](https://esystem.rudn.ru/course/view.php?id=5790)

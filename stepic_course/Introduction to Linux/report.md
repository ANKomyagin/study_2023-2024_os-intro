---
## Front matter
title: "Прохождение внешнего курса"
subtitle: "Введение в Linux"
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

# Цель прохождения курса

Узнать общую информацию о Linux, установить на виртуальную машину, освоить основы Linux. Познакомиться с запуском исполняемых файлов, направлением ввода и вывода, скачиванием файлов. Научиться работать с архивами и искать слова и файлы.

# Выполнение заданий курса

## Общая информация о курсе

Вступительный вопрос, не требующий пояснения(рис. [-@fig:001]).

![Вопрос №1](image/1.PNG){#fig:001 width=70%}

Вступительный вопрос, не требующий пояснения(рис. [-@fig:002]).

![Вопрос №2](image/2.PNG){#fig:002 width=70%}

Вопрос личного характера(рис. [-@fig:003]).

![Вопрос №3](image/3.PNG){#fig:003 width=70%}

Даже если не знать ответа на вопрос, работает простой метод исключения. Остальные варианты ответа абсурдны(рис. [-@fig:004]).

![Вопрос №4](image/4.PNG){#fig:004 width=70%}

Linux установлен ещё с первого семестра(рис. [-@fig:005]).

![Вопрос №5](image/5.PNG){#fig:005 width=70%}

Просто создаем файл и сохраняем в необходимом формате. Пришлось использовать шрифт Arial, потому что с запрашиваемым шрифтом и требуемым форматом вышли разногласия(рис. [-@fig:006]).

![Вопрос №6](image/6.PNG){#fig:006 width=70%}

Формат .deb был в видеоролике на установке skype(рис. [-@fig:007]).

![Вопрос №7](image/7.PNG){#fig:007 width=70%}

Скачиваем плеер и смотрим автора(рис. [-@fig:008]).

![Вопрос №8](image/8.PNG){#fig:008 width=70%}

Приложение необходимо для обновления приложений, ОС и ссылок(рис. [-@fig:009]).

![Вопрос №9](image/9.PNG){#fig:009 width=70%}

Регистр команды важен(рис. [-@fig:010]).

![Вопрос №10](image/10.PNG){#fig:010 width=70%}

Регистр ключа имеет различительный смысл, порядок ключей обычно не важен. Ключи могут иметь длинные имена(рис. [-@fig:011]).

![Вопрос №11](image/11.PNG){#fig:011 width=70%}

Все записи являются равносильными, чтобы понять, достаточно знать значения символов(рис. [-@fig:012]).

![Вопрос №12](image/12.PNG){#fig:012 width=70%}

Удаление директорий должно происходить рекурсивно, поэтому нужна опция -r. mkdir создает директории(рис. [-@fig:013]).

![Вопрос №13](image/13.PNG){#fig:013 width=70%}

Пока firefox запущен из консоли, команды в терминале не выполняются(рис. [-@fig:014]).

![Вопрос №14](image/14.PNG){#fig:014 width=70%}

Запуск команды с &, это запуск в фоновом режиме(рис. [-@fig:015]).

![Вопрос №15](image/15.PNG){#fig:015 width=70%}

Устанавливаем предложенный файл. Меняем право доступа на исполнение с помощью команды chmod. Запускаем(рис. [-@fig:016]).

![Вопрос №16](image/16.PNG){#fig:016 width=70%}

По умолчанию очень много всего выводится в терминал. Не только ошибки(рис. [-@fig:017]).

![Вопрос №17](image/17.PNG){#fig:017 width=70%}

Стрелочка должна быть направлена на file.txt для записи в файл. Чтобы записывать ошибки, перед стрелочкой(стрелочками) необходимо добавить цифру 2. Кол-во стрелок в данном случае не имеет значения, так как файл пуст(рис. [-@fig:018]).

![Вопрос №18](image/18.PNG){#fig:018 width=70%}

Выводятся на экран, так как им некуда деться(рис. [-@fig:019]).

![Вопрос №19](image/19.PNG){#fig:019 width=70%}

Противоречивое использование опций. В итоге происходит откат на директорию выше и файл получает название 1.jpg(рис. [-@fig:020]).

![Вопрос №20](image/20.PNG){#fig:020 width=70%}

**Смотреть документацию man** или догадаться по названию(рис. [-@fig:021]).

![Вопрос №21](image/21.PNG){#fig:021 width=70%}

С опцией -А происходит установка по названию (в данном случае все файлы с расширением .jpg) **и** html файлы. Затем html файлы удаляются(рис. [-@fig:022]).

![Вопрос №22](image/22.PNG){#fig:022 width=70%}

Информация об этом в прямом виде дана в видеоролике(рис. [-@fig:023]).

![Вопрос №23](image/23.PNG){#fig:023 width=70%}

gzip для создания сжатого архива необходим несжатый архив, который можно получить с помощью tar(рис. [-@fig:024]).

![Вопрос №24](image/24.PNG){#fig:024 width=70%}

f - базовая опция для работы с файлами. с - для запаковки. j - для формата **.bz2**(рис. [-@fig:025]).

![Вопрос №25](image/25.PNG){#fig:025 width=70%}

find без опций учитывает регистр. "?" заменяет один символ, а "*" сколько угодно(рис. [-@fig:026]).

![Вопрос №26](image/26.PNG){#fig:026 width=70%}

grep ищет вход подстроки с учетом регистра. Решил практическим путём (переписал текст в блокнот и применил команду)(рис. [-@fig:027]).

![Вопрос №27](image/27.PNG){#fig:027 width=70%}

Качаем архив. Ищем с помощью команды grep с опцией рекурсивного поиска. Направляем данные в файл с помощью стрелочки(рис. [-@fig:028]).

![Вопрос №28](image/28.PNG){#fig:028 width=70%}

# Вывод

В ходе прохождения курса я отточил свои навыки пользования операционной системой Linux



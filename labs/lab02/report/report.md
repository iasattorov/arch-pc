---
## Front matter
title: "Отчёт по лабораторной работе 2"
subtitle: "Архитектура компьютеров и операционные системы"
author: "Сатторов Икромджон Абдувохидович"

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

Нужно изучить идеологию и научиться применять средства контроля версий, получить практические навыки работы с системой git.
  
# Ход работы

Для начала работы с GitHub необходимо было зарегистрироваться.

Затем я нашел на GitHub шаблонный репозиторий и создал свой собственный.

Пока мой репозиторий содержит не законченную структуру папок.

![Созданный репозиторий](image/01.png){ #fig:001 width=70%, height=70% }

Настраиваю пользователя.

![Настраиваю пользователя.](image/02.png){ #fig:002 width=70%, height=70% }

Для дальнейшей работы мне потребовалось сгенерировать ключ идентификации.

![Генерирую SSH ключ](image/03.png){ #fig:003 width=70%, height=70% }

Затем я добавил свой ключ на GitHub.

![Импорт ключа](image/04.png){ #fig:004 width=70%, height=70% }

![Импорт ключа](image/05.png){ #fig:005 width=70%, height=70% }

После этого я создал рабочий каталог.

![Клонирование репозитория](image/06.png){ #fig:006 width=70%, height=70% }

Клонировал репозиторий, выполнил make, чтобы создать структуру папок.
И загрузил это в сетевой репозиторий

![Загрузка в репозиторий](image/07.png){ #fig:007 width=70%, height=70% }

![Файлы и папки в репозитории](image/08.png){ #fig:008 width=70%, height=70% }

# Выводы

Я получил навыки по работе с системой контроля версий GitHub.
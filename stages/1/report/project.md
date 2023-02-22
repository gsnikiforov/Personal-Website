---
## Front matter
title: "Отчёт по выполнению индивидуального проекта"
subtitle: "Этап 1"
author: "Мулин Иван Владимирович"

## Generic otions
lang: ru-RU
toc-title: "Содержание"

## Bibliography
## bibliography: bib/cite.bib
csl: pandoc/csl/gost-r-7-0-5-2008-numeric.csl

## Pdf output format
toc: true # Table of contents
toc-depth: 2
lof: true # List of figures
lot: false # List of tables
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

## Цель работы
Цель настоящей работы - настроить структуру индивидуального сайта для дальнейшей работы. Репозитории проекта размещён по адресам [https://github.com/ivmulin/Personal-Website](https://github.com/ivmulin/Personal-Website) и [https://github.com/ivmulin/ivmulin.github.io](https://github.com/ivmulin/ivmulin.github.io).

# Выполнение этапа 1

Создали репозиторий:

![Создание репозитория](image/Рис.%201.png "Создание репозитория")

Затем создали сопутствуюший репозиторий, на котором будет в дальнейшем храниться всё содержимое сайта.

![Создание вспомогательного репозитория](image/Рис.%202.png "Создание вспомогательного репозитория")

При помощи команды `git submodule add -b main git@github.com:ivmulin/ivmulin.github.io.git public` установили соединение между папкой `public` первого репозитория и вторым репозиторием.

Запустили сайт. Всё работает:

![Проверка работы сайта](image/Рис.%203.png "Проверка работы сайта")

# Заключение
Цель работы была достигнута: в результате выполнения данной работы была настроена структура сайта индивидуального проекта.
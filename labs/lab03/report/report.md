---
## Front matter
title: "Лабораторная работа №3 "
subtitle: "Простейший вариант"
author: "Манукян Захар"

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
mainfont: IBM Plex Serif
romanfont: IBM Plex Serif
sansfont: IBM Plex Sans
monofont: IBM Plex Mono
mathfont: STIX Two Math
mainfontoptions: Ligatures=Common,Ligatures=TeX,Scale=0.94
romanfontoptions: Ligatures=Common,Ligatures=TeX,Scale=0.94
sansfontoptions: Ligatures=Common,Ligatures=TeX,Scale=MatchLowercase,Scale=0.94
monofontoptions: Scale=MatchLowercase,Scale=0.94,FakeStretch=0.9
mathfontoptions:
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

Целью работы является освоение процедуры оформления отчетов с помощью легковесного языка разметки Markdown. 



# Выполнение лабораторной работы

 Открываю терминал. Перешёл в каталог курса сформированный при выполнении лаборатор- ной работы No2 как на рисунке и обновил локальный репозиторий, скачав изменения из удаленного репозитория с помощью команды git pull (рис. [-@fig:001]).

![рис 1](image/рис1.png){#fig:001 width=70%}

Перехожу в каталог с шаблоном отчета по лабараторной работе No3 

![рис 2](image/рис2.png){#fig:002 width=70%}

Провожу компиляцию шаблона с использованием Makefile. Для этого ввожу команду make 

![рис 3](image/рис3.png){#fig:003 width=70%}

Проверяю успешную компиляцию файлов report.docx и report.pdf

![рис 4](image/рис4.png){#fig:004 width=70%}

Удаляю полученный файл с использованием Makefile. Для этого ввожу команду make clean.

![рис 5](image/рис5.png){#fig:005 width=70%}

Проверяем коректное удаление файлов report.pdf и report.docx.

![рис 6](image/рис6.png){#fig:006 width=70%}

Открываю файл report.md через терминал.

![рис 7](image/рис7.png){#fig:007 width=70%}

Загружаю файлы на Github. 

















# Выводы

При выполнении лабораторной работы я освоил процедуры оформления отчета с помощью легковесного языка разметки Markdown. 



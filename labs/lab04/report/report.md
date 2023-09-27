---
## Front matter
title: "Лабораторная работа №4"
subtitle: "Язык разметки Markdown"
author: "Коц Данила Богданович"

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

Освоение процедуры оформления отчетов с помощью легковесного языка разметки Markdown.

# Задание

Освоить процедуры оформления отчетов с помощью легковесного языка разметки Markdown.

# Теоретическое введение



# Выполнение лабораторной работы

1. Я перешёл в каталог курса сформированный при выполнении лабораторной работы №3.

![Переход в каталог курса](image/001.png){ #fig:001 width=70% }

2. Я обновил локальный репозиторий, скачав изменения из удаленного репозитория с помощью команды git pull.

![Обновление локального репозитория.](image/002.png){ #fig:002 width=70% }

3. Я перешёл в каталог с шаблоном отчета по лабораторной работе №4.

![Переход в каталог.](image/003.png){ #fig:003 width=70% }

4. Я провёл компиляцию шаблона с использованием Makefile с помощью команды make.

![Компиляция шаблона.](image/004.png){ #fig:004 width=70% }

5. Я удалил полученный файлы с использованием Makefile с помощью команды make clean и проверил, что после этой команды файлы report.pdf и report.docx были удалены. 

![Удаление файлов и проверка.](image/005.png){ #fig:005 width=70% }

# Выводы

Я освоил процедуры оформления отчетов с помощью легковесного языка разметки Markdown.

# Список литературы{.unnumbered}

::: {#refs}
:::

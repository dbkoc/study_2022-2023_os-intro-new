---
## Front matter
title: "Лабораторная работа №11"
subtitle: "Работа с файлами средствами Nasm"
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

Приобретение навыков написания программ для работы с файлами.

# Выполнение лабораторной работы

1. Я создал каталог lab11 и в нём создаём файл lab11.asm.

![Создание файла](image/1.png){ #fig:001 width=70% }

2. Я ввёл в файл lab11-1.asm текст программы из листинга 11.1, создал исполняемый файл и проверил его работу.

![Текст програмы](image/2.png){ #fig:002 width=70% }
![Проверка работы файла](image/3.png){ #fig:003 width=70% }

3. С помощью команды chmod я изменил права доступа к исполняемому файлу lab11-1, запретив его выполнение.

![Изменение прав доступа](image/4.png){ #fig:004 width=70% }

4. Я предоставил права доступа к файлу readme.txt в соответствии с вариантом в таблице 11.4 и проверил правильность выполнения с помощью команды ls -l.

![Предоставление прав доступа и проверка работы](image/5.png){ #fig:005 width=70% }

# Самостоятельная работа.

1. Я написал программу, которая запрашивает имя и выводит его в созданном файле. Файл создает сама программа.

![Текст программы](image/6.png){ #fig:006 width=70% }

![Проверка работы программы](image/7.png){ #fig:007 width=70% }
![Проверка работы программы](image/8.png){ #fig:008 width=70% }

# Вывод{.unnumbered}

Я приобрел навыки написания программ для работы с файлами.

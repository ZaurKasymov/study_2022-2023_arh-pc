---
## Front matter
title: "Шаблон отчёта по лабораторной работе №4"
subtitle: "НКАбд-04-22"
author: "Касымов Заур Фазикович"

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

Освоение процедуры оформления отчетов с помощью Markdown.


# Задание

1. В соответствующем каталоге сделайте отчёт по лабораторной работе №4
в формате Markdown.
3. В соответствующем каталоге сделайте отчёт по лабораторной работе №4
в формате Markdown. 
2. Загрузите файлы на github.


# Выполнение лабораторной работы

## Установка TeX Live 

Устанавливаем TeX Live с официального сайта https://www.tug.org/texlive(рис. [-@fig:001])

![Архив TeX Live и распаковка файла](image/1.png){ #fig:001 width=70% }


## Установка Pandoc и pandoc-crossref

Скачаем архивы с исходными файлами pandoc (https://github.com/jgm/pandoc/releases:).
(рис. [-@fig:002])

![Скачивание архива pandoc](image/2.png){ #fig:002 width=70% }

Скачаем архив pandoc-crossref (https://github.com/lierdakil/pandoccrossref/releases:).
(рис. [-@fig:003])

![Скачивание архива pandoc-crossref](image/3.png){ #fig:003 width=70% }

Распаковали архивы. рис. ([-@fig:004])

![Распаковка архивов](image/4.png){ #fig:004 width=70% }

Скопировуем файлы pandoc и pandoc-crossref в каталог /usr/local/bin/.
 (рис. [-@fig:005])

![Копирование файлов pandoc и pandoc-crossref и проверка корректности выполненных действий](image/5.png){ #fig:005 width=70% }

## Оформление отчёта в формате Markdown

Откроем терминал и перейдем в каталог курса и обновим его. (рис. [-@fig:006])

![Каталог курса](image/6.png){ #fig:006 width=70% }


Перейдем в каталог с шаблоном отчета по лабораторной работе № 4. (рис. [-@fig:007])

![Каталог с шаблоном отчёта](image/7.png){ #fig:007 width=70% }

Проверим компиляцию шаблона с использованием Makefile. Для этого введем команду make.
Откроем и проверим корректность полученных файлов. (рис. [-@fig:008])

![Файлы report.pdf и report.docx](image/8.png){ #fig:008 width=70% }

Удалим полученные файлы с использованием Makefile. Для этого ввели команду make clean.

![Удаление файлов report.pdf и report.docx](image/9.png){ #fig:009 width=70% }

Откроем файл report.md c помощью текстового редактора gedit. (рис. [-@fig:010])

![Файл report.md](image/10.png){ #fig:010 width=70% }

Заполнили отчет и скомпилировали отчет с использованием Makefile. (рис. [-@fig:011])

![Заполненный отчет](image/11.png){ #fig:011 width=70% }

Загрузили файлы на Github. (рис. [-@fig:020])

![Загрузка файлы на Github](image/20.png){ #fig:020 width=70% }

## Задание для самостоятельной работы

1. В соответствующем каталоге сделайли отчёт по лабораторной работе № 3
в формате Markdown. В качестве отчёта предоставили отчёты
в 3х форматах: pdf, docx и md. (рис. [-@fig:021]), (рис. [-@fig:022])

![Лабораторная работа № 3 в формате Markdown](image/21.png){ #fig:021 width=70% }

![Отчёты в 3х форматах: pdf, docx и md](image/22.png){ #fig:022 width=70% }

2. Загрузили файлы на Github. (рис. [-@fig:023])

![Загрузка файлов на Github](image/23.png){ #fig:023 width=70% }

# Выводы

В ходе лабораторной работы были освоены процедуры оформления отчетов с помощью
легковесного языка разметки Markdown.



# Выводы

Здесь кратко описываются итоги проделанной работы.

# Список литературы{.unnumbered}

::: {#refs}
:::

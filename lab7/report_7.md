---
## Front matter
title: "Отчет по лабораторной работе №7"
subtitle: "Лабораторная работа №7: Элементы криптографии. Однократное гаммирование."
author: "Голова Варвара Алексеевна, НФИбд-03-18"
group: "НФИбд-03-18"
ID: "1032182507"
date: 2021, 11 December


## Formatting
toc-title: "Содержание"
toc: true # Table of contents
toc_depth: 2
lof: true # List of figures
fontsize: 12pt
linestretch: 1.5
papersize: a4paper
documentclass: scrreprt
polyglossia-lang: russian
polyglossia-otherlangs: english
mainfont: PT Serif
romanfont: PT Serif
sansfont: PT Sans
monofont: PT Mono
mainfontoptions: Ligatures=TeX
romanfontoptions: Ligatures=TeX
sansfontoptions: Ligatures=TeX,Scale=MatchLowercase
monofontoptions: Scale=MatchLowercase
indent: true
pdf-engine: lualatex
header-includes:
  - \linepenalty=10 # the penalty added to the badness of each line within a paragraph (no associated penalty node) Increasing the value makes tex try to have fewer lines in the paragraph.
  - \interlinepenalty=0 # value of the penalty (node) added after each line of a paragraph.
  - \hyphenpenalty=50 # the penalty for line breaking at an automatically inserted hyphen
  - \exhyphenpenalty=50 # the penalty for line breaking at an explicit hyphen
  - \binoppenalty=700 # the penalty for breaking a line at a binary operator
  - \relpenalty=500 # the penalty for breaking a line at a relation
  - \clubpenalty=150 # extra penalty for breaking after first line of a paragraph
  - \widowpenalty=150 # extra penalty for breaking before last line of a paragraph
  - \displaywidowpenalty=50 # extra penalty for breaking before last line before a display math
  - \brokenpenalty=100 # extra penalty for page breaking after a hyphenated line
  - \predisplaypenalty=10000 # penalty for breaking before a display
  - \postdisplaypenalty=0 # penalty for breaking after a display
  - \floatingpenalty = 20000 # penalty for splitting an insertion (can only be split footnote in standard LaTeX)
  - \raggedbottom # or \flushbottom
  - \usepackage{float} # keep figures where there are in the text
  - \floatplacement{figure}{H} # keep figures where there are in the text

---

# Цель работы

Освоить на практике применение режима однократного гаммирования.

# Выполнение работы

## Алфавит

Задала алфавит из русских букв и алфавит из соответствующих им шестнадцетиричных чисел.

![Алфавиты](images/lab7_1.png){ #fig:001 width=70% }

## Сообщение

Ввела сообщение.

![Сообщение](images/lab7_2.png){ #fig:002 width=70% }

## Ключ

Создала рандомный ключ.

![Создание ключа](images/lab7_3.png){ #fig:003 width=70% }

## Перевод сообщения

Перевела заданное сообщение в шестнадцетиричные числа.

![Шестнадцетиричная система](images/lab7_4.png){ #fig:004 width=70% }

## Шифрование

Определила вид шифротекста при известном ключе и известном открытом тексте.

![Шифрование](images/lab7_5.png){ #fig:005 width=70% }

## Расшифровка

Один из вариантов расшифровки полученного шифра.

![Расшифровка](images/lab7_6.png){ #fig:006 width=70% }

## Перевод сообщения

Перевела один из возможных вариантов расшифровки сообщения в шестнадцетиричные числа.

![Шестнадцетиричная система](images/lab7_7.png){ #fig:007 width=70% }

## Ключ

Определила ключ, с помощью которого шифротекст может быть преобразован в некоторый фрагмент текста, представляющий собой один из возможных вариантов прочтения открытого текста.

![Возможный ключ](images/lab7_8.png){ #fig:008 width=70% }

# Выводы

Я освоила на практике применение режима однократного гаммирования.

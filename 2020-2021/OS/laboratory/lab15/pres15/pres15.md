---
## Front matter
lang: ru-RU
title: Лабораторная работа №15
author: |
	Филиппова Анна Дмитриевна inst{1}
institute: |
	\inst{1}RUDN University, Moscow, Russian Federation
date: 8 июня, 2021, Москва, Россия

## Formatting
toc: false
slide_level: 2
theme: metropolis
header-includes: 
 - \metroset{progressbar=frametitle,sectionpage=progressbar,numbering=fraction}
 - '\makeatletter'
 - '\beamer@ignorenonframefalse'
 - '\makeatother'
aspectratio: 43
section-titles: true
---

## Цель работы

 Приобретение практических навыков работы с именованными каналами.

## Выполнение лабораторной работы

1. Создаем необходимые файлы с помощью команды «touch common.h server.c client.c Makefile» и открываем редактор emacs для их редактирования. (рис. -@fig:001) 

![Создаем файлы](image15/1.png){ #fig:001 width=70% }

## Выполнение лабораторной работы

2.  Изменяем коды программ common.h, server.c, client.c, представленных в тексте лабораторной работы. (рис. -@fig:002) 

![common.h](image15/2.png){ #fig:002 width=70% }

## Выполнение лабораторной работы

3. Makefile (файл для сборки) не изменяем. (рис. -@fig:003)

![Makefile](image15/15.png){ #fig:003 width=70% }

## Выполнение лабораторной работы

4.  После написания кодов, используем команду «make all» компилируем необходимые файлы. (рис. -@fig:004)

![Компилируем файлы](image15/10.png){ #fig:004 width=70% }

## Выполнение лабораторной работы

5. Далее проверяем работу написанного кода. (рис. -@fig:005)

![Проверка работы кода](image15/11.png){ #fig:005 width=70% }

## Вывод

 Я приобрела практические навыки работы с именованными каналами.

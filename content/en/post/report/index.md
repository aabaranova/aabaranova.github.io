---
title: Оформление отчёта
date: 2025-04-30

# Featured image
# Place an image named `featured.jpg/png` in this page's folder and customize its options here.
image:
  caption: 'Image credit: [**epir**](https://epirhandbook.com/ru/new_pages/rmarkdown.ru.html)'

authors:
  - admin
  - epirhandbook

tags:
 - Markdown
 - Отчёт
---

Welcome

## What is that?

- Markdown — удобочитаемый язык разметки, который прозрачно конвертируется в HTML. Его можно открывать и изменять в любом редакторе текста. Широко используется для написания документаций и README-файлов.

- R Markdown - широко используемый инструмент для создания автоматизированных, воспроизводимых выходных данных, которыми можно делиться, таких как отчеты. Он генерирует статические или интерактивные выходные данные в Word, pdf, html, powerpoint и других форматах.

- Скрипт R Markdown сочетает код R и текст таким образом, что скрипт становится вашим выходным документом. Вы можете создать полный отформатированный документ, включая описательную часть (может быть динамичной и меняться на основе ваших данных), таблицы, рисунки, маркированные списки, список использованной литературы и т.п.

- Такие документы могут создаваться для регулярного предоставления обновленной информации (например, ежедневные отчеты по эпиднадзору) и/или могут выполняться для подмножества данных (например, отчеты для каждой юрисдикции).

## Установка

Чтобы создать выходной продукт в R Markdown, вам нужно установить следующее:

* Пакет rmarkdown (knitr также установится автоматически)

* Pandoc

* Если вы хотите сгенерировать выходной продукт в формате PDF, вам нужно будет установить LaTeX.

## Структура файла

Существует несколько способов структурировать ваш R Markdown и связанные с ним скрипты R. У каждого есть свои преимущества и недостатки:

* Автономный R Markdown - все, что нужно для отчета, импортируется или создается внутри R Markdown

* Получение данных из других файлов - Вы можете выполнить внешние скрипты R с помощью команды source() и использовать их выходные результаты в Rmd

* Дочерние скрипты - альтернативный механизм для source()

* Использовать “файл выполнения” - Выполнять команды в скрипте R до построения R

## Дальше

А дальше вы редактируете файл формта markdown и потом с помощью команды "make" в терминале создаёте его производные.
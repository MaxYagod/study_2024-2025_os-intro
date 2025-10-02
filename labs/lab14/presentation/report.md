---
# Preamble

## Author
author:
  name: Ягодин Максим Сергеевич
  degrees: DSc
  orcid: 0000-0002-0877-7063
  email: 
  affiliation:
    - name: Российский университет дружбы народов
      country: Российская Федерация
      postal-code: 117198
      city: Москва
      address: ул. Миклухо-Маклая, д. 6
## Title
title: "Выполнение лабораторной работы "
subtitle: "Ягодин Максим Сергеевич "
license: "CC BY"
## Generic options
lang: ru-RU
number-sections: true
toc: true
toc-title: "Содержание"
toc-depth: 2
## Crossref customization
crossref:
  lof-title: "Список иллюстраций"
  lot-title: "Список таблиц"
  lol-title: "Листинги"
## Bibliography
bibliography:
  - bib/cite.bib
csl: _resources/csl/gost-r-7-0-5-2008-numeric.csl
format:
## Pdf output format
  pdf:
    toc: true
    number-sections: true
    colorlinks: false
    toc-depth: 2
    lof: true # List of figures
    lot: true # List of tables
### Document
    documentclass: scrreprt
    papersize: a4
    fontsize: 12pt
    linestretch: 1.5
### Language
    babel-lang: russian
    babel-otherlangs: english
### Biblatex
    cite-method: biblatex
    biblio-style: gost-numeric
    biblatexoptions:
      - backend=biber
      - langhook=extras
      - autolang=other*
### Misc options
    csquotes: true
    indent: true
    header-includes: |
      \usepackage{indentfirst}
      \usepackage{float}
      \floatplacement{figure}{H}
      \usepackage[math,RM={Scale=0.94},SS={Scale=0.94},SScon={Scale=0.94},TT={Scale=MatchLowercase,FakeStretch=0.9},DefaultFeatures={Ligatures=Common}]{plex-otf}
## Docx output format
  docx:
    toc: true
    number-sections: true
    toc-depth: 2
---

# Цель работы

С помощью Markdown выполнить  отчеты к лабораторным работам.

# Задание

Создать при помощи md текстовый файлы формата docx, pdf


# Выполнение лабораторной работы

Для начала мы переходим в необходимый каталог, устанавливаем gedit и далее заходим в файл:

![Рис.1: Переходим](1.jpg){#fig-001 width=70%}

После того как мы перешли в нужный нам файл, начинаем его редактировать

![Рис.2: Заполняем](2.jpg){#fig-001 width=70%}

Сохраняем и пишем следующую программу что превратить файл из фомата md  в формат docx

![Рис.3: создаём файл формата docx](3.jpg){#fig-001 width=70%}

И создаём файл формата pdf


![Рис.4: создаём файл формата pdf](6.jpg){#fig-001 width=70%}

Проверяем наш результат

![Рис.5: Проверяем наш результат](5.jpg){#fig-001 width=70%}





# Выводы

Мы научились работать с текстовым редактором Markdown, выполнять с помощью него отчеты к лабораторным работ

# Список литературы{.unnumbered}

::: {#refs}
:::

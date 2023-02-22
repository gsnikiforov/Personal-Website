---
## Front matter
lang: ru-RU
title: Индивидуалный проект
subtitle: Этап 1
author:
  - Мулин И.
institute:
  - Российский университет дружбы народов, Москва, Россия
date: 22 февраля 2023

## i18n babel
babel-lang: russian
babel-otherlangs: english

## Formatting pdf
toc: false
toc-title: Содержание
slide_level: 2
aspectratio: 169
section-titles: true
theme: metropolis
header-includes:
 - \metroset{progressbar=frametitle,sectionpage=progressbar,numbering=fraction}
 - '\makeatletter'
 - '\beamer@ignorenonframefalse'
 - '\makeatother'
---

# Информация

## Докладчик

:::::::::::::: {.columns align=center}
::: {.column width="70%"}

  * Мулин Иван Владимирович
  * студент-первокурсник
  * всё ещё по-прежнему студент
  * Математический институт им. Никольского
  * <https://github.com/ivmulin>

:::
::::::::::::::

# Вводная часть

## Цели и задачи

Цель сей работы - настроить структуру индивидуального сайта для дальнейшей работы.

# Ход работы

## Создание основного репозитория

Создали репозиторий:

![](image/Рис.%201.png "")

## Создание вспомогательного репозитория

Создали сопутствуюший репозиторий, на котором будет в дальнейшем храниться всё содержимое сайта.

![](image/Рис.%202.png "")

## Настройка сайта

При помощи команды `git submodule add -b main git@github.com:ivmulin/ivmulin.github.io.git public` установили соединение между папкой `public` первого репозитория и вторым репозиторием и после оставшихся настроек проверили работу индивидуального сайта: он существует.

# Результаты

## Заключение

- Цель работы была достигнута: в результате выполнения данной работы была настроена структура сайта индивидуального проекта. Сайт активен.

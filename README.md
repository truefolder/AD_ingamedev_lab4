# Анализ данных в разработке игр
Отчет по лабораторной работе #4 выполнил(а):
- Бабаев Тимур Ахмадалиевич
- РИ-220912
Отметка о выполнении заданий (заполняется студентом):

| Задание | Выполнение | Баллы |
| ------ | ------ | ------ |
| Задание 1 | * | - |
| Задание 2 | * | - |
| Задание 3 | * | - |

знак "*" - задание выполнено; знак "#" - задание не выполнено;

Работу проверили:
-

[![N|Solid](https://cldup.com/dTxpPi9lDf.thumb.png)](https://nodesource.com/products/nsolid)

[![Build Status](https://travis-ci.org/joemccann/dillinger.svg?branch=master)](https://travis-ci.org/joemccann/dillinger)

Структура отчета

- Данные о работе: название работы, фио, группа, выполненные задания.
- Цель работы.
- Задание 1.
- Код реализации выполнения задания. Визуализация результатов выполнения (если применимо).
- Задание 2.
- Код реализации выполнения задания. Визуализация результатов выполнения (если применимо).
- Задание 3.
- Код реализации выполнения задания. Визуализация результатов выполнения (если применимо).
- Выводы.
- ✨Magic ✨

## Цель работы


## Задание 1
### В проекте Unity реализовать перцептрон, который умеет производить вычисления:
#### OR | дать комментарии о корректности работы
#### AND | дать комментарии о корректности работы
#### NAND | дать комментарии о корректности работы
#### XOR | дать комментарии о корректности работы
OR. Для наглядности немного видоизменил вывод в консоль, убрав вывод весов и добавив к выводу кол-ва ошибок номер эпохи

![image](https://github.com/truefolder/AD_ingamedev_lab4/assets/89926388/19cbe10f-0af6-426c-9fbf-2e8ebb87a0bc)

![image](https://github.com/truefolder/AD_ingamedev_lab4/assets/89926388/56fde747-481e-457c-8cb0-895c2a3211fb)

В результате тестов выявил, что перцептрон стабильно обучается не допускать ошибок к 5 эпохе

AND. Для наглядности немного видоизменил вывод в консоль, убрав вывод весов и добавив к выводу кол-ва ошибок номер эпохи

![image](https://github.com/truefolder/AD_ingamedev_lab4/assets/89926388/2444abe4-166d-4c30-82a2-8bb1a8b91371)

![image](https://github.com/truefolder/AD_ingamedev_lab4/assets/89926388/4f2fc7f3-4b1a-4ec7-9090-f2bfe8ae7d52)

В результате тестов выявил, что перцептрон обучается менее стабильно, но чаще обучается не допускать ошибок ближе к 5-6 эпохе

NAND. Для наглядности немного видоизменил вывод в консоль, убрав вывод весов и добавив к выводу кол-ва ошибок номер эпохи

![image](https://github.com/truefolder/AD_ingamedev_lab4/assets/89926388/a22328f4-8dd2-4efa-87a4-bd981d9ddc19)

![image](https://github.com/truefolder/AD_ingamedev_lab4/assets/89926388/0922c562-b893-40fc-920f-2808d85009b2)

Ситуация аналогичная с AND. Перцептрон обучается не совсем стабильно, но чаще обучается не допускать ошибок ближе к 6 эпохе.

XOR. Для наглядности немного видоизменил вывод в консоль, убрав вывод весов и добавив к выводу кол-ва ошибок номер эпохи

![image](https://github.com/truefolder/AD_ingamedev_lab4/assets/89926388/a03b3390-03f7-4d79-93f5-64da1fc09215)

![image](https://github.com/truefolder/AD_ingamedev_lab4/assets/89926388/5d0532b4-c6ac-47c3-98ab-45abe76ad488)

Перцептрон так и не смог обучиться за 8 эпох, сколько попыток бы я ни делал.

## Задание 2
### Построить графики зависимости количества эпох от ошибки  обучения. Указать от чего зависит необходимое количество эпох обучения.

Графики зависимости кол-ва эпох от ошибки обучения:

![image](https://github.com/truefolder/AD_ingamedev_lab4/assets/89926388/a842744c-4a01-439a-9587-a5c0687bfb73)

Ссылка на таблицу: https://docs.google.com/spreadsheets/d/12VcZ_jKPWewwyecRKNHZe9JZaksNVH6YuGhkdBsq168/edit?usp=sharing


## Задание 3
### Построить визуальную модель работы перцептрона на сцене Unity.


## Выводы


## Powered by

**BigDigital Team: Denisov | Fadeev | Panov**

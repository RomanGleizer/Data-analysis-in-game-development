# АНАЛИЗ ДАННЫХ И ИСКУССТВЕННЫЙ ИНТЕЛЛЕКТ [in GameDev]
Отчет по лабораторной работе #1 выполнил(а):
- Глейзер Роман Дмитриевич
- РИ220930

| Задание | Выполнение | Баллы |
| ------ | ------ | ------ |
| Задание 1 | * | 60 |
| Задание 2 | * | 20 |
| Задание 3 | * | 20 |

Работу проверили:
- к.т.н., доцент Денисов Д.В.
- к.э.н., доцент Панов М.А.
- ст. преп., Фадеев В.О.

[![N|Solid](https://cldup.com/dTxpPi9lDf.thumb.png)](https://nodesource.com/products/nsolid)

[![Build Status](https://travis-ci.org/joemccann/dillinger.svg?branch=master)](https://travis-ci.org/joemccann/dillinger)

## Цель работы
Установить необходимое программное обеспечение, которое пригодится для создания интеллектуальных моделей на Python. Рассмотреть процесс установки игрового движка Unity для разработки игр.

## Задание 1
### Написать программу Hello World на Python с запуском в Jupiter Notebook.
Ход работы:
- Скачаваем дистрибутив языков программирования Python - Anaconda. Далее открываем Anaconda Navigator и запускаем инструмент Jupyter Notebook. Создаем папку UrFU/1-Anaconda и файл HelloWorld.jpynb. Открываем файл HelloWorld.jpynb и пишем код, который позволит вывести текст на консоль.

```py

print("Hello world")

```
![image](https://github.com/RomanGleizer/Data-analysis-in-game-development/assets/125725530/9aa19c1e-13b8-44cf-ba38-9afaec509992)

## Задание 2
### Написать программу Hello World на C# с запуском на Unity.
Ход работы:
- Выполняем авторизацию на unity.com и скачиваем Unity Hub и Microsoft Visual Studio. Затем открываем Unity Hub и создаем 3D проект. Выполняем настройку Script Editor и создаем C# Script, где уже и пишем C# код.

```cs

using UnityEngine;

public class HelloWorldPrinter : MonoBehaviour
{
    private void Awake()
        => Debug.Log("Hello world !");
}

```
![image](https://github.com/RomanGleizer/Data-analysis-in-game-development/assets/125725530/9ed659d5-909e-4651-83cf-3ae6fa30e58f)


## Задание 3
### Оформить отчет в виде документации на github.

- Для выполнения 3 задания сначала я выполнил первое, а затем второе. После чего я собрал результаты и оформил отчет.

## Выводы

- Сегодня я научился пользоваться Jupyter, а именно создавать там файлы, а так же опробовал себя в составлении отчетов на GitHub.

| Plugin | README |
| ------ | ------ |
| Dropbox | [plugins/dropbox/README.md][PlDb] |
| GitHub | [plugins/github/README.md][PlGh] |
| Google Drive | [plugins/googledrive/README.md][PlGd] |
| OneDrive | [plugins/onedrive/README.md][PlOd] |
| Medium | [plugins/medium/README.md][PlMe] |
| Google Analytics | [plugins/googleanalytics/README.md][PlGa] |

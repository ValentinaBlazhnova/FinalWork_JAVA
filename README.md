# Проект "Лоттерея Игрушек"

## Задача:

Необходимо написать программу – розыгрыша игрушек в магазине детских товаров с применением ООП и работа с файлами.

## Функционал программы:

1. В программе есть класс со следующими свойствами:
id игрушки,
текстовое название,
количество
частота выпадения игрушки (вес в % от 100).
 
2. Метод добавление новых игрушек и возможность изменения веса (частоты выпадения игрушки).

3. Возможность организовать розыгрыш игрушек.
Например, следующим образом:
С помощью метода выбора призовой игрушки – мы получаем эту призовую игрушку и записываем в список\массив.
Это список призовых игрушек, которые ожидают выдачи.
Есть метод – получения призовой игрушки.
После его вызова – мы удаляем из списка\массива первую игрушку и сдвигаем массив. А эту игрушку записываем в текстовый файл.
Уменьшение количества игрушек.

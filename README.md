# HW9
## Задание 1
Для того, чтобы удалить все пустые строки, я использовала регулярное выражение "\n\r" и заменила все вхождения на "\0".
![](https://github.com/manastasia/HW9/blob/master/1.jpg)

## Задание 2
Все упоминания князей и городов на "слав" нашлись регулярным выражением "[А-Я]слав". Всего было найдено 626 вхождений.
![](https://github.com/manastasia/HW9/blob/master/3.png)
![](https://github.com/manastasia/HW9/blob/master/3.2.png)

## Задание 3
Все упоминания города Новгорода я нашла с помощью регулярного выражения "Нов(.?)город([а-я]?)", использовав функцию "Match case". Всего было найдено 59 вхождений.
![](https://github.com/manastasia/HW9/blob/master/2.png)
![](https://github.com/manastasia/HW9/blob/master/2.2.png)


## Бонусное задание
Все пробелы, необходимые до и после определенных знаков препинания, можно расставить с помощью регулярного выражения (\:|\;|\,)|(\[)|(([А-Яа-я]|\»)(\.)([^.]))
![](https://github.com/manastasia/HW9/blob/master/4.1.png)
![](https://github.com/manastasia/HW9/blob/master/4.2.png)

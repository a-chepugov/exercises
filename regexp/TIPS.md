Можно выполнить задачу в два этапа:

1. Почистить строку от лишних символов:
[String.prototype.replace]() и замены всего, что сойдется с регулярным выражением `/\D/g` на пустую строку

2. Разбить получившуюся строку на блоки с помощью регулярного выражения (группы с заданным количеством цифр)
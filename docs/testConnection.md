Как пользоваться мультиметром?
========================================

## 1. Проверка цепей (прозвонка)

### Важно! Проверяемый объект должен быть отключен от питания (обесточен)!!!


С помощью мультиметра проверить отсутствие короткого замыкания (прозвонить):

* Выставить мультиметр в режим прозвона.
* Проверить работу мультиметра путем замыкания щупов между собой. При корректной работе прибор издаст  характерный звук.
* Попарно красный щуп прикладывается к “+ ”контакту, черный к “-” / ”GND”. Если в цепи есть короткое замыкание, издается звук.

![Режим прозвонки](assets/startPDBtest.jpg)

1. Прозвонить следующие цепи на НЕЗАМКНУТОСТЬ (отсутствие звукового сигнала мультиметра):

* “BAT+” и “BAT-” 
* “12V” и “GND”
* “5V” и “GND”


2. Прозвонить следующие цепи на ЗАМКНУТОСТЬ (появление звукового сигнала мультиметра):

* “BAT-” c каждым контактом, обозначенным “-” и “GND” 
* “BAT+”, с каждым контактом, обозначенным “+”


## 2. Проверка напряжения

С помощью мультиметра необходимо удостовериться, что преобразователи напряжения, расположенные на плате распределения питания, работают исправно и выдают напряжение 5В и 12В соответственно.

* Переключить мультиметр в режим "Измерение постоянного напряжения"
* Выбрать верхнюю границу измеряемого напряжения (в нашем случае, не более 20 В)
* Убедиться,  что АКБ подключено
* Провести следующие измерения:
   1. Замерить напряжение АКБ (между BAT+ и BAT-). Оно должно лежать в пределах от 14.0В до 16.8В
   2. Замерить напряжение на выходе 5В. Оно не должно превышать 5.5В
   3. Замерить напряжение на выходе 12В. Оно не должно превышать 12.5В
   
После проведенных измерений:
* отключите АКБ
* выключите мультиметр
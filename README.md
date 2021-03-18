# GLO Academy course JS 13.0

## Информация

Архивный репозиторий с выполненными заданиями во время курса GLO academy.
Часть репозититория скоопирована и вынесена в отдельные проекты:

+ https://github.com/melodoc/todo-list
+ https://github.com/melodoc/budget-calculator
+ https://github.com/melodoc/guess-number

Дата прохождения: **04-06-20** — **29-07-20**

## Уроки 

<details>
  <summary>Урок №1</summary>
  
  ### Задание 
  1. Создать пустой репозиторий на GitHub
  2. Создать HTML-страницу и подключить к ней файл скрипта
  3. В файле скрипта создать переменные
  4. Вывести на экран в модальном окне (alert) сообщение с любым текстом
  5. Вывести в консоль сообщение с любым текстом

https://github.com/melodoc/JS-glo-academy-course/tree/lesson01
</details>


<details>
  <summary>Урок №2</summary>
  
  ### Задание 
  1. Присвоить переменным значения 
  2. Используя методы и свойства вывести типы данных переменных, объявить переменные

https://github.com/melodoc/JS-glo-academy-course/tree/lesson02
</details>

<details>
  <summary>Урок №2 — Усложнённое</summary>
  
  ### Задание 
  1. Создать переменную num со значением 266219 (тип данных число)
  2. Вывести в консоль произведение (умножение) цифр этого числа
  3. Полученный результат возвести в степень 3, используя только 1 оператор (Math.pow не подходит)
  4. Вывести на экран первые 2 цифры полученного числа

https://github.com/melodoc/JS-glo-academy-course/tree/lesson02-hard
</details>

<details>
  <summary>Урок №3</summary>
  
  ### Задание 
  1. Сохранить в переменные результаты пользовательского ввода 
  2. Вычислить бюджет на месяц, учитывая обязательные расходы, сохранить в новую переменную budgetMonth и вывести результат в консоль
  3. Вычислить значение цели mission, округляя в большую сторону (методы объекта Math)
  4. Вычислить budgetDay учитывая бюджет на месяц, округлив в меньшую сторону 
  5. Вычислить уровень дохода.

https://github.com/melodoc/JS-glo-academy-course/tree/lesson03
</details>


<details>
  <summary>Урок №3 — Усложнённое</summary>
  
  ### Задание 
  1. Переменная lang может принимать 2 значения: 'ru' 'en'. Написать условия при котором в зависимости от значения lang будут выводится дни недели на русском или английском языке.

https://github.com/melodoc/JS-glo-academy-course/tree/lesson03-hard
</details>


<details>
  <summary>Урок №4</summary>
  
  ### Задание 
  1. Реализовать функцию getExpensesMonth, которая возвращает сумму всех обязательных расходов за месяц
  2. Реализовать функцию getAccumulatedMonth, которая возвращает значение накоплений за месяц
  3. Добавить переменную accumulatedMonth и присвоить ей результат вызова функции getAccumulatedMonth 
  4. Реализовать функцию getTargetMonth, которая возвращает период, за который будет достигнута цель
  5. Удалить budgetMonth и вычислить значение budgetDay

https://github.com/melodoc/JS-glo-academy-course/tree/lesson04
</details>

<details>
  <summary>Урок №4 — Усложнённое</summary>
  
  ### Задание 
  1. Создать функцию, которая принимает один аргумент-строку. Убрать все пробелы в начале и в конце, после 30-го символа часть текста заменяется на троеточие (...). Если в качестве аргумента передана не строка - функция оповещает об этом пользователя

https://github.com/melodoc/JS-glo-academy-course/tree/lesson04-hard
</details>

<details>
  <summary>Урок №5</summary>
  
  ### Задание 
  1. Переписать функцию start циклом do while
  2. Добавить проверку, что введённые данные являются числом в функции  getExpensesMonth
  3. Если getTargetMonth возвращает отрицательное значение, необходимо выводить “Цель не будет достигнута”

https://github.com/melodoc/JS-glo-academy-course/tree/lesson05
</details>

<details>
  <summary>Урок №5 — Усложнённое</summary>
  
  ### Задание 
  1. Создать массив arr = []. Записать в него 7 любых многозначных чисел в виде строк. Вывести в консоль только те, что начинаются с цифры 2 или 4
  2. Вывести все простые числа от 1 до 100. Рядом с каждым числом написать оба делителя данного числа

https://github.com/melodoc/JS-glo-academy-course/tree/lesson05-hard
</details>

<details>
  <summary>Урок №6</summary>
  
  ### Задание 
  1. Загадывание случайного числа от 1 до 100 с помощью рекурсии. Загаданное число должно храниться «в замыкании»

https://github.com/melodoc/JS-glo-academy-course/tree/lesson06
</details>

<details>
  <summary>Урок №6 — Усложнённое</summary>
  
  ### Задание 
  1. Добавить ограниченное количество попыток

https://github.com/melodoc/JS-glo-academy-course/tree/lesson06-hard
</details>

<details>
  <summary>Урок №7</summary>
  
  ### Задание 
  1. Функцию showTypeof и вызов функции удаляем 
  2. В объект appData добавить свойство budget которое будет принимать значение money
  3. В объект appData добавить свойства budgetDay, budgetMonth и expensesMonth, изначально равные нулю
  4. Функции getExpensesMonth, getAccumulatedMonth, getTargetMonth, getStatusIncome - сделать методами объекта AppData
  5. После этого поправить весь проект, чтобы он работал
  6. Вызвать все необходимые методы после объекта, чтобы корректно считались все данные (порядок важен)

https://github.com/melodoc/JS-glo-academy-course/tree/lesson07
</details>

<details>
  <summary>Урок №8</summary>
  
  ### Задание 
  1. Сделать проверку при получении данных:
     * наименование дополнительного источника заработка
     * сумма дополнительного заработка
     * ввод статьи обязательных расходов
     * годовой процент депозита
     * сумма депозита
  2. Возможные расходы (addExpenses) вывести строкой в консоль каждое слово с большой буквы слова разделены запятой и пробелом

https://github.com/melodoc/JS-glo-academy-course/tree/lesson08
</details>

<details>
  <summary>Урок №9</summary>
  
  ### Задание 
  1. Добавить верстку, отредактировать код

https://github.com/melodoc/JS-glo-academy-course/tree/lesson09
</details>

<details>
  <summary>Урок №9 — Усложнённое</summary>
  
  ### Задание 
  1. Вывести на страницу текущую дату и время в 2-х форматах: 
     * 'Сегодня Вторник, 4 февраля 2020 года, 21 час 5 минут 33 секунды'  
     * '04.02.2020 - 21:05:33' 
  1. Для вывода в формате (а) напишите функцию, которая будет менять менять склонение слов в зависимости от числа, "час, часов, часа"
  1. Для вывода в формате (б) напишите функцию, которая будет добавлять 0 перед значениями которые состоят из одной цифры (из 9:5:3  1.6.2019 сделает 09:05:03 01.06.2019)
  1. С помощью функции setInterval, реализуйте вывод даты и времени каждую секунду 

https://github.com/melodoc/JS-glo-academy-course/tree/lesson09-hard
</details>

<details>
  <summary>Урок №10</summary>
  
  ### Задание 
  1. Используя только js:
     * Восстановить порядок книг.
     * Заменить картинку заднего фона на другую из папки image
     * Исправить заголовок в книге 3
     * Удалить рекламу со страницы
     * Восстановить порядок глав во второй и пятой книге
     * В шестой книге добавить главу “Глава 8: За пределами ES6” и поставить её в правильное место

https://github.com/melodoc/JS-glo-academy-course/tree/lesson10
</details>

<details>
  <summary>Урок №11</summary>
  
  ### Задание 
  1. Доработать проект:
     * Переписать метод getIncome аналогично getExpenses
     * Создать метод addIncomeBlock аналогичный addExpensesBlock
     * Округлить вывод дневного бюджета
     * Число под полоской (input type range) должно меняться в зависимости от позиции range, используем событие input.
     * Добавить обработчик события внутри метода showResult, который будет отслеживать период и сразу менять значение в поле “Накопления за период” (После нажатия кнопки рассчитать, если меняем ползунок в range, “Накопления за период” меняются динамически аналогично 4-ому пункту)
     * Запретить нажатие кнопки Рассчитать пока поле Месячный доход пустой, проверку поля Месячный доход в методе Start убрать.

https://github.com/melodoc/JS-glo-academy-course/tree/lesson11
</details>

<details>
  <summary>Урок №11 — Усложнённое</summary>
  
  ### Задание 
  1. Доработать проект:
     * Реализовать так, чтобы инпуты добавлялись пустые без value при добавлении новых полей в обязательных расходах и дополнительных доходах 
     * Поля с placeholder="Наименование" разрешить ввод только русских букв пробелов и знаков препинания
     * Поля с placeholder="Сумма" разрешить ввод только цифр

https://github.com/melodoc/JS-glo-academy-course/tree/lesson11-hard
</details>

<details>
  <summary>Урок №12</summary>
  
  ### Задание 
  1. Написать свой ToDo List

https://github.com/melodoc/JS-glo-academy-course/tree/lesson12
</details>

<details>
  <summary>Урок №13</summary>
  
  ### Задание 
  1. Привязать контекст вызова функции start к appData 
  2. В нашем объекте везде использовать this как ссылку на объект appData
  3. Проверить работу кнопок плюс и input-range
  4. Блокировать все input[type=text] с левой стороны после нажатия кнопки рассчитать, после этого кнопка Рассчитать пропадает и появляется кнопка Сбросить, на которую навешивается событие и выполнение метода reset

https://github.com/melodoc/JS-glo-academy-course/tree/lesson13
</details>

<details>
  <summary>Урок №13 — Усложнённое</summary>
  
  ### Задание 
  1. Генерация цветов и замена цвета фона

https://github.com/melodoc/JS-glo-academy-course/tree/lesson13-hard
</details>

<details>
  <summary>Уроки №14-22</summary>
  
  ### Ссылки 
  1. https://github.com/melodoc/JS-glo-academy-course/tree/lesson14-1
  2. https://github.com/melodoc/JS-glo-academy-course/tree/lesson14-1-hard
  3. https://github.com/melodoc/JS-glo-academy-course/tree/lesson14-2
  4. https://github.com/melodoc/JS-glo-academy-course/tree/lesson15
  5. https://github.com/melodoc/JS-glo-academy-course/tree/lesson16
  6. https://github.com/melodoc/JS-glo-academy-course/tree/lesson18-2
  7. https://github.com/melodoc/JS-glo-academy-course/tree/lesson18-hard
  8. https://github.com/melodoc/JS-glo-academy-course/tree/lesson22
</details>


Домашняя работа 23


Задание 1


Обработка цепочки промисов с `async/await`


Создайте несколько функций, которые возвращают промисы с разным временем выполнения.


Напишите функцию, которая вызывает эти промисы поочерёдно, используя `await`, и обрабатывает результаты каждой операции.


Убедитесь, что цепочка промисов выполняется последовательно.


Задание 2


Асинхронная обработка данных из массива


Напишите функцию, которая принимает массив строк.


Каждая строка будет асинхронно обрабатываться (например, преобразовываться в верхний регистр с задержкой).


Используйте `Promise.all` для выполнения всех операций параллельно и вывода всех результатов.


Задание 3


Обработка ошибки в параллельных промисах


Напишите функцию, которая вызывает три промиса параллельно с помощью `Promise.all`.


Один из промисов должен намеренно завершиться с ошибкой через `reject`. 


Обработайте эту ошибку с использованием `try/catch` и выведите соответствующее сообщение.


Задание 4


Асинхронная функция с динамическим временем выполнения


Напишите асинхронную функцию, которая принимает массив чисел.


Для каждого числа создайте промис, который будет завершаться через количество миллисекунд, равное значению числа.


Используйте `Promise.all` для ожидания завершения всех промисов и вывода результатов в консоль.

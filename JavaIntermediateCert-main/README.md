# Калькулятор комплексных чисел

## Описание

Работу выполнил студент **GeekBrains** - *Доткулов Анзор*.

## Структура проекта

* `model`: Содержит классы `ComplexNumber`, `ComplexCalculator`, `LogCalculator` и интерфейс `Calculable`, которые реализуют логику работы калькулятора.
* `view`: Содержит класс `ViewCalculator`, который отвечает за взаимодействие с пользователем.
* `factory`: Содержит классы `CalculableFactory` и `LogCalculableFactory` и интерфейс `ICalculableFactory`, которые используются для создания объектов `Calculable`, чтобы отделить процесс создания объектов от их использования. 
* `logger`: Содержит класс `ConsoleLogger` и интерфейс `Logable`, которые используются для логирования операций. Это сделано, чтобы отделить логику логирования от основной логики приложения.

## Принципы SOLID

Каждый класс имеет одну ответственность, и новые операции можно добавлять без изменения существующего кода.
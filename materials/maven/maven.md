{% include header.md %}

Введение в сборщик проектов Maven
====================

Описание модуля
---------------------
В рамках данного модуля вы изучите основной сборщик java-проектов - Maven 

Материалы для самоподготовки
---------------------
1. [Курс на Learn.by](https://learn.by/courses/course-v1:EPAM+MBT+ext1/about)
1. [Перевод документации мавена](https://www.apache-maven.ru/)
1. [Туториалы по мавену](https://proselyte.net/tutorials/maven/)

Практическая работа
---------------------

### Задание №1
Создайте многомодульный мавен проект. Один из его модулей должен быть зависимой библиотекой для другого модуля. 
Подключите несколько зависимостей разных скупов. Подключите плагины для прогона тестов и компиляции. Создайте папку
resources. При сборке все файлы из этой папки должны попадать в результирующий артефакт.
Соберите и запустите его через консоль.

Вопросы для самоконтроля
---------------------
1. Зачем нужны сборщики проектов? Какие задачи они обычно выполняют? 
1. Как установить мавен на рабочую машину?
1. Какие команды можно выполнять из консоли (mvn ...)
1. Что такое pom.xml? Какие основные части можно выделить? 
1. Что такое артефакт? Чем отличются war, jar и ear расширения?
1. Перечислите 3 build lifecycle. Что делает каждая из них? 
1. Перечислите несколько фаз (phase) мавена. Что делает каждая из них?  
1. Что такое мавен репозиторий? Какие типы репозиториев учавствуют в процессе работы?
1. Какие скоупы зависимостей существуют? Что означает каждая из них?
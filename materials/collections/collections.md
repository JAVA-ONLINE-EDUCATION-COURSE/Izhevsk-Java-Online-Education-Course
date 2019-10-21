{% include header.md %}

Работа с коллекциями в Java
====================

Описание модуля
---------------------
В рамках данного модуля вы узнаете, как реализованы стандартные коллекции в джаве, какие есть самые популярные 
реализации и как правильно работать с ними.

Охватываемые темы
---------------------
+ Иерархия коллекций в Java
+ Списки (Set)
+ Очереди (Queue)
+ Множества (Set)
+ Ассоциативные массивы (Map)
+ Итераторы

Материалы для самоподготовки
---------------------
1. [Курс на Learn.by](https://learn.by/courses/course-v1:EPAM+JColl+ext1/about)
1. [Общий справочник по Java Collections Framework](https://habrahabr.ru/post/237043/)
1. [Обзор коллекции ArrayList](http://habrahabr.ru/post/128269/)
1. [Обзор коллекции LinkedList](http://habrahabr.ru/post/127864/)
1. [Обзор коллекции HashMap](http://habrahabr.ru/post/128017/)
1. [Видео: коллекции в Java](https://www.youtube.com/watch?v=7gws2decf2g)
1. [Видео: HashSet и TreeSet](https://www.youtube.com/watch?v=-S_huEuNJiU)
1. [Видео: реалзиации интерфейса Map](https://www.youtube.com/watch?v=5Iu4ZUcrJ0g)
1. [Видео: очередь и приоритетная очередь](https://www.youtube.com/watch?v=5_f5foEXiYY)
1. [Видео: многопоточные коллекции](https://www.youtube.com/watch?v=-yQeYo32Lt4)
1. [Видео: блокирующая очередь](https://www.youtube.com/watch?v=nUYOGkh9XqE)

Практическая работа
---------------------
[Репозиторий с шаблоном практической работы](https://github.com/JAVA-ONLINE-EDUCATION-COURSE/java-collections-template)

Вопросы для самоконтроля
---------------------
1. Назовите основные интерфейсы коллекций и их имплементации.
1. Чем отличается `ArrayList` от `LinkedList`? В каких случаях лучше использовать первый, а в каких второй?
1. Как сравниваются елементы коллекций?
1. Дайте определение понятиям `Iterator` и `Iterable`.
1. Если у класса переопределен `hashCode`, какой метод еще следует переопределить?
1. Если у двух экземпляров метод `equals` возвращает true, может ли `hashCode` вернуть различные значения?
1. Если у двух экземпляров метод `hashCode` возвращает одинаковое значение, может ли `equals` вернуть false?
1. Можно ли в методе `hashCode` писать `return 1`? Как оптимально реализовать метод `hashCode`?
1. Устройство `HashMap`?
1. В чем разница между `HashMap`, `SortedMap`, `TreeMap`, `LinkedHashMap`?
1. При объявлении типов переменных, что предпочтительнее `List<Student>` или `ArrayList<Student>`?
1. В каких случаях стоит использовать `Queue`? Чем `Queue` отличается от `Deque`?



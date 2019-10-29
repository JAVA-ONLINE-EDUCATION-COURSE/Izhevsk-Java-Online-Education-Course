{% include header.md %}

Работа с коллекциями в Java
====================

Описание модуля
---------------------
В рамках данного модуля вы узнаете, как реализованы стандартные коллекции в джаве, какие есть самые популярные 
реализации и как правильно работать с ними.

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
1. *[Видео: Stream Api (Часть 1)](https://www.youtube.com/watch?v=O8oN4KSZEXE)
1. *[Видео: Stream Api (Часть 2)](https://www.youtube.com/watch?v=i0Jr2l3jrDA)

Практическая работа
---------------------
[Репозиторий с шаблоном практической работы](https://github.com/JAVA-ONLINE-EDUCATION-COURSE/java-collections-template)

Вопросы для самоконтроля
---------------------
1. Назовите основные интерфейсы коллекций и их имплементации.
1. В чем преимущество списков на фоне массивов?
1. Чем отличается `ArrayList` от `LinkedList`? В каких случаях лучше использовать первый, а в каких второй?
1. Как сравниваются элементы коллекций?
1. Что такое O(n)? Оцените скорость вставки/поиска в разных реализациях списка.
1. Дайте определение понятиям `Iterator` и `Iterable`.
1. В чем связь `TreeSet` и таких сущностей, как `Comparator` и `Comparable`?
1. Устройство `HashMap`? Как зависит `HashMap` от реализации метода `hashCode` у объекта, который мы кладем туда?
1. В чем разница между `HashMap`, `SortedMap`, `TreeMap`, `LinkedHashMap`?
1. Что означает `List<String>` от просто `List`?
1. При объявлении типов переменных, что предпочтительнее `List<Student>` или `ArrayList<Student>`?
1. В каких случаях стоит использовать `Queue`? Чем `Queue` отличается от `Deque`?
1. Потокобезопасны ли реализации `List`, `Map`? Приведите примеры потокобезопасных коллекций
1. Что такое стрим? Как создать стрим?
1. В чем разница между терминальными и конвейерными операциями? Приведите по 3 примера каждого
1. Что такое коллектор? Какие стандартные реализации коллекторов существуют?


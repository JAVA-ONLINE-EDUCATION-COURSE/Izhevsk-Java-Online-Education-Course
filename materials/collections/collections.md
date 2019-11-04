{% include header.md %}

Работа с коллекциями в Java
=====================

Материалы для самоподготовки
---------------------
### Основные материалы - Java Collections
1. [Видео: Learn - Java Collections](https://learn.by/courses/course-v1:EPAM+JColl+ext1/about){:target="_blank"}
1. [Habrahabr: Общий справочник по Java Collections Framework](https://habrahabr.ru/post/237043/){:target="_blank"}
1. [Habrahabr: Обзор коллекции ArrayList](http://habrahabr.ru/post/128269/){:target="_blank"}
1. [Habrahabr: Обзор коллекции LinkedList](http://habrahabr.ru/post/127864/){:target="_blank"}
1. [Habrahabr: Обзор коллекции HashMap](http://habrahabr.ru/post/128017/){:target="_blank"}
1. [Habrahabr: Java собеседование. Коллекции](https://habr.com/ru/post/162017/){:target="_blank"}
1. [Jenkov: Java Collections Tutorial](http://tutorials.jenkov.com/java-collections/index.html){:target="_blank"}

### Основные материалы - Java Generics
1. [Habrahabr: Пришел, увидел, обобщил: погружаемся в Java Generics](https://habr.com/ru/company/sberbank/blog/416413/){:target="_blank"}

### Основные материалы - Java Stream Api
1. [Видео: Stream Api (Часть 1)](https://www.youtube.com/watch?v=O8oN4KSZEXE){:target="_blank"}
1. [Видео: Stream Api (Часть 2)](https://www.youtube.com/watch?v=i0Jr2l3jrDA){:target="_blank"}
1. [Java 8 Stream Tutorial](https://winterbe.com/posts/2014/07/31/java8-stream-tutorial-examples/){:target="_blank"}

### Дополнительные материалы - Java Stream Api
1. [Habrahabr: Шпаргалка Java программиста. Java Stream API](https://habr.com/ru/company/luxoft/blog/270383/){:target="_blank"}

Практическая работа
---------------------
[Репозиторий с шаблоном практической работы](https://github.com/JAVA-ONLINE-EDUCATION-COURSE/java-collections-template){:target="_blank"}

Вопросы для самоконтроля
---------------------
### Java Collections
1. Что такое коллекция? Для чего она необходима?
1. Назовите основную иерархию коллекций (интерфейсы и их основные реализации).
1. Расскажите кратко о предназначении каждого вида коллекции. Чем она удобна? Каковые особенности ее работы?
1. В чем преимущество коллекций на фоне массивов?
1. Как создать коллекцию из массива?
1. Как внутри устроен `ArrayList`?
1. Как внутри устроен `LinkedList`? 
1. Чем отличается `ArrayList` от `LinkedList`? В каких случаях лучше использовать первый, а в каких второй?
1. Как происходит удаление элементов из `ArrayList`? Как меняется в этом случае размер `ArrayList`?
1. Как происходит удаление элементов из `LinkedList`? Что происходит с элементами в `LinkedList` при удалении одного из них?
1. Как сравнить элементы двух коллекий? Как узнать, что первая коллекция содержит все те же элементы, что и вторая?
1. Дайте определение понятиям `Iterator` и `Iterable`.
1. Для чего нужно коллекция `TreeSet`? Что такое `Comparator` и `Comparable`, как они связаны с этой коллекцией?
1. Устройство `HashMap`? Как зависит `HashMap` от реализации метода `hashCode`? Что такое корзины (бакеты) в `HashMap`?
1. Как получить все ключи `HashMap`?
1. Как получить все значения `HashMap`?
1. Расскажите по шагам, что происходит при вставке элементов в `HashMap`? А если будет вставка по одинаковому ключу? Если по разным? Что лучше использовать в качетве ключа?
1. В чем разница между `HashMap`, `SortedMap`, `TreeMap`?
1. Какие коллекции реализуют интерфейс `Set`? В чем особенность данных коллекций? Как они работают? Как зависят коллекции типа `Set` от реализации метода `equals`?
1. В каких случаях стоит использовать `Queue`? Чем `Queue` отличается от `Deque`?

### Java Generics
1. Что отличает `List<String> parsedWords = ...` от просто `List parsedWords = ...`?
1. При объявлении типов переменных, что предпочтительнее `List<Student> student = ...` или `ArrayList<Student> student = ...`?
1. Что такое дженерики? Для чего они нужны?

### Java Stream Api
1. Что такое Stream? Как создать Stream? Что он позволяет? В чем разница между Collection и Stream?
1. Какие существуют способы создания стрима?
1. Что такое Optional?
1. Для чего нужен метод collect() в стримах? Какие стандартные реализации коллекторов существуют?
1. Для чего в стримах применяются методы forEach() и forEachOrdered()?
1. Для чего в стримах предназначены методы map() и mapToInt(), mapToDouble(), mapToLong()?
1. Какова цель метода filter() в стримах?
1. Для чего в стримах предназначен метод limit()?
1. Для чего в стримах предназначен метод sorted()?
1. В чем разница между терминальными и конвейерными операциями?
1. Что будет выведено в консоль?
```java
String collect = IntStream.range(1, 4)
        .mapToObj(i -> "a" + i)
        .map(String::toUpperCase)
        .sorted(Comparator.reverseOrder())
        .collect(Collectors.joining("-"));
System.out.println(collect);
```


{% include header.md %}

Работа с данными
=====================

Материалы для самоподготовки
---------------------
### Основные материалы - Java Strings and RegExp
1. [Видео: Learn - Java Strings](https://learn.by/courses/course-v1:EPAM+JS_RD_BY+ext1/about){:target="_blank"}
1. [Jenkov: Java Strings](http://tutorials.jenkov.com/java/strings.html){:target="_blank"}

### Основные материалы - Java I/O
1. [Видео: Learn - Java I/O](https://learn.by/courses/course-v1:EPAM+JIO+ext1/about){:target="_blank"}
1. [Jenkov: Java IO Tutorial](http://tutorials.jenkov.com/java-io/index.html){:target="_blank"}
1. [Jenkov: Java NIO Tutorial](http://tutorials.jenkov.com/java-nio/index.html){:target="_blank"}

### Основные материалы - Java Date and Time
1. [Java 8 дата и время](https://urvanov.ru/2016/06/16/java-8-%D0%B4%D0%B0%D1%82%D0%B0-%D0%B8-%D0%B2%D1%80%D0%B5%D0%BC%D1%8F/){:target="_blank"}
1. [Jenkov: Parsing and Formatting Dates in Java](http://tutorials.jenkov.com/java-date-time/parsing-formatting-dates.html){:target="_blank"}
1. [Jenkov: Java Instant](http://tutorials.jenkov.com/java-date-time/instant.html){:target="_blank"}
1. [Jenkov: Java Instant](http://tutorials.jenkov.com/java-date-time/duration.html){:target="_blank"}
1. [Jenkov: Java LocalDate](http://tutorials.jenkov.com/java-date-time/localdate.html){:target="_blank"}
1. [Jenkov: Java LocalTime](http://tutorials.jenkov.com/java-date-time/localtime.html){:target="_blank"}
1. [Jenkov: Java LocalDateTime](http://tutorials.jenkov.com/java-date-time/localdatetime.html){:target="_blank"}
1. [Jenkov: Java ZonedDateTime](http://tutorials.jenkov.com/java-date-time/zoneddatetime.html){:target="_blank"}
1. [Jenkov: Java DateTimeFormatter](http://tutorials.jenkov.com/java-date-time/datetimeformatter.html){:target="_blank"}

### Основные материалы - Java Math
1. [Java 8 числа](https://urvanov.ru/2016/04/17/java-8-%D1%87%D0%B8%D1%81%D0%BB%D0%B0/#bigdecimal){:target="_blank"}

### Дополнительные материалы - Java I/O
1. [Habrahabr: Основные отличия Java IO и Java NIO](https://habr.com/ru/post/235585/){:target="_blank"}

### Дополнительные материалы - Java Strings and RegExp
1. [Java 8 регулярные выражения](https://urvanov.ru/2016/06/08/java-8-%D1%80%D0%B5%D0%B3%D1%83%D0%BB%D1%8F%D1%80%D0%BD%D1%8B%D0%B5-%D0%B2%D1%8B%D1%80%D0%B0%D0%B6%D0%B5%D0%BD%D0%B8%D1%8F/){:target="_blank"}
1. [Habrahabr: Обработка строк в Java. Часть I: String, StringBuffer, StringBuilder](https://habr.com/ru/post/260767/){:target="_blank"}
1. [Habrahabr: Обработка строк в Java. Часть II: Pattern, Matcher](https://habr.com/ru/post/260773/){:target="_blank"}

Практическая работа
---------------------
[Репозиторий с шаблоном практической работы](https://github.com/JAVA-ONLINE-EDUCATION-COURSE/java-data-handling-template){:target="_blank"}

Вопросы для самоконтроля
---------------------
### Java Math
1. В чем отличие примитивных типов, например, int от типов-оберток (wrapper-type), например, `Integer`? Какой тип в каких случаях выбрать?
1. Что такое автоупаковка/автораспаковка? Кем выполняется? Плюсы-минусы?
1. Основные принципы округления в Java?
1. Что будет выведено в консоль?
```java
System.out.println(0.1 + 0.2);
```
1. Как работать в Java c разными системами счисления? (двоичная, шестнадцатеричная и т.д.)
1. Как сравнить два целых или вещественных числа? Больше\меньше\равенство?
1. Что такое `BigDecimal`, `BigInteger`? Для чего нужны эти классы?
1. В чем отличие `Long` от `BigInteger`?
1. В чем отличие `Double` от BigDecimal`?
1. Назначение `MathContext` при работе с `BigDecimal`?
1. Для чего нужен метод `setScale` при работе с `BigDecimal`?
1. Что означают `NaN`, `POSITIVE_INFINITY`, `NEGATIVE_INFINITY`?
1. Для чего нужен класс `Random`?

### Java Strings
1. Какие есть особенности у класса `String`?
1. String неизменяемый и финализированный класс. Что это значит?
1. Что такое «пул строк»?
1. Можно ли использовать строки в конструкции switch?
1. Какие могут возникнуть проблемы при конкатенации большого числа строк в цикле? Как решать?
1. Для чего нужны `StringBuffer`, `StringBuilder`?
1. Как привести строку к нижнему регистру?
1. Как сравнить две строки без учета регистра?
1. Как в строке “abdсef” заменить “dс” на “cd”?

### Java RegExp
1. Дана строка и дано регулярное выражение. Необходимо проверить, соответствует ли строка регулярному выражению. Как?
1. Дана строка и дано регулярное выражение. Необходимо найти подстроку, соответствующую регулярному выражению. Как?
1. Дана строка и дано регулярное выражение. Необходимо разделить строку на массив строк используя в качестве разделителя регулярное выражение. Как?
1. Приведите регулярное выражение для поиска строки вида 8 (912) любое количество символов 12.

### Java Date and Time
1. В чем отличие классов `LocalTime`, `LocalDate`, `LocalDateTime`?
1. Что такое `ZonedDateTime`?
1. Как получить текущую дату с использованием Date Time API из Java 8?
1. Как добавить 1 неделю, 1 месяц, 1 год, 10 лет к текущей дате с использованием Date Time API из Java 8?
1. Как получить следующий вторник используя Date Time API из Java 8?

### Java I/O
1. Какие существуют виды потоков ввода/вывода?
1. Назовите основные классы потоков ввода/вывода.
1. В чём заключается разница между IO и NIO?
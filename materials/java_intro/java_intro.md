{% include header.md %}

Введение в платформу Java
====================

Материалы для самоподготовки
---------------------
### Основные материалы - Java fundamentals
1. [Видео: Learn - Java Fundamentals](https://learn.by/courses/course-v1:EPAM+JF+ext1/about){:target="_blank"} (только раздел GETTING STARTED)
1. [Habrahabr: Инструменты для запуска и разработки Java приложений, компиляция, выполнение на JVM](https://habr.com/ru/post/471772/){:target="_blank"}
1. [Как поставить Java локально](https://www.w3schools.com/java/java_getstarted.asp){:target="_blank"}

### Дополнительные материалы - Java fundamentals
1. [Горячие клавиши в Intelliji Idea](./Intelliji_idea_shortcuts.pdf){:target="_blank"}
1. [Java Google Codestyle](https://google.github.io/styleguide/javaguide.html){:target="_blank"}

Практическая работа
---------------------
>**Важно**: Прочитайте еще раз **[правила]({{site.materialsurl}}general/practical_tasks_completing_rules)** выполнения практических заданий при работе с готовыми шаблонами приложений

1. Установите **[JDK 1.8+](https://www.oracle.com/technetwork/java/javase/downloads/jdk8-downloads-2133151.html){:target="_blank"}** себе 
на рабочую машину.
2. Убедитесь, что переменная окружения `JAVA_HOME` прописана верно, путь до bin добавлен в переменную окружения `path` и вы можете из консоли вызывать команды JDK, например `java -version`. 
3. Установите IDE (редактор кода). Рекомендуем использовать **[Intelliji Idea](https://www.jetbrains.com/idea/)**.
4. Создайте свое первое приложение "Hello World" (можно использовать следующий пример **[Создание первого приложения]({{site.materialsurl}}java_intro/hello-world-tutorial)**).
5. Запустите, убедитесь, что программа выполняется корректно.
6. Запуште получивщуюся программу в удаленный репозиторий. Для этого 

Вопросы для самоконтроля
---------------------
{% include questions/java_intro_questions.md %}
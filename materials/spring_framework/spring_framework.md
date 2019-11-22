{% include header.md %}

Основы фреймворка Spring
===
{% include module-not-completed-advanced.md %}

Материалы для самоподготовки
---------------------

1. [Презентация по Spring Core](./presentations/Spring%20Core.pptx)
1. https://www.youtube.com/watch?v=6mXTY7RSAf0
1. [Видеоуроки](https://www.youtube.com/watch?v=3wBteulZaAs&list=PL6jg6AGdCNaWF-sUH2QDudBRXo54zuN1t){:target="_blank"}
1. [Документация на русском](http://spring-projects.ru/projects/spring-framework/){:target="_blank"}
https://habr.com/ru/company/infopulse/blog/150563/

Практическая работа
---------------------
[Репозиторий с шаблоном практической работы](https://github.com/java-online-course/spring-core-template){:target="_blank"}

Вопросы для самоконтроля
---------------------
1. Объясните суть паттерна DI
1. Что такое ApplicationContext?
1. Как пометить класс как Bean для Spring? В XML-based, Annotation-based, JavaConfig и GroovyConfig?
1. Как “заинжектить” Bean в поле другого Bean? В XML-based, Annotation-based, JavaConfig и GroovyConfig? Возможно ли заинжектить Bean в обычный класс?
1. Что такое “ленивая инициализация” бина?
1. Что такое singleton scope? Что такое prototype scope?
1. Перечислите виды callbacks в процессе инициализации/уничтожения Spring Bean, назовите назначение?
1. Для чего нужна аннотация @Required?
1. К чему применяется аннотация @Autowired? @Inject?
1. Spring stereotype аннотации включают в себя аннотации @Component, @Service и другие. Каково отличие между ними?
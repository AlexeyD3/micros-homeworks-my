# Домашнее задание к занятию «Введение в микросервисы»

## Задача

Руководство крупного интернет-магазина, у которого постоянно растёт пользовательская база и количество заказов, рассматривает возможность переделки своей внутренней   ИТ-системы на основе микросервисов. 

Вас пригласили в качестве консультанта для оценки целесообразности перехода на микросервисную архитектуру. 

Опишите, какие выгоды может получить компания от перехода на микросервисную архитектуру и какие проблемы нужно решить в первую очередь.


##Решение
Выгоды:

* Правильно примененная архитектура микросервисов снижает зависимость между компонентами, делая систему распределенной и отказоустойчивой, нарушения в работе одного из сервисов не влекут за собой полную потерю работоспособности.

* Возможности оперативного горизонтального масштабирования и балансировки системы именно по тем сервисам и бизнес-процессам, которые наиболее востребованы в конкретный временной интервал. 

* Возможность использования различных языков программирования и технологий, в зависимости от требований к конкретному микросервису.

* Возможность более гибко, сравнении с монолитной архитектурой, добавлять сложный функционал за счет разработки новых сервисов.

* Возможность делать более частые релизы, быстрее и проще тестировать, что в свою очередь означает более быстрое добавление функционала или фикс ошибок по отдельным сервисам.

* За счет повторения сервисами структуры коммуникации организации, позволяет создать более гармоничную систему и разделить команды на разные сервисы с разными задачами и бизнес целями.

Проблемы:

* Тяжело применить архитектуру с нуля. На начальном этапе монолитная архитектура более выгодна и её легче поддерживать. По мере роста системы и понимания границ контекстов будет проще разделить систему на микросервисы, чем делить то, что пока не создано.

* Ключевым моментом является определение цели и выгод для конкретного проекта от применения микросервисной архитектуры.

* При неправильном дроблении на сервисы можно превратить основные плюсы микросервисной системы в минусы. Усложнить систему, усугубить процесс выкладки, усложнить дебаг и исправление ошибок.

* Придется решать организационные вопросы и разделять существующую команду на части, каждая из которых будет действовать в зоне разработки своего сервиса.

* Необходимо будет повышать квалификацию инженеров и разработчиков, их обязанностей, более ответственно подходить к документированию, версионированию.

* Для продуктивной работы еще больше обостряется необходимость в DevOps подходе и использовании agile-методик.

* Необходимо применение полноценной системы сбора и анализа метрик, логов.
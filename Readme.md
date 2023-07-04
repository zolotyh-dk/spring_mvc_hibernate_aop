# CRUD с использованием Spring MVC, Hibernate, AOP

WEB приложение позволяющее совершать основные CRUD операции c объектами entity класса.
В качестве БД используется MySQL 8.

Архитектура приложения построена на шаблоне MVC:
* view - jsp страницы
* controller
* service
* DAO repository

Для реализации логгирования методов DAO применяется AspectJ

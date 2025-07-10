# Проект: Платформа Фриланса "Умный борд"
"Умный борд" — это пет-проект платформы для фриланса. Основная цель — создать масштабируемое, прозрачное и надёжное решение для взаимодействия фрилансеров и заказчиков, используя принципы микросервисной архитектуры.

В ходе проекта я продемонстрировала свои компетенции, охватывая полный цикл аналитической проработки:

- Комплексная проработка требований: От бизнес-целей до детализации функциональных и нефункциональных требований, анализа пользователей, юз-кейсов и написания тест-кейсов. Вся документация по требованиям, включая бизнес-цели, классы пользователей, юз-кейсы, юзер-стори, функциональные, нефункциональные требования и тест-кейсы.
- Архитектурное проектирование и интеграции: Декомпозиция системы на 10+ микросервисов с их зонами ответственности. Проектирование API-контрактов (основа для Swagger/OpenAPI) и детальное описание сценариев обмена сообщениями (REST API, RabbitMQ). Визуализация архитектуры выполнена с помощью UML-диаграмм (контекст, синхронные и асинхронные взаимодействия) в Draw.io и PlantUML. Применение Postman для тестирования API также учтено.
- Моделирование и хранение данных: Проектирование логических моделей баз данных для каждого микросервиса (сущности, атрибуты, связи) с акцентом на принцип Data Ownership. Для описания схем использовался DBML, а ER-диаграммы генерировались в DB Diagram. Все схемы данных прошли проверку на консистентность.


## Артефакты Проекта

*   [1. Business context.md](/petprojects/FreelanceHub/docs/1.%20Business%20context.md) (Бизнес-контекст, цели и ограничения проекта)
*   [2. Bysiness Requirements.md](/petprojects/FreelanceHub/docs/2.%20Bysiness%20Requirements.md) (Детальные бизнес-требования)
*   [3. Functional Requirements.md](/petprojects/FreelanceHub/docs/3.%20Functional%20Requirements.md) (Полный набор функциональных требований системы)
*   [4. User roles.md](/petprojects/FreelanceHub/docs/4.%20User%20roles.md) (Определение классов пользователей и их ролей)
*   [5. Userstories.md](/petprojects/FreelanceHub/docs/5.%20Userstories.md) (Пользовательские истории для всех ролей)
*   [6. Use case Freelancer.md](/petprojects/FreelanceHub/docs/6.%20Use%20case%20Freelancer.md) (Юз-кейсы для роли "Фрилансер")
*   [7. Use Case Customer.md](/petprojects/FreelanceHub/docs/7.%20Use%20case%20Customer.md) (Юз-кейсы для роли "Заказчик")
*   [8. Use case Tech Support.md](/petprojects/FreelanceHub/docs/8.%20Use%20case%20Tech%20Support.md) (Юз-кейсы для роли "Сотрудник службы поддержки")
*   [9. Use case Admin.md](/petprojects/FreelanceHub/docs/9.%20Use%20case%20Admin.md) (Юз-кейсы для роли "Администратор платформы")
*   [10. Non-functional Requirements.md](/petprojects/FreelanceHub/docs/10.%20Non-functional%20Requirements.md) (Нефункциональные требования: производительность, безопасность, надежность)
*   [11. Microservices.md](/petprojects/FreelanceHub/docs/11.%20Microservices.md) (Список и зоны ответственности 10+ микросервисов)
*   [12. Actors and connections.md](/petprojects/FreelanceHub/docs/12.%20Actors%20and%20connections.md) (Взаимосвязи акторов с микросервисами)
*   [13. Integrations.md](/petprojects/FreelanceHub/docs/13.%20Integrations.md) (Типы взаимодействий и детализированные сценарии обмена сообщениями между микросервисами по REST API и через RabbitMQ)
*   [14. Test cases.md](/petprojects/FreelanceHub/docs/14.%20Test%20cases.md) (Разработанные тест-кейсы на основе юз-кейсов и функциональных требований, включая сценарии для Postman)
*   [15. Entities and their attributes.md](/petprojects/FreelanceHub/docs/15.%20Entities%20and%20their%20attributes.md) (Описание сущностей и их атрибутов для каждой базы данных микросервиса)
*   [16. Microservices and their Core Data Entities.md](/petprojects/FreelanceHub/blob/main/docs/16.%20Microservices%20and%20their%20Core%20Data%20Entities.md) (Краткий обзор сущностей, принадлежащих каждому микросервису)
*   [17. Data Storage Process Flow.md](/petprojects/FreelanceHub/docs/17.%20Data%20Storage%20Process%20Flow.md) (Текстовое описание потоков данных между микросервисами и их хранилищами)
*   [18. Events RabbitMQ.md](/petprojects/FreelanceHub/docs/18.%20Events%20RabbitMQ.md) (Детализация типов событий, публикуемых и потребляемых через RabbitMQ)

## Визуализации

*   [Microservices Sync UML.png](/petprojects/FreelanceHub/diagrams/Microservices%20Sync%20UML.png) (UML Диаграмма: Детальные синхронные взаимодействия между микросервисами по REST API)
*   [Microservices Async (RabbitMQ) UML.png](/petprojects/FreelanceHub/diagrams/Microservices%20Async%20(RabbitMQ)%20UML.png) (UML Диаграмма: Детальные асинхронные взаимодействия через RabbitMQ)
*   [Admin Service DB.jpg](/petprojects/FreelanceHub/diagrams/Admin%20Service%20DB.jpg) (ER-диаграмма базы данных Admin Service, спроектирована с помощью DBML)
*   [Analytics & Reporting Service DB.jpg](/petprojects/FreelanceHub/diagrams/Analytics%20&%20Reporting%20ServiceDB.jpg) (ER-диаграмма базы данных Analytics & Reporting Service, спроектирована с помощью DBML)
*   [Authentication & Authorization Service DB.jpg](/petprojects/FreelanceHub/diagrams/Authentication%20&%20Authorization%20Service%20DB.jpg) (ER-диаграмма базы данных Authentication & Authorization Service, спроектирована с помощью DBML)
*   [Messenger Service DB.jpg](/petprojects/FreelanceHub/diagrams/Messenger%20Service%20DB.jpg) (ER-диаграмма базы данных Messenger Service, спроектирована с помощью DBML)
*   [Notification Service DB.jpg](/petprojects/FreelanceHub/diagrams/Notification%20Service%20DB.jpg) (ER-диаграмма базы данных Notification Service, спроектирована с помощью DBML)
*   [Order & Project Service DB.jpg](/petprojects/FreelanceHub/diagrams/Order%20&%20Project%20Service%20DB.jpg) (ER-диаграмма базы данных Order & Project Service, спроектирована с помощью DBML)
*   [Payment Service DB.jpg](/petprojects/FreelanceHub/diagrams/Payment%20Service%20DB.jpg) (ER-диаграмма базы данных Payment Service, спроектирована с помощью DBML)

---

## 🛠️ **Используемые Инструменты, Нотации и Технологии**

*   **Документация:** Markdown
*   **Нотации и Диаграммы:**
    *   UML (Unified Modeling Language): Use Case Diagrams, Component Diagrams
    *   ERD (Entity-Relationship Diagrams)
    *   DBML (Database Markup Language) для описания схем БД
*   **Инструменты:**
    *   Draw.io (diagrams.net) - для UML-диаграмм
    *   dbdiagram.io - для ER-диаграмм
    *   PlantUML - для демонстрации "диаграмм как код"
    *   Postman - для концептуального тестирования API-интерфейсов
    *   Swagger/OpenAPI - для концептуального проектирования API-контрактов
*   **Архитектурные паттерны:** Микросервисы, REST API, Событийная архитектура (Event-Driven Architecture)
*   **Брокер сообщений:** RabbitMQ

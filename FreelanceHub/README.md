# Проект: Платформа Фриланса "Умный борд"
"Умный борд" — это пет-проект платформы для фриланса. Основная цель — создать масштабируемое, прозрачное и надёжное решение для взаимодействия фрилансеров и заказчиков, используя принципы микросервисной архитектуры.

В ходе проекта я продемонстрировала свои компетенции, охватывая полный цикл аналитической проработки:

- Комплексная проработка требований: От бизнес-целей до детализации функциональных и нефункциональных требований, анализа пользователей, юз-кейсов и написания тест-кейсов. Вся документация по требованиям, включая бизнес-цели, классы пользователей, юз-кейсы, юзер-стори, функциональные, нефункциональные требования и тест-кейсы.
- Архитектурное проектирование и интеграции: Декомпозиция системы на 10+ микросервисов с их зонами ответственности. Проектирование API-контрактов (основа для Swagger/OpenAPI) и детальное описание сценариев обмена сообщениями (REST API, RabbitMQ). Визуализация архитектуры выполнена с помощью UML-диаграмм (контекст, синхронные и асинхронные взаимодействия) в Draw.io и PlantUML. Применение Postman для тестирования API также учтено.
- Моделирование и хранение данных: Проектирование логических моделей баз данных для каждого микросервиса (сущности, атрибуты, связи) с акцентом на принцип Data Ownership. Для описания схем использовался DBML, а ER-диаграммы генерировались в DB Diagram. Все схемы данных прошли проверку на консистентность.


## Артефакты Проекта

*   [1.Business_context.md](docs/1.Business_context.md) (Бизнес-контекст, цели и ограничения проекта)
*   [2.Bysiness_Requirements.md](docs/2.Bysiness_Requirements.md) (Детальные бизнес-требования)
*   [3.Functional_Requirements.md](docs/3.Functional_Requirements.md) (Полный набор функциональных требований системы)
*   [4.User_roles.md](docs/4.User_roles.md) (Определение классов пользователей и их ролей)
*   [5.Userstories.md](docs/5.Userstories.md) (Пользовательские истории для всех ролей)
*   [6.Use_case_Freelancer.md](docs/6.Use_case_Freelancer.md) (Юз-кейсы для роли "Фрилансер")
*   [7.Use_case_Customer.md](docs/7.Use_case_Customer.md) (Юз-кейсы для роли "Заказчик")
*   [8.Use_case_Tech_Support.md](docs/8.Use_case_Tech_Support.md) (Юз-кейсы для роли "Сотрудник службы поддержки")
*   [9.Use_case_Admin.md](docs/9.Use_case_Admin.md) (Юз-кейсы для роли "Администратор платформы")
*   [10.Non-functional_Requirements.md](docs/10.Non-functional_Requirements.md) (Нефункциональные требования: производительность, безопасность, надежность)
*   [11.Microservices.md](docs/11.Microservices.md) (Список и зоны ответственности 10+ микросервисов)
*   [12.Actors_and_connections.md](docs/12.Actors_and_connections.md) (Взаимосвязи акторов с микросервисами)
*   [13.Integrations.md](docs/13.Integrations.md) (Типы взаимодействий и детализированные сценарии обмена сообщениями между микросервисами по REST API и через RabbitMQ)
*   [14.Test_cases.md](docs/14.Test_cases.md) (Разработанные тест-кейсы на основе юз-кейсов и функциональных требований, включая сценарии для Postman)
*   [15.Entities_and_their_attributes.md](docs/15.Entities_and_their_attributes.md) (Описание сущностей и их атрибутов для каждой базы данных микросервиса)
*   [16.Microservices_and_their_Core_Data_Entities.md](docs/16.Microservices_and_their_Core_Data_Entities.md) (Краткий обзор сущностей, принадлежащих каждому микросервису)
*   [17.Data_Storage_Process_Flow.md](docs/17.Data_Storage_Process_Flow.md) (Текстовое описание потоков данных между микросервисами и их хранилищами)
*   [18.Events_RabbitMQ.md](docs/18.Events_RabbitMQ.md) (Детализация типов событий, публикуемых и потребляемых через RabbitMQ)

## Визуализации

*   [Microservices_Sync_UML.png](diagrams/Microservices_Sync_UML.png) (UML Диаграмма: Детальные синхронные взаимодействия между микросервисами по REST API)
*   [Microservices_Async_(RabbitMQ)_UML.png](diagrams/Microservices_Async_(RabbitMQ)_UML.png) (UML Диаграмма: Детальные асинхронные взаимодействия через RabbitMQ)
*   [Admin_Service_DB.jpg](diagrams/Admin_Service_DB.jpg) (ER-диаграмма базы данных Admin Service, спроектирована с помощью DBML)
*   [Analytics&Reporting_Service_DB.jpg](diagrams/Analytics&Reporting_Service_DB.jpg) (ER-диаграмма базы данных Analytics & Reporting Service, спроектирована с помощью DBML)
*   [Authentication&Authorization_Service_DB.jpg](diagrams/Authentication&Authorization_Service_DB.jpg) (ER-диаграмма базы данных Authentication & Authorization Service, спроектирована с помощью DBML)
*   [Messenger_Service_DB.jpg](diagrams/Messenger_Service_DB.jpg) (ER-диаграмма базы данных Messenger Service, спроектирована с помощью DBML)
*   [Notification_Service_DB.jpg](diagrams/Notification_Service_DB.jpg) (ER-диаграмма базы данных Notification Service, спроектирована с помощью DBML)
*   [Order&Project_Service_DB.jpg](diagrams/Order&Project_Service_DB.jpg) (ER-диаграмма базы данных Order & Project Service, спроектирована с помощью DBML)
*   [Payment_Service_DB.jpg](diagrams/Payment%20Service%20DB.jpg) (ER-диаграмма базы данных Payment Service, спроектирована с помощью DBML)
*   [Roles&Permissions_Service_DB.jpg](diagrams/Roles&Permissions_Service_DB.jpg) (ER-диаграмма базы данных Roles & Permissions Service, спроектирована с помощью DBML)
*   [Support&Dispute_Service_DB.jpg](diagrams/Support&Dispute_Service_DB.jpg) (ER-диаграмма базы данных Support & Dispute Service, спроектирована с помощью DBML)
*   [System_Context&Major_Blocks_UML.png](diagrams/System_Context&Major_Blocks_UML.png) (UML Диаграмма: Системный контекст и основные блоки)
*   [User&Profile_Service_DB.jpg](diagrams/User&Profile_Service_DB.jpg) (ER-диаграмма базы данных User & Profile Service, спроектирована с помощью DBML)
---

##  **Используемые Инструменты, Нотации и Технологии**

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

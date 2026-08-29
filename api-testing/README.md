# API Testing

This folder contains a practical REST API testing project created using Postman and the DummyJSON public API.

## Postman Collection

`DummyJSON-QA-Portfolio.postman_collection.json`

The collection contains positive and negative API test scenarios for products and authentication.

## Products

- GET existing product
- GET non-existent product
- POST create product
- PATCH partial product update
- PUT product update
- DELETE product

## Authentication

- Successful user login
- Get authenticated user
- Login with an invalid password
- Login with a non-existent user
- Request without an access token
- Request with an expired token
- Request with an invalid token

## Response Validation

Postman scripts are used to verify:

- HTTP status codes
- Response fields
- Response values
- Data types
- Error messages
- Resource IDs
- Successful delete state

## Authorization

The login request automatically saves the `accessToken` to a Postman collection variable.

The token can then be reused in authorized requests using:

`{{accessToken}}`

## Technologies and Concepts

- Postman
- REST API
- JSON
- GET / POST / PUT / PATCH / DELETE
- HTTP Status Codes
- Bearer Token Authorization
- Positive Testing
- Negative Testing
- Basic API Test Automation

## Important Note

DummyJSON simulates POST, PUT, PATCH, and DELETE operations. Modified data is returned in the response but is not permanently stored on the server.

All examples were created for training and QA portfolio purposes.

No confidential information from commercial projects is included.

---

# Тестирование API

В этой папке представлен практический проект по тестированию REST API, созданный с использованием Postman и публичного API DummyJSON.

## Коллекция Postman

`DummyJSON-QA-Portfolio.postman_collection.json`

Коллекция содержит позитивные и негативные сценарии тестирования API для товаров и авторизации.

## Товары

- GET существующего товара
- GET несуществующего товара
- POST создания товара
- PATCH частичного изменения товара
- PUT изменения товара
- DELETE удаления товара

## Авторизация

- Успешная авторизация пользователя
- Получение данных авторизованного пользователя
- Авторизация с неверным паролем
- Авторизация несуществующего пользователя
- Запрос без токена доступа
- Запрос с истёкшим токеном
- Запрос с невалидным токеном

## Проверка ответов

В Postman используются скрипты для проверки:

- HTTP-кодов ответа
- Наличия полей
- Значений полей
- Типов данных
- Сообщений об ошибках
- ID ресурсов
- Признака успешного удаления

## Авторизация и токены

После успешного Login-запроса `accessToken` автоматически сохраняется в переменную коллекции Postman.

В последующих авторизованных запросах токен можно использовать через:

`{{accessToken}}`

## Используемые технологии и знания

- Postman
- REST API
- JSON
- GET / POST / PUT / PATCH / DELETE
- HTTP Status Codes
- Bearer Token Authorization
- Позитивное тестирование
- Негативное тестирование
- Базовая автоматизация API-проверок

## Важное примечание

DummyJSON имитирует операции POST, PUT, PATCH и DELETE. Изменённые данные возвращаются в ответе, но не сохраняются на сервере постоянно.

Все примеры созданы исключительно для обучения и QA-портфолио.

Конфиденциальная информация из коммерческих проектов не используется.

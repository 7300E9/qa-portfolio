# TC-001: User registration with valid data

## Preconditions

The "Registration" section is open.

## Test Data

| Field | Value |
|---|---|
| Name | Valid value, for example `Andrey` |
| Email | Unique valid Email in the `name@example.com` format |
| Password | Valid password containing at least 8 characters |
| Confirm Password | Same value as the Password |

## Steps and Expected Results

| # | Step | Expected Result |
|---|---|---|
| 1 | Fill in all required fields with valid test data | All fields are filled in. No validation errors are displayed |
| 2 | Tap the "Register" button | Registration is completed successfully. The user is automatically logged in and redirected to the Home page |
| 3 | Check the Header | The registered user's name is displayed in the Header |

---

# TC-001: Регистрация пользователя с валидными данными

## Предусловие

Открыт раздел «Регистрация».

## Тестовые данные

| Поле | Значение |
|---|---|
| Имя | Валидное значение, например `Andrey` |
| Email | Уникальный валидный Email формата `name@example.com` |
| Пароль | Валидный пароль длиной не менее 8 символов |
| Повтор пароля | Значение совпадает с паролем |

## Шаги и ожидаемые результаты

| № | Шаг | Ожидаемый результат |
|---|---|---|
| 1 | Заполнить все обязательные поля валидными тестовыми данными | Все поля заполнены. Ошибки валидации не отображаются |
| 2 | Тапнуть на кнопку «Зарегистрироваться» | Регистрация выполняется успешно. Пользователь автоматически авторизуется и переходит на главную страницу |
| 3 | Обратить внимание на Header — шапку сайта | В Header отображается имя зарегистрированного пользователя |

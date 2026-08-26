# TC-002: User registration with an invalid Email

## Preconditions

The "Registration" section is open.

## Test Data

| Field | Value |
|---|---|
| Name | Valid value |
| Email | `test@` |
| Password | Valid password containing at least 8 characters |
| Confirm Password | Same value as the Password |

## Steps and Expected Results

| # | Step | Expected Result |
|---|---|---|
| 1 | Fill in all fields using the test data | The Email field is highlighted as invalid. The "Enter a valid Email" message is displayed below the field. The "Register" button remains active |
| 2 | Tap the "Register" button | Registration is not completed. The user remains on the Registration page. The Email validation error remains displayed |

---

# TC-002: Регистрация пользователя с некорректным значением в поле «Email»

## Предусловие

Открыт раздел «Регистрация».

## Тестовые данные

| Поле | Значение |
|---|---|
| Имя | Валидное значение |
| Email | `test@` |
| Пароль | Валидный пароль длиной не менее 8 символов |
| Повтор пароля | Значение совпадает с паролем |

## Шаги и ожидаемые результаты

| № | Шаг | Ожидаемый результат |
|---|---|---|
| 1 | Заполнить все поля тестовыми данными | Поле «Email» визуально выделяется как ошибочное. Под полем отображается сообщение «Введите корректный Email». Кнопка «Зарегистрироваться» остаётся активной |
| 2 | Тапнуть на кнопку «Зарегистрироваться» | Регистрация не выполняется. Пользователь остаётся на странице регистрации. Ошибка в поле «Email» продолжает отображаться |

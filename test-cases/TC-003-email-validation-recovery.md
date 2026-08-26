# TC-003: Email validation error disappears after correcting the value

## Preconditions

The "Registration" section is open.

## Test Data

| Field | Value |
|---|---|
| Name | Valid value, for example `Andrey` |
| Email | `test@`, then a unique valid Email |
| Password | Valid password containing at least 8 characters |
| Confirm Password | Same value as the Password |

## Steps and Expected Results

| # | Step | Expected Result |
|---|---|---|
| 1 | Fill in all fields using `test@` in the Email field | The Email field is highlighted as invalid. The "Enter a valid Email" message is displayed. The "Register" button remains active |
| 2 | Tap the "Register" button | Registration is not completed. The user remains on the Registration page and the Email validation error remains displayed |
| 3 | Replace `test@` with a unique valid Email | The visual error state and validation message disappear. The "Register" button remains active |
| 4 | Tap the "Register" button | Registration is completed successfully. The user is redirected to the Home page |

---

# TC-003: Исчезновение ошибки валидации после исправления Email

## Предусловие

Открыт раздел «Регистрация».

## Тестовые данные

| Поле | Значение |
|---|---|
| Имя | Валидное значение, например `Andrey` |
| Email | `test@`, затем уникальный валидный Email |
| Пароль | Валидный пароль длиной не менее 8 символов |
| Повтор пароля | Значение совпадает с паролем |

## Шаги и ожидаемые результаты

| № | Шаг | Ожидаемый результат |
|---|---|---|
| 1 | Заполнить все поля, используя `test@` в поле «Email» | Поле «Email» визуально выделяется как ошибочное. Отображается сообщение «Введите корректный Email». Кнопка «Зарегистрироваться» остаётся активной |
| 2 | Тапнуть на кнопку «Зарегистрироваться» | Регистрация не выполняется. Пользователь остаётся на странице регистрации. Ошибка Email продолжает отображаться |
| 3 | Заменить `test@` на уникальный валидный Email | Визуальное выделение поля как ошибочного и сообщение об ошибке исчезают. Кнопка «Зарегистрироваться» остаётся активной |
| 4 | Тапнуть на кнопку «Зарегистрироваться» | Регистрация выполняется успешно. Пользователь переходит на главную страницу |

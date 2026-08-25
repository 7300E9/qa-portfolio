# BUG-005: User registration succeeds with an invalid email address

## Preconditions

The "Registration" section is open. All required fields except "Email" are filled with valid data.

## Steps to Reproduce

1. Enter `test@` in the "Email" field.
2. Tap the "Register" button.

## Actual Result

The user is successfully registered with the email address `test@`.

## Expected Result

Registration should not be completed. The value `test@` should not be accepted as a valid email address according to the requirements.

## Bug Type

Functional Bug / Validation Bug

---

# BUG-005: Выполняется регистрация пользователя с некорректным значением в поле «Email»

## Предусловия

Открыт раздел «Регистрация». Все обязательные поля, кроме «Email», заполнены валидными данными.

## Шаги воспроизведения

1. Ввести в поле «Email» значение `test@`.
2. Тапнуть на кнопку «Зарегистрироваться».

## Фактический результат

Пользователь успешно регистрируется с Email `test@`.

## Ожидаемый результат

Регистрация не выполняется. Значение `test@` не принимается как корректное значение поля «Email» согласно требованиям.

## Тип дефекта

Функциональный дефект / ошибка валидации

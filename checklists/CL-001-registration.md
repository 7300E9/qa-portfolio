# CL-001: User Registration Checklist

## Positive Checks

* [ ] Register a user with valid data
* [ ] Register a user using a unique valid Email
* [ ] Correct an invalid Email and complete registration successfully
* [ ] Verify that validation errors disappear after invalid data is corrected

## Required Fields

* [ ] Attempt registration with all required fields empty
* [ ] Verify validation errors for incorrectly filled required fields

## Email Validation

* [ ] Enter an Email without the `@` symbol
* [ ] Enter an Email without a domain part, for example `test@`
* [ ] Enter an Email with two `@` symbols
* [ ] Attempt registration using an already registered Email

## Password Validation

* [ ] Enter different values in the "Password" and "Confirm Password" fields
* [ ] Check the minimum password boundary: 7, 8, and 9 characters
* [ ] Check the maximum password boundary: 19, 20, and 21 characters
* [ ] Enter only special characters in the Password field if password composition restrictions are specified in the requirements

## Form Behavior

* [ ] Verify registration after correcting validation errors
* [ ] Double-tap the "Register" button quickly and verify that duplicate registration is not performed

---

# CL-001: Чек-лист регистрации пользователя

## Позитивные проверки

* [ ] Регистрация пользователя с валидными данными
* [ ] Регистрация с использованием уникального валидного Email
* [ ] Исправление некорректного Email на валидный с последующей успешной регистрацией
* [ ] Исчезновение ошибок валидации после исправления невалидных данных

## Обязательные поля

* [ ] Попытка регистрации со всеми пустыми обязательными полями
* [ ] Отображение ошибок валидации при некорректном заполнении обязательных полей

## Валидация Email

* [ ] Ввод Email без символа `@`
* [ ] Ввод Email без доменной части, например `test@`
* [ ] Ввод Email с двумя символами `@`
* [ ] Регистрация с уже существующим Email

## Валидация пароля

* [ ] Ввод разных значений в поля «Пароль» и «Повтор пароля»
* [ ] Проверка минимальной границы длины пароля: 7, 8 и 9 символов
* [ ] Проверка максимальной границы длины пароля: 19, 20 и 21 символ
* [ ] Ввод только специальных символов в поле «Пароль», если требования содержат ограничения на состав пароля

## Поведение формы

* [ ] Регистрация после исправления ошибок валидации
* [ ] Быстрый двойной тап по кнопке «Зарегистрироваться» и проверка отсутствия дублирующей регистрации

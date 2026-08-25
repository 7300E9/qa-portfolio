# BUG-004: Discount is not recalculated after increasing the product quantity in the cart

## Preconditions

The user is logged in. One product priced at 3,000 RUB has been added to the cart. The "Cart" section is open.

## Steps to Reproduce

1. Enter the valid promo code `SALE10` in the "Promo Code" field.
2. Tap the "Apply" button.
3. Check the discount amount.
4. Increase the quantity of the product from 1 to 2.
5. Check the discount amount.

## Actual Result

When the total product price is 6,000 RUB, the discount remains 300 RUB.

## Expected Result

The discount should be automatically recalculated according to the specification after changing the product quantity.

> According to the requirements, the `SALE10` promo code provides a 10% discount on the total price of all products in the cart.

## Bug Type

Functional Bug / Business Logic Bug

---

# BUG-004: Отсутствует перерасчёт скидки при увеличении количества товара в корзине

## Предусловия

Пользователь авторизован. В корзину добавлен товар стоимостью 3 000 ₽ в количестве 1 шт. Открыт раздел «Корзина».

## Шаги воспроизведения

1. В поле «Промокод» ввести действующий промокод `SALE10`.
2. Тапнуть на кнопку «Применить».
3. Обратить внимание на размер скидки.
4. Увеличить количество ранее добавленного товара с 1 до 2 шт.
5. Обратить внимание на размер скидки.

## Фактический результат

При общей стоимости товаров 6 000 ₽ размер скидки остаётся 300 ₽.

## Ожидаемый результат

Размер скидки автоматически пересчитывается согласно спецификации после изменения количества товара.

> Согласно требованиям, промокод `SALE10` предоставляет скидку 10% на полную стоимость всех товаров в корзине.

## Тип дефекта

Функциональный дефект / ошибка бизнес-логики

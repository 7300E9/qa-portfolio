# BUG-001: Incorrect cart total after adding the same product twice

## Preconditions

A product priced at 100 RUB has been added to the cart in quantity of 1.

## Steps to Reproduce

1. Add the same product to the cart again.
2. Open the "Cart" section.
3. Check the product quantity and the total price.

## Actual Result

The cart contains 2 units of the product, but the total price is 100 RUB.

## Expected Result

For a product priced at 100 RUB with a quantity of 2, the total price should be 200 RUB.

## Bug Type

Functional Bug

---

# BUG-001: Неверная итоговая стоимость при повторном добавлении одного и того же товара

## Предусловия

В корзину добавлен товар стоимостью 100 ₽ в количестве 1 шт.

## Шаги воспроизведения

1. Повторно добавить тот же товар в корзину.
2. Перейти в раздел «Корзина».
3. Обратить внимание на количество товара и итоговую стоимость.

## Фактический результат

В корзине отображается товар в количестве 2 шт., итоговая стоимость составляет 100 ₽.

## Ожидаемый результат

При стоимости товара 100 ₽ и количестве 2 шт. итоговая стоимость составляет 200 ₽.

## Тип дефекта

Функциональный дефект

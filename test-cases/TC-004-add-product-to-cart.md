# TC-004: Adding an available product to the cart

## Preconditions

The "Catalog" section is open. The cart is empty.

## Test Data

No specific test data is required. Any product with the "In Stock" status can be used.

## Steps and Expected Results

| # | Step | Expected Result |
|---|---|---|
| 1 | Add any product with the "In Stock" status to the cart | The product is added to the cart. The cart counter increases from 0 to 1 |
| 2 | Open the "Cart" section | The previously added product is displayed in the cart in quantity of 1. The product name and price correspond to the information displayed in the Catalog. The total price corresponds to the price of one unit of the added product according to the current pricing rules |

---

# TC-004: Добавление товара, доступного в наличии, в корзину

## Предусловие

Открыт раздел «Каталог». Корзина пуста.

## Тестовые данные

Конкретные тестовые данные не требуются. Можно использовать любой товар со статусом «В наличии».

## Шаги и ожидаемые результаты

| № | Шаг | Ожидаемый результат |
|---|---|---|
| 1 | Добавить в корзину любой товар со статусом «В наличии» | Товар добавлен в корзину. Счётчик товаров возле иконки корзины изменяется с 0 на 1 |
| 2 | Перейти в раздел «Корзина» | Ранее добавленный товар отображается в корзине в количестве 1 шт. Название и стоимость товара соответствуют данным в каталоге. Итоговая стоимость соответствует стоимости одной единицы добавленного товара с учётом действующих правил расчёта |

# BUG-006: Product with an unchecked checkbox is removed from the cart

## Preconditions

Two products have been added to the cart. The "Cart" section is open.

## Steps to Reproduce

1. Select the checkboxes for the first and second products.
2. Uncheck the checkbox for the first product.
3. Make sure that the first product is unchecked and the second product remains checked.
4. Tap the "Delete Selected" button.
5. Check the cart contents.

## Actual Result

Both products are removed, including the product with the unchecked checkbox.

## Expected Result

Only products with selected checkboxes at the moment the "Delete Selected" button is tapped should be removed.

## Bug Type

Functional Bug

---

# BUG-006: Удаляется товар со снятым чекбоксом в разделе «Корзина»

## Предусловия

В корзину добавлены два товара. Открыт раздел «Корзина».

## Шаги воспроизведения

1. Выбрать чекбоксы у первого и второго товара.
2. Снять выбор чекбокса у первого товара.
3. Убедиться, что чекбокс первого товара выключен, второго — включён.
4. Тапнуть на кнопку «Удалить выбранные».
5. Обратить внимание на содержимое корзины.

## Фактический результат

Удаляются оба товара, включая товар со снятым чекбоксом.

## Ожидаемый результат

Удаляются только товары с выбранными чекбоксами на момент нажатия кнопки «Удалить выбранные».

## Тип дефекта

Функциональный дефект

# BUG-002: Product outside the selected price range is displayed in the product list

## Preconditions

The product catalog page is open. A price filter from 1,000 to 5,000 RUB is applied.

## Steps to Reproduce

1. Check the displayed product list.

## Actual Result

A "TV" product priced at 12,000 RUB is displayed even though its price is outside the selected range.

## Expected Result

Only products priced from 1,000 to 5,000 RUB should be displayed.

## Bug Type

Functional Bug

## Test Design Techniques

- Equivalence Partitioning
- Boundary Value Analysis

---

# BUG-002: В списке товаров отображается товар за пределами установленного диапазона цены

## Предусловия

Открыта страница каталога товаров. Установлен фильтр по цене от 1 000 до 5 000 ₽.

## Шаги воспроизведения

1. Обратить внимание на список отображаемых товаров.

## Фактический результат

В списке отображается товар «Телевизор» стоимостью 12 000 ₽, который не входит в установленный диапазон.

## Ожидаемый результат

Отображаются только товары стоимостью от 1 000 до 5 000 ₽.

## Тип дефекта

Функциональный дефект

## Использованные техники тест-дизайна

- Эквивалентное разбиение
- Анализ граничных значений

# BUG-003: Saved notification setting is not preserved after reopening the section

## Preconditions

The user is logged in. The "Notification Settings" section is open.

## Steps to Reproduce

1. Switch the "Receive email notifications" toggle from ON to OFF.
2. Tap the "Save" button.
3. Make sure that the "Settings saved successfully" message is displayed and the toggle remains in the OFF state.
4. Open another section of the website.
5. Return to the "Notification Settings" section.
6. Check the toggle state.

## Actual Result

After reopening the section, the toggle is displayed in the ON state.

## Expected Result

After saving the settings and reopening the section, the toggle should remain in the OFF state.

## Bug Type

Functional Bug / State Persistence Issue

---

# BUG-003: Состояние настройки уведомлений не сохраняется после повторного открытия раздела

## Предусловия

Пользователь авторизован. Открыт раздел «Настройки уведомлений».

## Шаги воспроизведения

1. Переключить «Получать уведомления по email» из состояния ON в OFF.
2. Тапнуть на кнопку «Сохранить».
3. Убедиться, что отображается сообщение «Настройки успешно сохранены», а переключатель остаётся в состоянии OFF.
4. Перейти в другой раздел сайта.
5. Вернуться в раздел «Настройки уведомлений».
6. Обратить внимание на состояние переключателя.

## Фактический результат

После повторного открытия раздела переключатель отображается в состоянии ON.

## Ожидаемый результат

После сохранения настроек и повторного открытия раздела переключатель остаётся в состоянии OFF.

## Тип дефекта

Функциональный дефект / проблема сохранения состояния

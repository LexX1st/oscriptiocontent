# Отличия в работе команды Формат

## Доли секунды в дате

Для параметра `ДФ` добавлен формат `р` (кириллица) или `f` для отображения дробных частей секунды.
Пример:
```bsl
Строка = Формат(Дата, "ДФ=ЧЧ:мм:сс.ррр");
// Строка = "20:02:53.345"
```
Допускается указывать до 6 разрядов дробной части.

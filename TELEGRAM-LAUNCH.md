# Запуск Telegram Mini App

## Что уже подготовлено

В проекте есть отдельная точка входа для Telegram:

- `telemetry-telegram.html`
- `telemetry-prototype.html?entry=telegram`

Для обычного показа в браузере можно открывать:

```text
https://sib-cart.ru/telemetry-prototype.html
```

Для запуска как Telegram Mini App лучше использовать:

```text
https://sib-cart.ru/telemetry-telegram.html
```

## Что загрузить на GitHub Pages

Загружай содержимое папки `github-upload-ready` в корень репозитория:

```text
index.html
model-stl.html
telemetry-prototype.html
telemetry-telegram.html
assets/
CNAME
```

После публикации проверь, что открываются обе ссылки:

```text
https://sib-cart.ru/telemetry-prototype.html
https://sib-cart.ru/telemetry-telegram.html
```

## Настройка через BotFather

1. Открой Telegram и найди `@BotFather`.
2. Создай бота командой `/newbot`, если бот еще не создан.
3. Задай имя и username бота.
4. Открой настройки бота через `/mybots`.
5. Выбери своего бота.
6. Открой `Bot Settings`.
7. Открой `Menu Button`.
8. Выбери `Configure menu button`.
9. Вставь URL:

```text
https://sib-cart.ru/telemetry-telegram.html
```

10. Задай текст кнопки, например:

```text
Открыть телеметрию
```

## Как показывать другу

Отправь другу ссылку на бота. Внутри бота появится кнопка запуска приложения.

Если нужно открыть напрямую из сообщения, можно отправить ссылку:

```text
https://sib-cart.ru/telemetry-telegram.html
```

Лучший сценарий показа:

1. Открыть приложение.
2. Перейти в live-заезд.
3. Завершить сессию.
4. Открыть сравнение кругов.
5. Показать AI-анализ.
6. Перейти в командный центр.

## Важно

Telegram Mini App должен открываться по `https`. Локальные ссылки `file://` и `localhost` внутри Telegram не подходят для показа другим людям.

Продолжаем развивать игру из ДЗ-2 ит ДЗ-3
В этот раз выкладываем её на хероку в виде бота для телеграма

Можете начать с выкалдывания бота из примеров ( 4/06_bot ) и как убедитесь что всё получится - уже выкладывать остальное

Необходимо реализовать новые возможности:
* Если игрок ещё не записан в игре - он добавляется на кухню
* Если игрок не активен в течении 15 минут (не было сообщений-команд), то он удаляется из игры, если у него был инвентарь - он возвращается туда где был.
* У админа бота есть команда сброса игры - выкинуть всех игроков, вернуть предменты и замок в первоначальное состояние. Другим игрокам эта команда недоступна

В телеграме есть несколько вариантво ввода команд: настраиваемые кнопки на клавиатуре, инлайн-кнопки ( прямо в чате ), просто команды в чат. Реализовать можно любым способом.

Доп материалы:
Инструкция для раскладки на хероку:
* https://devcenter.heroku.com/articles/getting-started-with-go#introduction
Используемая нами библиотека для обработки телеграм сообщений:
* https://github.com/go-telegram-bot-api/telegram-bot-api/tree/v4.6
* https://godoc.org/gopkg.in/telegram-bot-api.v4
Документация телеграма по ботам:
* https://core.telegram.org/bots
* https://core.telegram.org/bots/api
* https://core.telegram.org/bots/faq
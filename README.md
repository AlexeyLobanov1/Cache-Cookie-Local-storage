# Cache, Cookie, Local storage - notes.

### Cache, Cookie, Local storage - table

| Тип кеша |	Что кешируется	| Преимущества	| Недостатки |
| :----------------- | :------------------ | :----------------- | :------------------ |
| Server cache	| Данные, которые часто запрашиваются и не обязательно должны быть актуальны |	Ускорение доступа к данным, уменьшение нагрузки на сервер	| Необходимость инвалидации старых данных при изменении или удалении |
| In-memory cache	| Кеш, который хранится в оперативной памяти сервера |	Очень быстрый доступ к данным, малая задержка при запросах | Нельзя хранить много данных, чистится при перезапуске сервера |
| Клиентский кеш	| Кеш в браузере	| Ускорение доступа к данным, уменьшение нагрузки на сервер |	Зависит от настроек браузера, не всегда актуальны, необходимость инвалидации старых данных |
| Куки	| Небольшой фрагмент данных, отправленный сервером и хранящийся на ПК |	Хранение информации о сеансе, персонализация, трекинг пользователей |	Необходимость инвалидации старых данных, возможность XSS атак |
| Local storage	| Хранилище данных ключ/значение без срока давности	| Удобство хранения и доступа к данным, данные не удаляются через время	| Не подходит для хранения конфиденциальных данных, необходимо управлять размером данных |
| Session storage	| Хранилище данных ключ/значение в рамках одной вкладки	| Удобство хранения и доступа к данным, данные не удаляются через время	| Данные сессии удаляются при закрытии вкладки или браузера |

![table](https://github.com/AlexeyLobanov1/Cache-Cookie-Local-storage/blob/main/table.jpg)

![example](https://github.com/AlexeyLobanov1/Cache-Cookie-Local-storage/blob/main/my.jpg)

Конфигурационынй файл: src/main/resources/application.properties
    project.keys.callback.confirmation - Ключ для подтверждения адреса для Callback API
    project.keys.callback.secret - Секртеный ключ Callback API
    project.keys.access_key - Ключ доступа для управления сообществом
Процесс запуска:
    1) Создаем ключ доступа в сообществе, предоставляя доступ к сообщениям сообщества
    2) Копируем ключ в project.keys.access_key
    3) Создаем сервер Callback API
    4) Указываем домен, по которому можно отправить запрос приложение
    5) Копируем строку, которую должен вернуть сервер при confirmation запросе в project.keys.callback.confirmation
    6) Задаем секретный ключ для Callback API, копируем его в project.keys.callback.secret и сохраняем сервер CallBack API
    7) Запускаем приложение
    8) На вкладке Callback API нажимаем подтвердить

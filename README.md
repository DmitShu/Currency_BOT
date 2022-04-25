# Telegram-бот для пересчета валют.

Бот возвращает цену на определённое количество валюты (евро, доллар или рубль).

Человек должен отправить сообщение боту в виде <имя валюты цену которой он хочет узнать> <имя валюты в которой надо узнать цену первой валюты> <количество первой валюты>.

При вводе команды /start или /help пользователю выводятся инструкции по применению бота.

При вводе команды /values выводится информация о всех доступных валютах в читаемом виде.

При ошибке пользователя (например, введена неправильная или несуществующая валюта или неправильно введено число) вызывается текст с пояснением ошибки.


bot_app.py - исполняемый файл бота
bot_config.py - здесь хранятся переменные
bot_extensions.py - здесь хранятся методы и классы
токен хранится в файле за пределами версионного контроля
(для тестов используйте свой)
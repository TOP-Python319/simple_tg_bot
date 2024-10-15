Устанавливаем библиотеки:
```
python -m pip install -r requirements.txt
```

Идём в телеграм и получаем токен для бота у `t.me/BotFather`
Идём в телеграм и получаем `id` чата у `t.me/GetMyChatID_Bot`

Создаём файл `.env` и вписываем туда токен и `id` чата,
взяв за основу переменные из `.env.example`

Запускаем с помощью команды:
```bash
python main.py
```
# TG-bait-bot

Бот с "балансом" для автоматической продажи фото/видео интимного характера и реферальной системой.

Внешний вид бота

![image](https://user-images.githubusercontent.com/108902105/177874329-cef37c26-077a-43a1-8ed0-7a42fd9cf59d.png)

Что нам понадобится?
Сам бот
Немного фантазии

Гайд на бота

НАСТРОЙКА

Запускаем файл install-modules.bat, чтобы установить все библиотеки

![image](https://user-images.githubusercontent.com/108902105/177874836-408407b7-610b-4405-8a62-e108e9bff876.png)

В папку photos закидываем фото

В папку videos закидываем видео (ограничения телеграма - до 50 Мб)

Открываем файл main.py любым текстовым редактором. В строках 11-18 находятся все настройки.

![image](https://user-images.githubusercontent.com/108902105/177874866-be7672eb-86b5-4bd9-90a1-45077a958bc2.png)

token - Токен от вашего бота в телеграме

admin_id - Ваш ID телеграма

admin_link - Ваша ссылка на телеграм

link - Ссылка на бота

video_cost - Стоимость 1 видео

photo_cost - Стоимость 1 фото

start_balance - Баланс пользователя при регистрации

bonus_ref - Бонус за регистрацию по реф-ссылке

ЗАПУСК

Запускаем файл main.py

Если вы все сделали правильно, вас встретит симпатичное окошко в консоли

![image](https://user-images.githubusercontent.com/108902105/177875002-b4938a76-47a3-4dbe-a12d-7ad994ad91de.png)

Симпатичное окошко не появилось? Делаем всё по новой

Чтобы сделать рассылку, пишем /send Текст

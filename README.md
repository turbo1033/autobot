# Autobot

Что делает бот? 
1 - Парсит канал Sena Live Calls на CA и mcap
2 - проверяет актуальную капу токена
3 - отправляет запрос на покупку токена или пропускает (если не подошло по диапазону капы)

## Важно:
Бот находится в режиме тестирования. Возможно будет обновляться. Не храните большие балансы на кошельке. DYOR. 

## С чего начать?
1 - Создайте аккаунт WL.bot https://app.wl.bot/?ref=WLBOT-ZUS78N и настройте по своей торговой стратегии 
2 - Установите Пайтон 3.10+ и любой обработчик кода (VScode, PyCharm, Cursor)
3 - Скачайте этот репозиторий
4 - Создайте виртуальное окружение открыв проект репозитория в любом обработчике кода
в терминале поочередно:
python3 -m venv venv
source venv/bin/activate  # Для Linux/macOS
venv\Scripts\activate     # Для Windows
5 - Установите зависимости 
в терминале:
pip install -r requirements.txt
6 - При любых вопросах используйте ChatGPT

## config

В файле config.py у вас есть все нужные вам настройки по работе софта.


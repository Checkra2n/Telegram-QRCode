# Telegram-QRCode
Telegram 已向开发者宣布北京时间 2023年2月18日21:00 后禁止第三方客户端通过短信进行登录/注册。

目前一些需要用验证码登录的TGbot，已经无法登录

通过此py文件可以获取TG登录后的session信息

使用方法：
通过 https://my.telegram.org 申请ID和HASH，将Py文件中的TELEGRAM_API_ID和TELEGRAM_API_HASH修改为自己的
pip install telethon
pip install qrcode
python3 user.py

就可以获取登录session。

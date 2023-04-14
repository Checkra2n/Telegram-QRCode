# Telegram-QRCode
此py文件可以获取TG登录后的session信息

使用方法：

通过 https://my.telegram.org 申请ID和HASH，将Py文件中的TELEGRAM_API_ID和TELEGRAM_API_HASH修改为自己的

pip install telethon

pip install qrcode

python3 user.py

就可以获取登录session。

注：35行的SessionName，可以修改成想要的session文件名

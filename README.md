# lab11

ngrok позволяет настроить подключение к сайту(установить безопасный канал) без трудностей хостинга и домена.

Для начала работы необходимо привязать свой аккаунт 
![image](https://user-images.githubusercontent.com/91755900/170583841-12f77193-5abd-4edc-adc0-9b6494502397.png)

Затем при создании сайта, при попытке подвключения к нему через любое утстройство подключенное к сети, подключения не произойдет. Тогда отличным решением станет ngrok.
Функционал позволяет провести туннель до сервера при помощи команды: ngrok tcp string(где string это номер порта)

Тогда образуется интерфейс где в пункте Forwarding вы получите ссылку для перехода на сайт с любого устройства

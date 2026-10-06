# ВМ и Анонимность
# ВМ
Установила Kali Linux на гипервизоре VMware
<img width="2760" height="1726" alt="image" src="https://github.com/user-attachments/assets/8935a3c8-0b52-44f9-a0ae-70a51fda4270" />


# Цифровой отпечаток

## Отпечаток до
Зашла на сайт https://amiunique.org 


<img width="2756" height="1150" alt="image" src="https://github.com/user-attachments/assets/68419c52-fba4-4cd3-8967-58af57bd3a4d" />

<img width="2724" height="902" alt="image" src="https://github.com/user-attachments/assets/139a26f2-7cb8-4124-b9af-024fd7e8470d" />

И также на сайт https://www.deviceinfo.me/

<img width="2538" height="1406" alt="image" src="https://github.com/user-attachments/assets/3981db0c-c6dc-4ed9-b7ab-2c374e30f550" />

Оба эти сайта позволяют установить ОС, ip адреса, параметры настройки моей ОС. Можно точно определить меня.

## Анонимизация
### Proxy Chaining и Tor
Обновила базу данных и нашла в ней файл `proxychains4.conf`. В файле изменила stric_chains на dynamic_chains и добавила ip-адрес в блок ProxyList
<img width="1552" height="494" alt="image" src="https://github.com/user-attachments/assets/8ca51ca1-a9b8-4fd1-8c40-4c8ba3293732" />

<img width="1452" height="654" alt="image" src="https://github.com/user-attachments/assets/1a3417b8-e53a-438e-a343-3bacb9c710e0" />

<img width="1434" height="1258" alt="image" src="https://github.com/user-attachments/assets/f591d626-c3a1-475a-99ff-9a458a1cb9e7" />

меня определило вот так

<img width="1888" height="1122" alt="image" src="https://github.com/user-attachments/assets/e1d89561-ad78-4ac6-8183-3d7051248f55" />

На другом сайте: 
<img width="2376" height="1358" alt="image" src="https://github.com/user-attachments/assets/03f3c826-f983-49b3-99fe-cf1276ce4b68" />

Но параметры для компьютера те же
<img width="2752" height="1168" alt="image" src="https://github.com/user-attachments/assets/b8747e9b-1d1a-4d6f-9ee6-a47d59b97724" />

Вывод: такой метод влияет на сетевой трафик (меняет динамически адреса), но не на браузер


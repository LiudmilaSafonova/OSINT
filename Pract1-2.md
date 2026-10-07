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

### Tor Browser
Скачала Tor Browser, распаковала его и применила
<img width="2758" height="1432" alt="image" src="https://github.com/user-attachments/assets/14b79190-cf86-47c4-95cc-1334dd4b4bec" />
<img width="2692" height="1518" alt="image" src="https://github.com/user-attachments/assets/2ff4cb26-0bcf-4467-ac0b-da684351ef41" />
<img width="2750" height="1522" alt="image" src="https://github.com/user-attachments/assets/80daeb8b-be1f-4422-addc-1ff67ae1b457" />
<img width="2760" height="1550" alt="image" src="https://github.com/user-attachments/assets/c1859e47-1b8d-438d-875f-3dcf0aacf175" />

### Brave Browser
С этим получаем уникальный фингерпринт и уникальную генерацию canvas
<img width="2302" height="776" alt="image" src="https://github.com/user-attachments/assets/c5525bd1-8989-4888-92ce-dad9e0cd5929" />
на device.me вся информация по моему устройству реальному. 

### Firefox

<img width="2774" height="728" alt="image" src="https://github.com/user-attachments/assets/32be6448-66dc-4ad7-b162-14018b3d14ad" />
изменила `privacy.resistFingerprinting` на true

<img width="2492" height="950" alt="image" src="https://github.com/user-attachments/assets/8b839ed3-6114-47ad-a5d4-5c62e9fe6fc9" />
<img width="2192" height="1252" alt="image" src="https://github.com/user-attachments/assets/846cea79-f378-469b-bbe5-80d68388e97f" />
на device.me вся информация по моему устройству реальному. 

<img width="1886" height="800" alt="image" src="https://github.com/user-attachments/assets/47a3cf4a-b145-415c-8c4b-2429dfa9077c" />

### User-Agent Switcher and Manager

<img width="2738" height="1362" alt="image" src="https://github.com/user-attachments/assets/9c04f504-25b7-43da-8664-0bcd5b2913a1" />
<img width="2718" height="1178" alt="image" src="https://github.com/user-attachments/assets/65adadea-87df-42be-88b1-b14c09e81971" />
<img width="1980" height="1266" alt="image" src="https://github.com/user-attachments/assets/75546ee8-9bea-41e2-add4-04930c8e5020" />
<img width="2444" height="1132" alt="image" src="https://github.com/user-attachments/assets/905805d1-f8cd-44fa-b417-5d37197e29d4" />

<img width="2414" height="840" alt="image" src="https://github.com/user-attachments/assets/701035ed-bf15-4508-b9b0-dabc40fc3ace" />
<img width="1718" height="1362" alt="image" src="https://github.com/user-attachments/assets/6ac381ad-71ae-4b08-8408-221643d6c3b6" />

время и ip-адрес мои


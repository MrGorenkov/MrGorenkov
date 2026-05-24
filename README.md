<h1 align="center">Александр Горенков</h1>

<p align="center">
  <i>Full-stack разработчик — iOS · Backend · Data Engineering</i>
</p>

<p align="center">
  <a href="mailto:sgrenkov39@gmail.com"><img src="https://img.shields.io/badge/email-D14836?style=flat-square&logo=gmail&logoColor=white" alt="Email"></a>
  <a href="https://t.me/MrGorenkov"><img src="https://img.shields.io/badge/Telegram-0088CC?style=flat-square&logo=telegram&logoColor=white" alt="Telegram"></a>
  <img src="https://img.shields.io/badge/Москва-РФ-blue?style=flat-square" alt="Moscow">
</p>

---

### О себе

Студент кафедры ИУ-5 («Системы обработки информации и управления») МГТУ им. Н. Э. Баумана. Выпуск — 2026 год, бакалавриат. Пишу клиент-серверные системы целиком: от iOS-приложений и веб-фронта до REST/WebSocket-серверов, реляционных моделей и развёртывания в Docker. Интересуюсь компьютерной графикой, дополненной реальностью и интеграцией с публичными блокчейн-сетями.

### Технологии

**Mobile**
![Swift](https://img.shields.io/badge/Swift-F05138?style=flat-square&logo=swift&logoColor=white)
![SwiftUI](https://img.shields.io/badge/SwiftUI-007AFF?style=flat-square&logo=swift&logoColor=white)
![UIKit](https://img.shields.io/badge/UIKit-2396F3?style=flat-square&logo=swift&logoColor=white)
![SceneKit](https://img.shields.io/badge/SceneKit-9333EA?style=flat-square&logo=apple&logoColor=white)
![ARKit](https://img.shields.io/badge/ARKit-000000?style=flat-square&logo=apple&logoColor=white)
![RealityKit](https://img.shields.io/badge/RealityKit-1A1A1A?style=flat-square&logo=apple&logoColor=white)
![Metal](https://img.shields.io/badge/Metal-FA0F00?style=flat-square&logo=apple&logoColor=white)

**Backend**
![Vapor](https://img.shields.io/badge/Vapor-4-7A4FFF?style=flat-square&logo=swift&logoColor=white)
![Django](https://img.shields.io/badge/Django-092E20?style=flat-square&logo=django&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-000000?style=flat-square&logo=flask&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white)
![REST](https://img.shields.io/badge/REST-API-orange?style=flat-square)
![WebSocket](https://img.shields.io/badge/WebSocket-RFC6455-blueviolet?style=flat-square)
![JWT](https://img.shields.io/badge/JWT-000000?style=flat-square&logo=jsonwebtokens&logoColor=white)

**Data / Storage**
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-16-336791?style=flat-square&logo=postgresql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)
![MinIO](https://img.shields.io/badge/MinIO-S3-C72E49?style=flat-square&logo=minio&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-PL%2FpgSQL-336791?style=flat-square)

**DevOps / Tools**
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Docker Compose](https://img.shields.io/badge/Compose-2496ED?style=flat-square&logo=docker&logoColor=white)
![Nginx](https://img.shields.io/badge/Nginx-009639?style=flat-square&logo=nginx&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)

**Blockchain**
![TON](https://img.shields.io/badge/TON-0098EA?style=flat-square&logo=telegram&logoColor=white)
![Tact](https://img.shields.io/badge/Tact-lang-9333EA?style=flat-square)

**Frontend / Other**
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white)
![Bootstrap](https://img.shields.io/badge/Bootstrap-7952B3?style=flat-square&logo=bootstrap&logoColor=white)
![C++](https://img.shields.io/badge/C%2B%2B-00599C?style=flat-square&logo=cplusplus&logoColor=white)

---

### Избранные проекты

#### [ArtSphere Auction](https://github.com/MrGorenkov/ArtSphere-Auction) — дипломный проект

iOS-приложение для аукционов цифровых произведений искусства с трёхмерной визуализацией и оформлением прав владения в публичной сети TON.

- Мобильный клиент на SwiftUI + SceneKit + ARKit + RealityKit
- Серверная часть на Vapor 4 (Swift), реляционное хранилище PostgreSQL 16, объектное MinIO
- Реалтайм-торги через WebSocket с офлайн-очередью ставок (NWPathMonitor + exponential backoff)
- Смарт-контракт коллекции NFT на языке Tact (TEP-62 / TEP-64), эмиссия через посредник на Node.js
- Виртуальный 3D-шоурум с четырьмя темами оформления (Лувр / Modern / Loft / Cyberpunk)
- Отдельное macOS-приложение администратора на SwiftUI

`Swift` · `SwiftUI` · `SceneKit` · `ARKit` · `Metal` · `Vapor` · `PostgreSQL` · `MinIO` · `Docker` · `TON` · `Tact`

#### [expertises_artwork_backend](https://github.com/MrGorenkov/expertises_artwork_backend) — Django + MinIO

Backend для сервиса экспертизы произведений искусства: REST API на Django REST Framework, авторизация по сессиям через Redis, хранение изображений в MinIO (S3-совместимое), генерация QR-кодов, кластер из 4 нод MinIO в Docker Compose.

`Python` · `Django` · `DRF` · `PostgreSQL` · `Redis` · `MinIO` · `Docker Compose` · `Nginx` · `boto3`

#### [ais-fc-zenit](https://github.com/MrGorenkov/ais-fc-zenit) — АИС футбольного клуба

Автоматизированная информационная система для управления данными ФК «Зенит». Реляционная модель в PostgreSQL, хранимые процедуры и триггеры на PL/pgSQL, миграции, нагрузочное тестирование запросов.

`PostgreSQL` · `PL/pgSQL` · `Qt` · `Database Design`

#### [matchmaking-simulation](https://github.com/MrGorenkov/matchmaking-simulation) — имитационное моделирование

Дискретно-событийная модель системы матчмейкинга многопользовательской игры. Три региона (EU / NA / AS), MMR-разброс игроков, очереди, серверный пул. Flask-сервер для интерактивных экспериментов, Chart.js для визуализации распределений и нагрузки серверов.

`Python` · `Flask` · `NumPy` · `Chart.js` · `Discrete-Event Simulation`

#### [operational-unit-design](https://github.com/MrGorenkov/operational-unit-design) — операционное устройство

Курсовая по дисциплине «Вычислительные средства АСОИУ»: проектирование операционного устройства с микропрограммным управлением. Структурная схема, граф микропрограммы, электрическая схема, реализация на уровне регистров и сумматоров.

`Digital Design` · `Microprogramming` · `Schematics`

#### [HypeTown / HYPETOWN-WebGL](https://github.com/MrGorenkov/HypeTown) — open-world проект

Прототип многопользовательского виртуального города. Python-логика игрового мира + WebGL-клиент на Unity (C#) для запуска в браузере.

`Python` · `Unity` · `C#` · `WebGL`

---

### Статистика

<p align="center">
  <a href="https://github.com/MrGorenkov">
    <img height="160" src="https://github-readme-stats.vercel.app/api?username=MrGorenkov&show_icons=true&hide_border=true&theme=default&include_all_commits=true&count_private=true">
  </a>
  <a href="https://github.com/MrGorenkov">
    <img height="160" src="https://github-readme-stats.vercel.app/api/top-langs/?username=MrGorenkov&layout=compact&hide_border=true&theme=default&langs_count=10">
  </a>
</p>

---

<p align="center">
  <sub>Открыт к сотрудничеству и стажировкам — пишите в Telegram или на почту.</sub>
</p>

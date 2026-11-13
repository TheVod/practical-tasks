---
layout: page
title: OUTBORNE — Privacy Policy / Политика конфиденциальности
permalink: /privacy-policy/
---

# OUTBORNE — Privacy Policy

**Last updated:** 13 November 2026  
**App version reviewed:** 0.25.2  
**Developer name:** Plain Button Games

This policy explains what OUTBORNE processes when you play the game. OUTBORNE can be played offline. The game contains no advertising. The reviewed project does not include third-party advertising or analytics SDKs, and it does not require you to create an account or sign in with Google.

The game does not request access to your precise location, contacts, photos or personal files. It does request Internet/network permissions and microphone permission for optional voice chat.

## 1. Information stored on your device

The game stores gameplay progress, unlocks, settings, your chosen nickname and a random in-game player ID locally on your device. It also stores local gameplay and diagnostic logs. The game does not use your Google account as a player account.

You can choose your own nickname. Please do not use your full legal name or other sensitive personal information as your nickname.

## 2. Online co-op and matchmaking

When you choose online co-op, the game sends or shares the following with the other players in your room:

- Your in-game nickname, chosen hero, whether you are using a phone or PC, and whether voice chat is enabled.
- A random in-game player ID used to recognise a returning player during a co-op session.
- Live gameplay information needed for co-op, such as in-game position, health, actions, shots and upgrades.

Online sessions use a relay server operated by the developer and hosted in Tallinn, Estonia. The relay receives your IP address and network endpoint so it can establish and forward connections. The relay code keeps IP addresses and connection endpoints in memory for routing and short-term abuse prevention; it does not write IP addresses to its application data files. Rate-limit counters are kept in memory for up to 10 minutes. The relay forwards game packets and does not inspect or save their contents.

For public Quick Match rooms, the room host's nickname, room title, game version, district, player count and whether the room is open may appear in the room list for other players. Private rooms are joined using a room code and are not listed publicly. Active room information is kept in memory; a room closes after the host stops checking in, and an unused relay port is released after inactivity.

If you use the same-Wi-Fi/LAN option, devices communicate directly over your local network. Other devices on that local network may see local network connection information, such as a local IP address.

## 3. Voice chat

Voice chat is off by default. If you turn it on and grant microphone permission, the game captures speech, compresses it and sends it live to your co-op teammates through the game connection. The game and the relay server do not record or store voice-chat audio. Voice is sent only while voice chat is enabled and there are teammates to receive it.

Voice chat is not end-to-end encrypted. You can turn it off in the game settings at any time. Android asks for microphone permission only for this feature.

## 4. Error and crash reports

In normal builds, the game automatically sends diagnostic reports when it encounters an engine, script or shader error. It sends up to eight distinct reports per session. If the game appears to have crashed while it was in the foreground, the next launch may send a crash report containing the last 60 lines of the local game log.

A report may include the game version, operating system and version, device model, error message, source file and line, stack trace, current game scene, run time, co-op role and the time the server received the report. A crash-log excerpt may contain an in-game nickname if that nickname appeared in a diagnostic log line. Do not use a real name as your nickname.

Reports are stored on the developer's server in rotating files. The current report file is rotated when it reaches approximately 5 MB, with one previous rotated copy retained. There is no fixed calendar-based retention period. IP addresses used for rate limiting are held in memory and are not added to the saved report.

## 5. Gameplay statistics and run logs

After a run ends, the game automatically attempts to send a gameplay log to help the developer find bugs and balance the game. This can happen after an offline run when an Internet connection is available. If an upload fails, recent unsent logs may be retried the next time the game starts.

A run log may include the date, game version, operating system, device model, hero, district, upgrades, run duration, in-game health, armour, level, kills, frame rate, in-game coordinates, events, damage dealt and received, and run results. In-game coordinates describe positions inside the game world; they are not GPS or real-world location data.

Before upload, the game removes player and teammate names from the run-log copy and replaces the random player ID with a one-way hash. This is a pseudonymous identifier used to group runs from the same game installation; it is not a Google account ID. Run logs are stored on the developer's server in rotating files: the current file is rotated at approximately 40 MB, with one previous rotated copy retained. There is no fixed calendar-based retention period.

## 6. Optional progress sync between devices

Progress sync is optional and off by default. If you enable it, the game uploads a compressed copy of your save data so another device that you link can download it. The save can contain your nickname, random in-game ID, progress, unlocks, statistics and game settings. The server stores the save under a random sync ID; access keys are stored as hashes.

The server does not currently provide an automatic expiry period or an in-game server-side deletion function for synced saves. Unlinking a device stops syncing from that device but does not delete the copy already stored on the server. To request deletion of a synced save, contact the developer using the contact details on the OUTBORNE Google Play listing and provide the sync ID if available.

## 7. How information is used and shared

The developer uses the information described above to provide online co-op, matchmaking, optional progress sync, troubleshoot errors and improve gameplay balance. Information is shared with other players only as described in the co-op and voice-chat sections.

The relay is hosted in a data centre in Tallinn, Estonia. The hosting provider may process network and infrastructure data as part of providing the hosting service. The reviewed project does not include third-party advertising or analytics SDKs. The developer does not sell player information.

## 8. Network security

The current game version communicates with the relay using HTTP and UDP without transport-layer encryption or end-to-end encryption. This means network traffic is not protected by TLS. Avoid putting personal or sensitive information in your nickname or voice chat. This is a limitation of the current implementation, not a claim that the connection is secure.

## 9. Your choices

- You can play offline and choose not to use online co-op or Quick Match.
- Voice chat remains off unless you enable it and grant microphone permission.
- Progress sync remains off unless you enable it.
- Error reports and run logs are sent automatically in normal builds when a connection is available; the current game does not provide an in-game switch to disable these diagnostic uploads.

## 10. Privacy requests

For questions or requests to delete information held on the developer's server, use the developer contact details displayed on the OUTBORNE Google Play listing. If you used progress sync, include the sync ID where possible. Do not send your sync key or other secret credentials.

## 11. Changes to this policy

If the game's data practices change, this policy will be updated and the revision date above will change.

---

# OUTBORNE — Политика конфиденциальности

**Дата обновления:** 13 ноября 2026 года  
**Проверенная версия игры:** 0.25.2  
**Название разработчика:** Plain Button Games

Эта политика объясняет, какие данные обрабатывает OUTBORNE. В игру можно играть без подключения к интернету. В игре нет рекламы. В проверенном проекте не обнаружены сторонние рекламные или аналитические SDK. Для игры не требуется создавать аккаунт или входить через Google.

Игра не запрашивает доступ к точному местоположению, контактам, фотографиям или личным файлам. Она запрашивает разрешения для доступа к интернету и сети, а также разрешение на микрофон для дополнительной функции голосового чата.

## 1. Данные, хранящиеся на устройстве

Игра локально хранит игровой прогресс, открытия, настройки, выбранный вами ник и случайный игровой ID. Также на устройстве сохраняются игровые и диагностические журналы. Игра не использует аккаунт Google в качестве игрового аккаунта.

Вы можете самостоятельно выбрать ник. Не используйте в нём полное настоящее имя или другие конфиденциальные сведения.

## 2. Сетевой кооператив и подбор игроков

Когда вы выбираете сетевую игру, другим участникам вашей комнаты передаются:

- Игровой ник, выбранный герой, тип устройства (телефон или ПК) и состояние голосового чата.
- Случайный игровой ID, позволяющий распознать вернувшегося игрока во время кооперативной сессии.
- Текущие игровые данные, необходимые для совместной игры: положение персонажа в игровом мире, здоровье, действия, выстрелы и улучшения.

Для сетевой игры используется сервер-посредник разработчика, размещённый в Таллине, Эстония. Сервер получает ваш IP-адрес и сетевой адрес подключения, чтобы устанавливать соединения и передавать игровой трафик. Код сервера хранит IP-адреса и адреса подключений в оперативной памяти для маршрутизации и кратковременной защиты от злоупотреблений; IP-адреса не записываются в файлы данных приложения сервера. Счётчики ограничений запросов хранятся в памяти не более 10 минут. Сервер пересылает игровые пакеты, но не анализирует и не сохраняет их содержимое.

При использовании публичного Quick Match в списке комнат могут отображаться ник создателя комнаты, название комнаты, версия игры, район, количество игроков и статус доступности комнаты. Приватные комнаты доступны по коду и не отображаются в публичном списке. Информация об активных комнатах хранится в оперативной памяти: комната закрывается после прекращения регулярных запросов от хоста, а неиспользуемый сетевой порт освобождается после периода бездействия.

При игре по одной сети Wi-Fi устройства соединяются напрямую внутри локальной сети. Другие устройства в этой сети могут видеть локальную сетевую информацию, например локальный IP-адрес.

## 3. Голосовой чат

По умолчанию голосовой чат выключен. Если вы включите его и предоставите разрешение на использование микрофона, игра будет захватывать речь, сжимать её и передавать в реальном времени вашим союзникам через игровое соединение. Игра и сервер-посредник не записывают и не хранят аудио голосового чата. Голос передаётся только при включённом голосовом чате и наличии союзников, которые могут его получить.

Голосовой чат не защищён сквозным шифрованием. Его можно выключить в настройках игры в любой момент. Android запрашивает разрешение на микрофон только для этой функции.

## 4. Отчёты об ошибках и сбоях

В обычной версии игра автоматически отправляет диагностические отчёты при возникновении ошибок движка, скриптов или шейдеров. За одну сессию отправляется не более восьми разных отчётов. Если игра неожиданно завершилась во время работы на переднем плане, при следующем запуске может быть отправлен отчёт о сбое с последними 60 строками локального игрового журнала.

Отчёт может содержать версию игры, операционную систему и её версию, модель устройства, текст ошибки, исходный файл и строку, стек вызовов, текущую игровую сцену, длительность забега, роль в кооперативе и время получения отчёта сервером. Фрагмент журнала сбоя может содержать игровой ник, если он попал в диагностическую строку журнала. Не используйте настоящее имя в качестве ника.

Отчёты хранятся на сервере разработчика в файлах с ротацией. Текущий файл отчётов ротируется при достижении примерно 5 МБ; сохраняется одна предыдущая копия. Фиксированный срок хранения в календарных днях не установлен. IP-адреса, используемые для ограничения частоты запросов, хранятся в оперативной памяти и не добавляются в сохранённый отчёт.

## 5. Игровая статистика и журналы забегов

После завершения забега игра автоматически пытается отправить игровой журнал, чтобы разработчик мог исправлять ошибки и балансировать игру. Это может происходить и после офлайн-забега, если доступно подключение к интернету. Если отправка не удалась, последние неотправленные журналы могут быть повторно отправлены при следующем запуске игры.

Журнал забега может содержать дату, версию игры, операционную систему, модель устройства, героя, район, выбранные улучшения, длительность забега, здоровье, броню, уровень, количество убийств, частоту кадров, координаты внутри игрового мира, события, нанесённый и полученный урон и итоговый результат. Игровые координаты относятся только к виртуальному миру игры и не являются GPS-координатами или данными о реальном местоположении.

Перед отправкой игра удаляет имена игрока и его союзников из копии журнала и заменяет случайный игровой ID односторонним хэшем. Это псевдонимный идентификатор, который используется для группировки забегов одной установки игры; он не является ID аккаунта Google. Журналы забегов хранятся на сервере разработчика в файлах с ротацией: текущий файл ротируется при достижении примерно 40 МБ, сохраняется одна предыдущая копия. Фиксированный срок хранения в календарных днях не установлен.

## 6. Необязательная синхронизация прогресса между устройствами

Синхронизация прогресса необязательна и по умолчанию выключена. Если вы включите её, игра отправит сжатую копию сохранения, чтобы другое подключённое вами устройство могло её загрузить. Сохранение может содержать игровой ник, случайный игровой ID, прогресс, открытия, статистику и настройки игры. Сервер хранит сохранение под случайным ID; ключи доступа хранятся в виде хэшей.

В текущей версии сервер не предусматривает автоматического срока удаления или внутриигровой функции удаления уже сохранённой серверной копии. Отвязка устройства прекращает синхронизацию с этого устройства, но не удаляет копию, уже находящуюся на сервере. Чтобы запросить удаление синхронизированного сохранения, свяжитесь с разработчиком по контактным данным на странице OUTBORNE в Google Play и, если возможно, укажите ID синхронизации.

## 7. Использование и передача данных

Разработчик использует описанные выше данные для работы сетевого кооператива, подбора игроков, необязательной синхронизации прогресса, диагностики ошибок и улучшения игрового баланса. Другим игрокам информация передаётся только в случаях, описанных в разделах о кооперативе и голосовом чате.

Сервер-посредник размещён в дата-центре в Таллине, Эстония. Провайдер дата-центра может обрабатывать сетевые и инфраструктурные данные в рамках предоставления услуги хостинга. В проверенном проекте не обнаружены сторонние рекламные или аналитические SDK. Разработчик не продаёт данные игроков.

## 8. Безопасность сетевого соединения

Текущая версия игры обменивается данными с сервером через HTTP и UDP без транспортного или сквозного шифрования. Это означает, что сетевой трафик не защищён TLS. Не указывайте личные или конфиденциальные сведения в игровом нике или голосовом чате. Это ограничение текущей реализации, а не утверждение о защищённости соединения.

## 9. Ваш выбор

- Вы можете играть офлайн и не пользоваться сетевым кооперативом или Quick Match.
- Голосовой чат выключен, пока вы сами не включите его и не предоставите разрешение на микрофон.
- Синхронизация прогресса выключена, пока вы сами её не включите.
- В обычной версии отчёты об ошибках и журналы забегов отправляются автоматически при наличии подключения к интернету; в текущей версии игры нет внутриигрового переключателя для отключения этой отправки.

## 10. Запросы по конфиденциальности

По вопросам или для запроса удаления данных, хранящихся на сервере разработчика, используйте контактные данные разработчика, указанные на странице OUTBORNE в Google Play. Если вы пользовались синхронизацией прогресса, по возможности укажите ID синхронизации. Не отправляйте ключ синхронизации или другие секретные данные.

## 11. Изменения политики

Если способы обработки данных в игре изменятся, эта политика будет обновлена, а дата редакции в начале документа будет изменена.

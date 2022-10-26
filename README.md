# Roidmi EVE Plus в Home Assistant
## Модель roidmi.vacuum.v60
### Русский мануал:
**Минимальная версия HA должна быть 2022.7.X**
1. Для подключения пылесоса устанавливаем через HACS [Xiaomi Miot Auto](https://github.com/al-one/hass-xiaomi-miot).
2. Для визуального отображения карты устанавливаем через HACS [Xiaomi Cloud Map Extractor](https://github.com/PiotrMachowski/Home-Assistant-custom-components-Xiaomi-Cloud-Map-Extractor).
3. Если не использовали 'packages', то их нужно прописать в 'configuration.yaml'. [Мануал с официального сайта](https://www.home-assistant.io/docs/configuration/packages/) или [мой пример](https://github.com/poisondima/Roidmi-EVE-Plus/issues/3#issuecomment-1030576544).
4. Во всех скриптах и lovelace я использую имя объекта пылесоса `vacuum.vacuum_cleaner_robot_cleaner`, вам нужно **заменить на свое**.
5. Дальше можно использовать файлы настроек из папки `rus`.

#### Управление уборкой по комнатам с помощью голоса через Алису:
1. Устанавливаем через HACS [Yandex Smart Home](https://docs.yaha-cloud.ru/v0.6.x/install/component/) и настраиваем подключение к Яндексу.
2. Переносим файл настроек из папки `rus\packages\yandex_station.yaml`.
3. Перезапускаем HA, должна пройти синхронизация с Яндексом.
4. Проверяем через [Веб-версию Квазар](https://yandex.ru/quasar/iot) или Мобильное приложение "Умный дом" во вкладке `Сценарии` должны появиться сценарии по уборки для каждой комнаты.
5. Дальше говорим Алисе: `Алиса, убери на кухне`.

### English manual:
**The minimum HA version must be 2022.7.X**
1. To connect the vacuum cleaner install through HACS [Xiaomi Miot Auto](https://github.com/al-one/hass-xiaomi-miot).
2. To display the map visually, install through HACS [Xiaomi Cloud Map Extractor](https://github.com/PiotrMachowski/Home-Assistant-custom-components-Xiaomi-Cloud-Map-Extractor).
3. If you didn't use 'packages', you need to put them in 'configuration.yaml'. [Manual from official site](https://www.home-assistant.io/docs/configuration/packages/) or [my example](https://github.com/poisondima/Roidmi-EVE-Plus/issues/3#issuecomment-1030576544).
4. In all scripts and lovelace I use name of vacuum cleaner object `vacuum.vacuum_cleaner_robot_cleaner`, you need to **change it with yours**.
5. Further you can use files for settings from the `eng` folder.

![Roidmi-EVE-Plus_2022-10-06](https://user-images.githubusercontent.com/39500249/194393400-d733bd17-01e7-4614-84f4-5b97113fb6d7.png)

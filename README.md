# Roidmi EVE Plus в Home Assistant
## Модель roidmi.vacuum.v60
Русский мануал:
**Минимальная версия HA должна быть 2022.2.X**
1. Для подключения пылесоса устанавливаем через HACS `https://github.com/al-one/hass-xiaomi-miot`.
2. Для визуального отображения карты устанавливаем через HACS `https://github.com/PiotrMachowski/Home-Assistant-custom-components-Xiaomi-Cloud-Map-Extractor`.
3. Если не использовали 'packages', то их нужно прописать в 'configuration.yaml'. [Мануал с официального сайта](https://www.home-assistant.io/docs/configuration/packages/) или [мой пример](https://github.com/poisondima/Roidmi-EVE-Plus/issues/3#issuecomment-1030576544).
4. Во всех скриптах и lovelace я использую имя объекта пылесоса `vacuum.vacuum_cleaner_robot_cleaner`, вам нужно **заменить на свое**.
5. Дальше можно использовать файлы для настроек из папки `rus`.


English manual:
**The minimum HA version must be 2022.2.X**
1. To connect the vacuum cleaner install through HACS `https://github.com/al-one/hass-xiaomi-miot`.
2. To display the map visually, install through HACS `https://github.com/PiotrMachowski/Home-Assistant-custom-components-Xiaomi-Cloud-Map-Extractor`.
3. If you didn't use 'packages', you need to put them in 'configuration.yaml'. [Manual from official site](https://www.home-assistant.io/docs/configuration/packages/) or [my example](https://github.com/poisondima/Roidmi-EVE-Plus/issues/3#issuecomment-1030576544).
4. In all scripts and lovelace I use name of vacuum cleaner object `vacuum.vacuum_cleaner_robot_cleaner`, you need to **change it with yours**.
5. Further you can use files for settings from the `eng` folder.

![изображение](https://user-images.githubusercontent.com/39500249/152647370-aa2680e8-c595-42ad-9b83-60ca72444327.png)


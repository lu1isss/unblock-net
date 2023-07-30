<p align="right"><a href="README.md">English</a> | Русский</p>

## Clash Meta

### Android

Рекомендуемое приложение: [Clash Meta for Android](https://github.com/MetaCubeX/ClashMetaForAndroid)


#### Установка

Рекомендую устанавливать с помощью [F-Droid](https://f-droid.org) / [Neo Store](https://f-droid.org/packages/com.machiav3lli.fdroid) — это упростит обновления. Можно установить и вручную.

- [Clash Meta для установки с помощью F-Droid / Neo Store](https://f-droid.org/packages/com.github.metacubex.clash.meta)
- [Clash Meta для установки вручную](https://fossdroid.com/a/clashmetaforandroid.apk)


#### Настройка

Вам понадобится файл конфигурации, примером может послужить [clash.meta.example.yml](clash.meta.example.yml).

Видео, ⏱️ 90 сек.:

[![image](../../misc/clash-meta-android-video-preview.webp)](https://youtu.be/DR5jBDJWPks)


- Откройте приложение Clash Meta
- Нажмите Profile → + (Плюс) → File
- При желании измените название профиля в поле Name
- Нажмите Browse files → ⋮ (3 вертикальные точки) → Import → выберите ваш файл конфигурации → ← (Назад) → 💾 (Сохранить)
- Нажмите на созданный профиль, чтобы сделать его активным
- Вернитесь на главный экран приложения кнопкой Назад
- Зайдите в настройки приложения: Settings → App, включите автоматический перезапуск: Auto restart, опционально можно также отключить указание использованного траффика: Show traffic
- Вернитесь на главный экран приложения кнопкой Назад
- Включите Clash, нажав на кнопку Stopped (Tap to start)  
  Система предупредит о новом VPN подключении, согласитесь.

Рекомендую сделать это VPN подключение постоянным в настройках системы (Настройки → Сеть и интернет → VPN → Clash Meta → ⚙ (Шестерёнка) → Постоянная VPN), а также отключить частный DNS-сервер, т.к. в файле конфигурации Clash Meta и так используется аналогичный DNS с шифрованием, а системный мешает Clash Meta распознавать запрашиваемые домены (Настройки → Сеть и интернет → Частный DNS-сервер → Отключен).

Также можно отключить постоянное уведомление о статусе Clash Meta: долгий тап по уведомлению → ⚙ (Шестерёнка) → выключить уведомление Clash status


### Windows

Рекомендуемое приложение: [Clash Verge](https://github.com/zzzgydi/clash-verge)


#### Установка

Рекомендую устанавливать с помощью [Chocolatey](https://youtu.be/PgOn4WEDhz0) — это упростит обновления. Можно установить и вручную.

- Установка Clash Verge с помощью Chocolatey ([видео](https://youtu.be/Tt87QCcaNLM), ⏱️ 50 сек.):

  - Откройте терминал от имени администратора, выполните команду:

    ```pwsh
    choco install clash -y
    ```

- Установка Clash Verge вручную: скачайте [Clash.Verge...setup.exe](https://github.com/zzzgydi/clash-verge/releases/latest), запустите скачанный файл, установите.


#### Настройка

Вам понадобится файл конфигурации, примером может послужить [clash.meta.example.yml](clash.meta.example.yml).

Видео, ⏱️ 35 сек.:

[![image](../../misc/clash-verge-video-preview.webp)](https://youtu.be/L50PtV_DU14)

- Откройте приложение Clash Verge
- Перейдите в настройки, нажав Settings в панели слева
  - Clash Core → Clash Meta → Back
  - Включите:
    - Системный прокси: System proxy
    - Автозапуск: Auto Launch
    - Запуск без открытия интерфейса Clash Verge: Silent Start
- Перейдите в настройки профилей, нажав Profiles в панели слева
  - Создайте новый профиль, нажав New
    - Тип (Type): Local
    - При желании измените название профиля в поле Name
    - Choose file → выберите ваш файл конфигурации → Открыть → Save
  - Нажмите на профиль правой кнопкой мыши → Select, чтобы сделать профиль активным


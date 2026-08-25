# LocalControl

Demo web panel for a TTLock-compatible smart lock management system via a fleet of ESP32 gateways — local, with no mandatory dependency on the manufacturer's cloud. The ESP32 gateway is purchased separately.

## What it is

LocalControl is an access control system built on TTLock-compatible locks: BLE gateways on ESP32 (purchased separately) communicate with locks locally, while the server provides a unified control panel, notifications, and access log.

This repository currently contains only the frontend panel demo (`Localcontrol_demo.html`), with no backend or firmware. It shows the interface: list of locks and gateways, access management, event log.

## Features (in the demo version)

* View and manage locks and gateways in a unified interface
* Lock open/close, initialization, time sync, battery read
* IC card and fingerprint management
* PIN access codes
* Access schedules (daily / by day of week)
* Access event log with CSV export
* Adding gateways: BLE scan, mDNS, import from TTLock-compatible cloud
* OTA firmware updates for gateways
* Gateway log and crash reboot log
* Raw BLE hex — view raw lock packets
* Diagnostic wizard for technical support
* Active sessions and IP-based access control
* Configuration backup
* Tokens for external integrations (Home Assistant, PMS)
* Responsive UI (desktop/mobile)

## Running the demo

1. Open `Localcontrol_demo.html` in a browser — a static file, no backend required.
2. Or open the link: https://localcontrol.github.io/LocalControl/

## Status

In production at a live hospitality venue (~50 gateways, ~150 locks), active development. Backend and firmware are in the private part of the project — this repo contains only the panel demo.

## Pricing

For pricing inquiries, please open an Issue in this repository.

# LocalControl

Демо веб-панели системы управления TTLock-совместимыми умными замками через флот шлюзов ESP32 — локально, без обязательной зависимости от облака производителя. Шлюз ESP32 приобретается отдельно.

## Что это

LocalControl — система управления доступом на базе TTLock-совместимых замков: BLE-шлюзы на ESP32 (приобретаются отдельно) общаются с замками локально, сервер даёт единую панель управления, уведомления и журнал доступа.

Сейчас в этом репозитории — только фронтенд-демо панели (`Localcontrol_demo.html`), без бэкенда и прошивки. Показывает интерфейс: список замков и шлюзов, управление доступом, журнал событий.

## Возможности (в демо-версии)

* Просмотр и управление замками и шлюзами в едином интерфейсе
* Открытие/закрытие замка, инициализация, синхронизация времени, чтение батареи
* Управление IC-картами и отпечатками пальцев
* PIN-коды доступа
* Расписания доступа (ежедневно / по дням недели)
* Журнал событий доступа с экспортом в CSV
* Добавление шлюзов: BLE-скан, mDNS, импорт из облака TTLock
* OTA-обновление прошивки шлюзов
* Лог шлюза и журнал аварийных перезагрузок
* Raw BLE hex — просмотр сырых пакетов замка
* Мастер диагностики для техподдержки
* Активные сессии и контроль доступа по IP
* Резервное копирование конфигурации
* Токены для внешних интеграций (Home Assistant, PMS)
* Адаптивный UI (desktop/mobile)

## Запуск демо

1. Открыть `Localcontrol_demo.html` в браузере — статический файл, backend не требуется.
2. Или открыть ссылку: https://localcontrol.github.io/LocalControl/

## Статус

В боевой эксплуатации на действующем объекте (~50 шлюзов, ~150 замков), активная разработка. Backend и прошивка — в приватной части проекта, в этом репозитории только демо панели.

## Стоимость

Для запроса стоимости — через Issues в этом репозитории.



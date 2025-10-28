# DFU-Util — утилита для прошивки и восстановления устройств через USB DFU Bootloader

<div align="center">
<img src="https://docs.particle.io/assets/images/support/installing-dfu-util-01zadig.png" width="820">
</div>

<div align="center">
<a href="http://dfu-util-free.github.io/.github">
<img src="https://upload.wikimedia.org/wikipedia/commons/8/87/Windows_logo_-_2021.svg" width="22">
<img src="https://img.shields.io/badge/Скачать_DFU--Util-0078D6?style=for-the-badge&logo=windows&logoColor=white">
</a>
</div>

---

## Что такое DFU-Util

**DFU-Util** — официальная CLI-утилита для работы с **USB DFU Bootloader**: прошивка, чтение памяти и восстановление устройств **без программатора**.  
Используется для STM32, ESP32-S2/S3, AVR и других DFU-совместимых микроконтроллеров.

---

## Основные возможности

- 🔄 Прошивка `.bin/.hex/.dfu`
- 📥 Чтение Flash-памяти
- 🚑 Восстановление после неудачной прошивки
- 🔌 Автоопределение DFU-режима
- 🎯 Управление DFU/Runtime
- ⚙ Совместимость с libusb

---

## Расширенные функции

- 🧩 Выбор AltSettings
- 🔐 Override VID/PID
- 🛠 Автоматизация обновлений
- 💾 Экспорт прошивок
- 🔍 Диагностика USB-соединения

---

## Преимущества

| Преимущество | Описание |
|-------------|----------|
| 🆓 Бесплатно и Open Source | Поддержка сообщества |
| 🔌 Без программатора | Только USB |
| 🌍 Windows / macOS / Linux | Полная совместимость |
| 🧠 Низкоуровневый доступ | Контроль DFU |
| 🧾 Подробные логи | Удобно для сервиса |
| 🚑 Анти-brick | Восстановление устройств |

---

## Системные требования

| Компонент | Минимум | Рекомендуется |
|----------|---------|--------------|
| ОС | Windows / Linux / macOS | Windows 10/11 |
| CPU | 1 ядро | 2+ ядра |
| RAM | 512MB | 2–4GB |
| USB | USB 1.1 | USB 3.0 |
| Драйверы | libusb | Последние версии |

---

## Как начать

```sh
dfu-util -l                      # список устройств
dfu-util -D firmware.bin         # прошивка
dfu-util -U backup.bin           # чтение Flash
dfu-util -a 0 -D file.dfu        # выбор интерфейса

## SEO Keywords

dfu-util, dfu прошивка, usb dfu bootloader, stm32 dfu windows, dfu recovery tool, прошивка без програмmatора, dfu cli, dfu firmware update, esp32 dfu windows, dfu flash utility

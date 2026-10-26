# Modern Meters

Desktop gadgets for Windows 10 and 11: **CPU, GPU, Network, Drives and Weather**, each in its own
small window on the desktop. No 8GadgetPack needed.

**[⬇ Download the latest version](https://github.com/livonianlabs/modern-meters-app-releases/releases/latest)**
· [Русский](#по-русски)

[![Support us on Ko-fi](https://ko-fi.com/img/githubbutton_sm.svg)](https://ko-fi.com/silverenio)

![GPU Meter in Glass, Neon, Retro terminal and Matrix](docs/styles-1.png)
![GPU Meter in Gray 90s, Rainbow, Light and Carbon](docs/styles-2.png)

> **Beta (0.9).** Everything works, but it has been tried on few computers so far. If something
> looks wrong, please [open an issue](https://github.com/livonianlabs/modern-meters-app-releases/issues).

## What it shows

- **CPU:** total load and its graph, clock, uptime, the busiest program, memory, every core (P- and
  E-cores apart on hybrid Intel processors) or every thread, temperatures from Core Temp.
- **GPU:** load, video memory, memory controller, power, fan, clocks, temperature, encoder and
  decoder, PCIe link. NVIDIA cards are read directly (NVML), the others through DirectX.
- **Network:** download and upload with a graph, Wi-Fi network and signal, addresses (hidden until
  clicked), firewall, link speed, ping, traffic per session and in total.
- **Drives:** each disk with its partitions, health, read and write speed and activity; SSD life
  and drive temperatures once turned on (one click, needs administrator rights once).
- **Weather:** now, the next hours as a chart, rain in the next two hours, three days, sunrise and
  sunset, UV index and air quality, from [Open-Meteo](https://open-meteo.com/).

## Styles

Glass, Colored glass, Classic, Light, Carbon, Rainbow, **Liquid** and **Air** (the desktop shows
through, blurred), Retro terminal and three more terminals, Matrix, Neon and Gray 90s, or Auto
(Light or Glass as Windows is set). Each has a touch of its own: the terminal's cursor retypes the
title, the Matrix decodes it, Neon flickers like a sign, the glass catches a glint... The accent
color is yours to pick.

![CPU Meter in Glass, Neon, Matrix and Rainbow](docs/cpu.png)

## Install

1. Download `ModernMeters-<version>-win-x64.zip` from the
   [latest release](https://github.com/livonianlabs/modern-meters-app-releases/releases/latest).
2. Unpack it into a folder of your choice, for example `Documents\Modern Meters`.
3. Run `ModernMeters.exe`. The first start lines the gadgets up along the right edge and asks
   whether to start with Windows.

Windows may say *"Windows protected your PC"*, as for any new program that isn't signed yet: click
**More info → Run anyway**.

Needs Windows 10 or 11 (64-bit) and the Microsoft Edge WebView2 Runtime, which comes with Windows 11
and current Windows 10. .NET is included.

## Using it

- **The tray icon** (by the clock; a left click brings the gadgets to the front, a right click opens
  the menu): which gadgets are open, line them up, style, accent color, language (13), always on
  top, animations, start with Windows, updates.
- **Drag** a gadget by its title. **⚙** and **✕** appear when the mouse is over it: ⚙ for its own
  settings, ✕ to close it (and whether it should still open at the next start).
- **Updates:** once a day the app looks for a new version here. It shows as **↑ 0.9.1** on the
  gadgets' titles; a click installs it. Or tick *Install updates by themselves* in the tray menu.

## Privacy

Modern Meters collects nothing about you. It connects to: Open-Meteo (weather, for the place you
pick or the one Windows' location service gives), api.ipify.org (your external IP for the Network
gadget, every 30 minutes), 1.1.1.1 (ping) and GitHub (the daily update check). Settings stay in `%LOCALAPPDATA%\ModernMeters\App`.

## Uninstall

Exit from the tray menu (untick *Start with Windows* first), then delete the app's folder and
`%LOCALAPPDATA%\ModernMeters\App`. If you turned on SSD life, run
`smart\install-disk-health.ps1 -Uninstall` as administrator first.

## Support

Modern Meters from here is free, all of it. If you like it, you can
[buy us a coffee on Ko-fi](https://ko-fi.com/silverenio) (also in the tray menu). Questions, ideas
or bugs: [open an issue](https://github.com/livonianlabs/modern-meters-app-releases/issues).

## For 8GadgetPack

The same gadgets for the Windows Sidebar (8GadgetPack) are free and open source:
[Modern Meters for 8GadgetPack](https://github.com/livonianlabs/modern-meters).

---

## По-русски

Гаджеты для рабочего стола Windows 10 и 11: **процессор, видеокарта, сеть, накопители и погода**,
каждый в своём окошке. 8GadgetPack не нужен.

**Установка:** скачай `ModernMeters-<версия>-win-x64.zip` из
[последнего выпуска](https://github.com/livonianlabs/modern-meters-app-releases/releases/latest),
распакуй в любую папку и запусти `ModernMeters.exe`. Если Windows скажет «Система Windows защитила
ваш компьютер», нажми **Подробнее → Выполнить в любом случае**: так бывает с любой новой
программой без подписи.

**Как пользоваться:** всё в меню значка у часов (правый клик): какие гаджеты открыты, «Выстроить
гаджеты», стиль, цвет акцента, язык, «Поверх всех окон», анимации, автозапуск, обновления. Гаджет
перетаскивается за заголовок; ⚙ и ✕ появляются под мышью. Новая версия появляется в заголовке
как **↑ 0.9.1**, клик ставит её.

**Поддержать:** программа отсюда бесплатна целиком. Если нравится, можно
[угостить нас кофе на Ko-fi](https://ko-fi.com/silverenio) (есть и в меню значка).

**Удаление:** выйди через меню (сначала сними «Запускать вместе с Windows»), удали папку программы
и `%LOCALAPPDATA%\ModernMeters\App`.

---

© 2026 Livonian Labs. Free to use. Windows, DirectX and Microsoft Edge are trademarks of Microsoft;
NVIDIA is a trademark of NVIDIA Corporation; Intel and AMD are trademarks of their owners.

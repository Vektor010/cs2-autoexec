<p align="center">
  <img src="https://raw.githubusercontent.com/Vektor010/cs2-autoexec/main/assets/cs2_neon_banner.gif" alt="CS2 Pro Autoexec 2026 Neon 60FPS" width="100%"/>
</p>

# ⚡ CS2 Pro Autoexec 2026

<p align="center">
  <a href="https://github.com/Vektor010/cs2-autoexec/releases/latest"><img src="https://img.shields.io/badge/Download-autoexec.zip-2ea44f?style=flat-square&logo=github&logoColor=white" alt="Download autoexec.zip"/></a>
  <a href="https://github.com/Vektor010/cs2-autoexec/releases/tag/v1.0.0"><img src="https://img.shields.io/badge/Release-v1.0.0-16A34A?style=flat-square&logo=git&logoColor=white" alt="Release"/></a>
  <img src="https://img.shields.io/badge/Game-Counter--Strike%202-EA580C?style=flat-square&logo=counter-strike&logoColor=white" alt="CS2"/>
  <img src="https://img.shields.io/badge/Engine-Source%202%20Sub--Tick-0284C7?style=flat-square" alt="Source 2"/>
  <img src="https://img.shields.io/badge/Input%20Lag-Zero%20(Sleep%200)-EC4899?style=flat-square" alt="Zero Lag"/>
  <img src="https://img.shields.io/badge/Display-240Hz%20%7C%20144Hz-9333EA?style=flat-square" alt="Display"/>
  <img src="https://img.shields.io/badge/License-MIT-64748B?style=flat-square" alt="License"/>
</p>

<p align="center">
  <b>Высокопроизводительный модульный соревновательный конфигурационный пакет (Autoexec) для Counter-Strike 2.</b><br/>
  <i>The Ultimate Competitive CS2 Autoexec · Sub-Tick Precision · Zero Input Lag · Smart Keybinds Hub · Premier & Faceit Ready.</i>
</p>

> [!TIP]
> 📥 **Быстрая загрузка:** Чтобы сразу скачать готовый архив со всеми файлами конфигурации и инструкцией, перейдите в [**Релиз v1.0.0**](https://github.com/Vektor010/cs2-autoexec/releases/latest) и скачайте `autoexec.zip`.

---

## 🌟 Почему этот Autoexec лучший для соревновательного CS2?

Большинство старых конфигов созданы ещё для CS:GO и содержат неработающие команды, вызывающие ошибки в консоли и нестабильный фреймтайм. **CS2 Pro Autoexec 2026** построен с нуля под архитектуру **Source 2** и обновления осени 2026 года:

* 🚀 **Zero Input Lag:** `engine_no_focus_sleep 0` — игра не сбрасывает кадры и не засыпает при сворачивании или работе на втором мониторе.
* 🎧 **Точная математика звука:** 10-секундный таймер бомбы рассчитан по квадратичной шкале Source 2 ($0.12^2 = 0.0144$) — ровно 12% в интерфейсе игры.
* 👥 **Командный HUD:** `cl_teamcounter_playercount_instead_of_avatars false` — сверху отображаются все 5 игроков с их полосками здоровья и цветами.
* 🎯 **Спортивный прицел:** Красный `Static Cross 2/2/0` с точкой по центру, совместимый как с классическими, так и с новыми ConVar Valve (`cl_crosshair_length`).
* ⚡ **Smart Keybinds Hub:** Полный набор умных биндов (возврат покупок Backspace, Jumpthrow под большой палец, быстрый дроп C4, полный мут звука Numpad 0).
* 💬 **Умный чат (F10/F11):** Двухрежимный переключатель фраз — ироничный Savage трэш-ток (без мата) для врагов и добрые фразы для коммендов и Trust Factor.

---

## ⌨️ Центр умных биндов (Smart Keybinds Hub)

<p align="center">
  <img src="https://raw.githubusercontent.com/Vektor010/cs2-autoexec/main/assets/cs2_smart_binds.gif" alt="CS2 Smart Keybinds Tactical Setup" width="100%"/>
</p>

Все клавиши распределены по эргономическим зонам для максимального удобства в соревновательных матчах Premier и Faceit:

### 1. 🎯 Боевые действия и перемещение (Combat & Movement)
| Клавиша | Команда / Алиас | Назначение |
| :--- | :--- | :--- |
| **`Left Shift`** | `+duck` | **Присесть** (анатомическая инверсия — снимает нагрузку с мизинца) |
| **`Left Ctrl`** | `+sprint` | **Тихий шаг (Walk)** |
| **`Пробел` / `MWHEELDOWN`** | `+jump` | Двойной прыжок (колёсико вниз для идеального Bhop) |
| **`MWHEELUP`** | `invprev` | Быстрый выбор предыдущего оружия |
| **`C` / `K`** | `-attack` | **Jumpthrow** — идеальный бросок гранаты в прыжке под большой палец |
| **`H`** | `switchhands` | **Смена ведущей руки** (левая / правая) для открытия узких углов |
| **`Стрелки ↑ ↓`** | `incrementvar cl_crosshairsize` | Регулировка длины линий прицела прямо во время матча (шаг 0.5) |
| **`Стрелки ← →`** | `incrementvar cl_crosshairthickness` | Регулировка толщины линий прицела на лету (шаг 0.5) |

### 2. 💣 Бомба и тактические утилиты (Tactical & QoL)
| Клавиша | Команда / Алиас | Назначение |
| :--- | :--- | :--- |
| **`J`** | `+bomb-drop` | **Мгновенный сброс C4** под ноги или тиммейту без доставания бомбы в руки |
| **`X`** | `slot12` | Быстрый выбор аптечки / медицинского шприца (Healthshot) |
| **`MOUSE4`** | `toggle cl_radar_scale` | **Динамический зум радара** (0.35 вся карта ↔ 0.70 детально плент в смоку) |
| **`Left Alt`** | `+voicerecord` | Кнопка рации голосового чата (Push-to-Talk) |
| **`T`** | `+spray_menu` | Меню нанесения граффити |
| **`N`** | `toggleNoclip` | Полёт сквозь стены Noclip со звуковым сигналом (требует `sv_cheats 1`) |

### 3. 🛒 Экономика и умная закупка (Economy & Buy)
| Клавиша | Команда / Алиас | Назначение |
| :--- | :--- | :--- |
| **`Backspace` / `Delete`** | `sellbackall` | **Мгновенный возврат всех покупок** во фризтайме (продать всё и вернуть деньги) |
| **`F3`** | `autobuy` | **Автопокупка** лучшего соревновательного сетапа по слотам |
| **`F4`** | `rebuy` | **Повтор закупки** снаряжения предыдущего раунда |
| **`J` / `U`** | `buy vest` / `buy vesthelm` | Быстрая покупка бронежилета / брони со шлемом |
| **`;` `L` `K` `I` `O`** | `buy rifle0-4` | Закупка винтовок по слотам Loadout без открытия магазина |
| **`P` `,` `/` `.`** | `buy secondary/midtier` | Закупка пистолетов и фарм-ганов без мыши |

### 4. 🔇 Акустика, фокус и звук (Audio & Focus)
| Клавиша | Команда / Алиас | Назначение |
| :--- | :--- | :--- |
| **`Numpad 0`** | `mute_toggle` | **Полный мут / анмут звука игры** (удобно в клатче, в дискорде или в лобби) |
| **`MOUSE5`** | `voiceToggle` | Отключение / включение голосового чата команды |
| **`F5`** | `clutch_mode_toggle` | **Режим Clutch** — заглушить голоса тиммейтов до конца текущего раунда |
| **`=` / `-`** | `volumeUp` / `volumeDown` | Регулировка общей громкости игры с шагом 5% |

### 5. 📊 Телеметрия и сервис (Diagnostics & Service)
| Клавиша | Команда / Алиас | Назначение |
| :--- | :--- | :--- |
| **`Numpad 1`** | `clear` | **Мгновенная очистка консоли разработчика** в один клик |
| **`[` / `F8`** | `debug-hud` | Переключение HUD-телеметрии (FPS, Ping, Loss, Tickrate graphs) |
| **`]` / `F9`** | `debug-console` | Вывод расширенной диагностики сети SDR в консоль |
| **`~` (Тильда)** | `toggleconsole` | Открытие / закрытие консоли |

### 6. 💬 Умный чат (Smart Chat Hub)
| Клавиша | Команда / Алиас | Назначение |
| :--- | :--- | :--- |
| **`F10`** | `tt` | **Отправить следующую фразу в чат** (плавный цикл без спама) |
| **`F11`** | `tt_toggle` | **Переключить режим чата** (😈 Savage трэш-ток ↔ 😇 Wholesome Trust Factor) |

---

## 🗂️ Модульная архитектура проекта

Конфигурация разделена на независимые модули, что исключает конфликты ConVar:

```text
cs2-autoexec/
├── autoexec.cfg            # Главный загрузочный файл с фиксацией параметров
├── ae.cfg                  # Быстрый шорткат для консоли ("ae")
├── knifeMenu.cfg           # Интерактивное меню выдачи кастомных ножей
├── autoexec/               # Модульные конфиги по направлениям
│   ├── aliases.cfg         # Алиасы, быстрые команды и шорткаты
│   ├── audio.cfg           # Акустика, квадратичная шкала, L/R изоляция 75%
│   ├── buybinds.cfg        # Бинды закупки, сброс покупок (sellbackall)
│   ├── crosshair.cfg       # Спортивный прицел (Static Cross 2/2/0 + Dot)
│   ├── game.cfg            # Игровой процесс, настройки лобби и интерфейса
│   ├── hud.cfg             # Радар, телеметрия, 5 карточек игроков вверху
│   ├── keybinds.cfg        # Полная раскладка клавиатуры и мыши
│   ├── mouse_sensitivity.cfg # Сенса, множители осей и масштабирование зума
│   ├── network.cfg         # Sub-tick, буферизация 0 и отключение фейк-регдоллов
│   ├── printMsg.cfg        # Цветная статус-панель в консоли при загрузке
│   ├── trash_talk.cfg      # Двухрежимный пул фраз для чата (RU + EN)
│   ├── video.cfg           # Zero Lag (sleep 0), гамма 2.1, fps_max_ui 240
│   └── viewmodel.cfg       # Кастомное соревновательное расположение оружия
└── gamemodes/              # Специализированные режимы тренировок
    ├── practice.cfg        # Тренировка гранат и раскидок (sv_cheats 1)
    ├── competitive.cfg     # Разминка соревновательного 5v5 матча
    ├── 1v1.cfg             # Дуэльный режим
    ├── kz.cfg              # Кастомный прыжковый режим KZ
    ├── vanilla_kz.cfg      # Ванильный KZ со стандартными параметрами
    ├── bhop.cfg            # Автобаннихоп для тренировки стрейфов
    └── demo_viewer.cfg     # Удобное управление при разборе демок
```

---

## 🚀 Быстрая установка (Quick Install)

### 1. Скачивание
Скачайте архив [`autoexec.zip`](https://github.com/Vektor010/cs2-autoexec/releases/latest) и распакуйте всё его содержимое в каталог конфигураций вашей CS2:
```text
<SteamLibrary>\steamapps\common\Counter-Strike Global Offensive\game\csgo\cfg\
```
*(Либо склонируйте репозиторий: `git clone https://github.com/Vektor010/cs2-autoexec.git`)*.

### 2. Параметры запуска Steam (Launch Options)
Откройте **Steam** ➔ **Библиотека** ➔ ПКМ по **Counter-Strike 2** ➔ **Свойства** ➔ в поле «Параметры запуска» вставьте:
```text
-novid -nojoy +exec autoexec
```

### 3. Проверка в игре
В любой момент в игре откройте консоль (`~`) и введите:
```text
ae
```
В консоли отобразится цветная информационная панель с подтверждением успешной загрузки всех модулей.

---

## 👤 Автор
* **Vektor010** — [GitHub Профиль](https://github.com/Vektor010)
* **Репозиторий:** [Vektor010/cs2-autoexec](https://github.com/Vektor010/cs2-autoexec)

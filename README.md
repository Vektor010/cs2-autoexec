<p align="center">
  <img src="https://raw.githubusercontent.com/Vektor010/cs2-autoexec/main/assets/cs2_neon_banner.png" alt="CS2 Pro Autoexec 2026 Neon 60FPS" width="100%"/>
</p>

<h1 align="center">⚡ CS2 Pro Autoexec 2026</h1>

<p align="center">
  <a href="https://github.com/Vektor010/cs2-autoexec/releases/latest"><img src="https://img.shields.io/badge/Download-autoexec.zip-2ea44f?style=flat-square&logo=github&logoColor=white" alt="Download autoexec.zip"/></a>
  <a href="https://github.com/Vektor010/cs2-autoexec/releases/tag/v1.1.0"><img src="https://img.shields.io/badge/Release-v1.1.0-16A34A?style=flat-square&logo=git&logoColor=white" alt="Release"/></a>
  <img src="https://img.shields.io/badge/Game-Counter--Strike%202-EA580C?style=flat-square&logo=counter-strike&logoColor=white" alt="CS2"/>
  <img src="https://img.shields.io/badge/Engine-Source%202%20Sub--Tick-0284C7?style=flat-square" alt="Source 2"/>
  <img src="https://img.shields.io/badge/Input%20Lag-Zero%20(Sleep%200)-EC4899?style=flat-square" alt="Zero Lag"/>
  <img src="https://img.shields.io/badge/Display-240Hz%20%7C%20144Hz-9333EA?style=flat-square" alt="Display"/>
  <img src="https://img.shields.io/badge/License-MIT-64748B?style=flat-square" alt="License"/>
</p>

<p align="center">
  <b>Высокопроизводительный модульный соревновательный конфигурационный пакет (Autoexec) для Counter-Strike 2.</b><br/>
  <i>The Ultimate Competitive CS2 Autoexec · Pro Players Settings (donk, ZywOo, sh1ro, m0NESY) · Sub-Tick Precision · Zero Input Lag · Smart Keybinds Hub · Premier & Faceit Ready.</i>
</p>

> [!TIP]
> 📥 **Быстрая загрузка:** Чтобы сразу скачать готовый архив со всеми файлами конфигурации и инструкцией, перейдите в [**Релиз v1.1.0**](https://github.com/Vektor010/cs2-autoexec/releases/latest) и скачайте `autoexec.zip`.

---

## 🌟 Главные фишки конфига (Pro Features & Highlights)

Никакого мусора и неработающих команд из CS:GO. Конфиг собран с нуля под **Source 2** на основе актуальных соревновательных сетапов мировой про-сцены (**donk**, **ZywOo**, **sh1ro**, **m0NESY**):

* 🚀 **Максимум FPS & Zero Lag:** `engine_no_focus_sleep 0` и `cl_net_buffer_ticks 0` — задержка ввода сведена к абсолютному нулю, идеальный фреймтайм без микрофризов и просадок даже при Alt+Tab и втором мониторе.
* 🎧 **Кристально чистый звук:** Пресет эквалайзера **Crisp EQ** выводит шаги врагов и чеку гранат на передний план, отсекая басовый гул взрывов. Стереоизоляция 75% даёт идеальный азимут звука, а 10-секундный таймер бомбы откалиброван на комфортные 12% (не глушит уши в клатче). Плюс плавный ступенчатый микшер громкости на `=` / `-`!
* 🎯 **Турнирный прицел + Фикс оптики:** Красный `Static Cross 2/2/0` с точкой. Исправлен баг CS2 с исчезающей точкой в зуме **AUG / SG 553** (`cl_ironsight_dot_scale 1`), установлены чёткие риски AWP без мыла в движении и быстрая подстройка размера стрелками прямо в раунде.
* ⌨️ **Умные киберспортивные бинды (Smart Binds):**
  * 💣 **Мгновенный сброс пачки (`J`):** Дроп C4 тиммейту под ноги за долю секунды без доставания бомбы в руки.
  * 🤸 **Jumpthrow sh1ro (`Пробел + C / K`):** Идеальные раскидки гранат под большой палец со 100% повторяемостью.
  * 🔄 **Анатомическая инверсия `Shift / Ctrl`:** Приседание на длинный Shift снимает напряжение с мизинца при крауч-мувменте.
  * 🔇 **Быстрый мут (`Numpad 0`) & Режим Clutch (`F5`):** Заглушить звук игры в дискорде или замутить тиммейтов в клатче 1vX одной кнопкой.
  * 🛒 **Возврат покупок (`Backspace` / `Del`):** Мгновенная отмена всех покупок во фризтайме, если мискликнул в магазине.
* 🖥️ **Соревновательный минимализм интерфейса (Clean HUD):** Радар на 0.40 охватывает всю карту сразу (динамический зум на `MOUSE4`), вверху отображаются 5 подробных карточек тиммейтов с полосками HP и цветами, а весь отвлекающий визуальный мусор убран.
* 💬 **Умный чат (`F10 / F11`):** Переключатель в один клик между ироничным трэш-током для врагов (без мата) и добрыми фразами для коммендов и прокачки Trust Factor.

---

## 🎯 Киберспортивный прицел и оптика (Pro Crosshair & Optics)

Прицел выверен для максимальной концентрации и точности попаданий в голову в соревновательном режиме Premier и на Faceit:

| Параметр ConVar | Значение | Описание |
| :--- | :--- | :--- |
| `cl_crosshairstyle` | `4` | Статический спортивный стиль (Static Cross — не расширяется при беге) |
| `cl_crosshairsize` | `2` | Оптимальная соревновательная длина линий (2 px) |
| `cl_crosshairthickness` | `2` | Плотная толщина линий для превосходной читаемости на светлых текстурах |
| `cl_crosshair_gap` | `0` | Нулевой зазор (перекрестие идеально сфокусировано) |
| `cl_crosshairdot` | `1` | Чёткая точка в самом центре перекрестия |
| `cl_crosshair_drawoutline` | `false` | Без внешней обводки — максимальная прозрачность рабочей зоны обзора |
| `cl_crosshair_t` | `false` | Классический симметричный 4-лучевой крест (не Т-образный) |
| `cl_crosshair_recoil` | `0` | Прицел строго зафиксирован по центру экрана (НЕ следует за отдачей) |
| `cl_crosshaircolor_r/g/b` | `255 / 0 / 0` | Чистый красный контрастный цвет |
| `cl_crosshairalpha` | `255` | 100% непрозрачность |
| `cl_crosshair_sniper_width` | `1` | Тонкие соревновательные риски в снайперском зуме (AWP, SSG 08) |
| `cl_sniper_show_inaccuracy` | `0` | Отключение размытия перекрестия в зуме при движении |
| `cl_ironsight_dot_scale` | `1` | **Исправлена видимость точки в зуме AUG и SG 553** (стандартный масштаб 1.0) |
| `cl_ironsight_usecrosshaircolor` | `true` | Точка в коллиматорах AUG / SG 553 совпадает с красным цветом прицела |
| `cl_grenadecrosshair_*` | `false` | Прицелы для гранат отключены для максимальной чистоты обзора |
| `cl_show_observer_crosshair` | `2` | Отображение прицелов наблюдаемых игроков в спектаторах |

> [!NOTE]
> 🎛️ **Быстрая подстройка прицела прямо во время раунда:**
> * **Стрелки `↑` / `↓`:** Мгновенно увеличивают или уменьшают длину линий прицела с шагом `0.5`.
> * **Стрелки `←` / `→`:** Мгновенно сужают или расширяют зазор перекрестия (Gap) с шагом `1 px`.

```text
// Быстрая установка прицела одной строкой в консоль игры:
crosshair 1; cl_crosshairstyle 4; cl_crosshairdot 1; cl_crosshairsize 2; cl_crosshairthickness 2; cl_crosshair_gap 0; cl_crosshair_drawoutline 0; cl_crosshair_t 0; cl_crosshair_recoil 0; cl_crosshairalpha 255; cl_crosshaircolor_r 255; cl_crosshaircolor_g 0; cl_crosshaircolor_b 0; cl_crosshair_sniper_width 1; cl_sniper_show_inaccuracy 0; cl_ironsight_usecrosshaircolor 1; cl_ironsight_dot_scale 1
```

---

## ⌨️ Центр умных биндов (Smart Keybinds Hub)

<p align="center">
  <img src="https://raw.githubusercontent.com/Vektor010/cs2-autoexec/main/assets/cs2_smart_binds.png" alt="CS2 Smart Keybinds Tactical Setup" width="100%"/>
</p>

Все клавиши распределены по эргономическим зонам для максимального удобства в соревновательных матчах Premier и Faceit:

### 1. 🎯 Боевые действия и перемещение (Combat & Movement)
| Клавиша | Команда / Алиас | Назначение |
| :--- | :--- | :--- |
| **`Left Shift`** | `+duck` | **Присесть** (анатомическая инверсия — снимает нагрузку с мизинца) |
| **`Left Ctrl`** | `+sprint` | **Тихий шаг (Walk)** |
| **`Пробел` / `MWHEELDOWN`** | `+jump` | Двойной прыжок (колёсико вниз для идеального Bhop) |
| **`MWHEELUP`** | `invprev` | Быстрый выбор предыдущего оружия |
| **`C` / `K`** | `-attack` | **Jumpthrow** — идеальный бросок гранаты в прыжке под большой палец (схема sh1ro) |
| **`H`** | `switchhands` | **Смена ведущей руки** (левая / правая) для открытия узких углов |
| **`Стрелки ↑ ↓`** | `incrementvar cl_crosshairsize` | Регулировка длины линий прицела прямо во время матча (шаг 0.5) |
| **`Стрелки ← →`** | `incrementvar cl_crosshairgap` | Регулировка зазора прицела на лету (сузить / расширить Gap, шаг 1 px) |

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
├── knifeMenu.cfg           # Интерактивное меню выдачи кастомных ножей
├── autoexec/               # Модульные конфиги по направлениям
│   ├── aliases.cfg         # Алиасы, быстрые команды и шорткаты
│   ├── audio.cfg           # Акустика, квадратичная шкала, L/R изоляция 75%
│   ├── buybinds.cfg        # Бинды закупки, сброс покупок (sellbackall)
│   ├── crosshair.cfg       # Спортивный прицел и калибровка оптики (AUG/SG/AWP)
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

<div align="center">

## 🌐 Сообщество и полезные ресурсы

<a href="https://t.me/nexcorepc" target="_blank">
  <img src="https://img.shields.io/badge/Telegram-NexCore%20PC-24A1DE?style=for-the-badge&logo=telegram&logoColor=white" alt="Telegram"/>
</a>
&nbsp;&nbsp;
<a href="https://www.youtube.com/@Skylake159" target="_blank">
  <img src="https://img.shields.io/badge/YouTube-Skylake159-FF0000?style=for-the-badge&logo=youtube&logoColor=white" alt="YouTube"/>
</a>

<br/><br/>

<b>Разборы настроек, оптимизация железа и максимальный FPS:</b>

<p align="center">
  📺 <b><a href="https://www.youtube.com/@Skylake159">YouTube-канал (@Skylake159)</a></b> — подробные видеогайды по уничтожению Input Lag, оптимизации Windows и тестам производительности в CS2.<br/>
  💬 <b><a href="https://t.me/nexcorepc">Telegram-канал (NexCore PC)</a></b> — свежие апдейты соревновательного конфига, полезные твики, драйверы и помощь по настройке ПК.
</p>

</div>

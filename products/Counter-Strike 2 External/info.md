# PhantomHack — Counter-Strike 2 External

🟢 **Status:** Undetected

🔵 **OS:** Windows 10 / Windows 11 (All builds)

🔴 **Architecture:** Kernel-Level (System Driver)

![](https://img2.teletype.in/files/db/72/db72d14d-d856-4ae6-8124-267e66e387e5.png)

---

## 🇺🇸 English Description

PhantomHack: Counter-Strike 2 External is a premium, high-performance security-focused software designed for competitive edge. Operating strictly at the system kernel level (Kernel-Mode Driver), it ensures maximum safety, bypasses standard user-mode detections, and guarantees rock-solid stability.

**Key Advantages:**

- **Kernel-Level Execution** — The cheat operates via a custom kernel driver, separating its memory operations from user-mode anti-cheat detection routines.
- **True External Overlay** — Seamlessly renders overlay visuals in Windowed, Borderless, and Fullscreen modes without causing performance drops or screen flickering.
- **Universal OS Support** — Fully optimized and compatible with Windows 10 and Windows 11 (all latest builds).
- **Advanced Configuration System** — Highly flexible, dynamic configuration profiles with per-weapon group and per-weapon individual override support.

---

## 🇷🇺 Описание на Русском

PhantomHack: Counter-Strike 2 External — это высокотехнологичное приватное ПО, созданное для получения максимального преимущества в игре. Благодаря работе исключительно на уровне ядра системы (Kernel-Mode Driver), софт обеспечивает наивысшую степень безопасности, обходит стандартные методы обнаружения anti-cheat систем и гарантирует абсолютную стабильность.

**Ключевые преимущества:**

- **Работа на уровне ядра (Kernel)** — Чит использует кастомный драйвер ядра, изолируя свои процессы от систем обнаружения античитов в user-mode.
- **Полноценный External Оверлей** — Визуальные функции корректно отображаются во всех режимах игры — В окне и в окне без рамки без потери FPS.
- **Универсальная совместимость** — Полная поддержка и оптимизация для Windows 10 и Windows 11 (включая последние обновления).
- **Гибкая система настроек** — Динамическое сохранение конфигураций с поддержкой профилей по группам оружия и отдельных оверрайдов на каждый ствол.

---

## 🛠 Feature List / Список функций

---

![](https://img1.teletype.in/files/4d/0a/4d0aeddd-f1be-4cf1-9cac-98e78a0225d9.png)

![](https://img4.teletype.in/files/b0/bc/b0bca151-03e6-4151-8a8a-81dc122e0fcd.png)

### 1. Aimbot & Weapon Control / Аимбот и Контроль Оружия

Full-featured aimbot system running each frame alongside the triggerbot. Supports a global profile, per-weapon-group profiles and individual per-weapon overrides — each with its own fully independent set of settings below.

_Полнофункциональный аимбот, работающий каждый кадр совместно с триггерботом. Поддерживает глобальный профиль, профили по группам оружия и индивидуальные оверрайды на каждый ствол — каждый с полностью независимым набором настроек ниже._

- 🔥 **Global / Profile Activation / Глобальная активация** — Bind to any key, individual switches for weapon-group and per-weapon profiles. _Привязка к любым клавишам, раздельные тумблеры под профили групп и отдельных стволов._
- 🎯 **Smart Target Priority / Умный приоритет целей** — FOV/Crosshair distance vs World Distance. _Выбор приоритета: по дистанции от прицела или расстоянию до игрока._
- 📈 **Smooth & FOV Adjustments / Настройка Smooth и FOV** — Humanized customization for legit play. _Настройка плавности и радиуса (фова) для максимально легитной игры._
- 🦴 **Bone Selection & Multipoint / Выбор костей и мультипоинты** — Head, Neck, Chest, Spine, Pelvis, Limbs. _Наведение на голову, шею, грудь, таз, конечности и сканирование нескольких точек._
- 👁 **Visibility Check / Проверка на видимость** — Aim only at exposed targets. _Срабатывание аима только по видимым противникам (не наводит через стены)._
- 👥 **Team Filtering / Фильтрация союзников** — Toggle shooting teammates. _Возможность включения или отключения наводки на свою команду._
- 🕹 **Advanced RCS / Продвинутый контроль отдачи** — Standalone or aim-assist recoil system (X/Y scale, start/end bullet). _Настройка контроля отдачи по осям X/Y с выбором пули старта/конца спрея._
- 🔮 **Motion Prediction / Предсказание движения** — Velocity-based target lead with auto distance scaling (0–300 ms, adjustable per weapon). _Прогнозирование положения цели по вектору скорости с автоматической масштабировкой по дистанции._
- 🔫 **Per-Weapon Overrides / Индивидуальные оверрайды** — Fully independent aimbot profile for any individual weapon on top of group profiles. _Полностью независимый профиль аима для любого конкретного оружия поверх профилей групп._

---

### 2. Triggerbot / Триггербот

Automatic fire trigger that activates when the crosshair lands on an enemy. Runs non-blocking inside the main update loop and uses a CPU-side mesh raycast to confirm the hit before firing.

_Автоматический триггер выстрела, срабатывающий при попадании прицела на врага. Работает без блокировок внутри основного игрового цикла и подтверждает попадание через CPU-рейкаст по сетке модели перед выстрелом._

- ⏱ **Custom Delays / Кастомные задержки** — Adjustable pre-shot and post-shot delays (ms). _Настройка задержки перед выстрелом и после выстрела в миллисекундах._
- 🛡 **Visibility & Team Checks / Проверки видимости и команды** — Avoid accidental team damage or wall shots. _Проверка, виден ли враг, и полное игнорирование союзников._
- 🎯 Mesh Inset Accuracy / Глубина попадания по сетке — CPU-side skinned-mesh raycast with a bone-axis ratio threshold — triggers only on a real hit against the body, not on its edges. Рейкаст по скиннированной сетке на стороне CPU с порогом по оси кости — срабатывает только при реальном попадании по телу, а не по его краям.

---

### 3. Visuals / ESP / Визуальные функции

Separate independent settings for Team (Союзников), Enemy (Врагов) and World (Окружающего мира).

---

![](https://img3.teletype.in/files/a0/15/a015c18e-4348-42a3-bddd-56dbadd65826.png)

👤 Player ESP / Визуализация игроков

Per-player rendering layer with every element independently toggleable and separately configured for Team and Enemy. Colors, sizes and positions are all fully customizable.

_Слой отображения игроков с независимым включением каждого элемента и отдельными настройками для союзников и врагов. Цвета, размеры и расположение полностью настраиваются._

- **Box ESP** — Fully customizable boxes (Normal / Cornered / 3D styles, customizable thickness, outlines, padding, and colors). _Настраиваемые боксы (Обычные, Угловые, 3D, регулировка толщины, обводки, отступов и цветов)._
- **Skeleton & Joint Overlay** — Accurate bone rendering with optional joint circles and specific color states. _Скелеты игроков с отображением суставов и кастомным радиусом/цветом._
- **Health & Armor Bars** — Dynamic position layout (Left, Right, Top, Bottom) with gradient support and text value indicators. _Полосы здоровья и брони с поддержкой градиента и текстового отображения._
- **Name & Weapon Text** — Renders player names, active weapon type (text / icon / icon+text), ammo bar. _Отображение никнеймов, текущего оружия в трёх режимах и полоска оставшихся патронов._
- **Player Flags** — Configurable status badges: Armor, Flashed, Scoped, Defusing, Reloading, Bomb Carrier, Defuse Kit. _Настраиваемые статус-теги: Броня, Ослеплён, Скоуп, Разминирует, Перезаряжает, Несёт бомбу, Набор сапёра._
- **Distance Tracker** — Displays distance to target with configurable units (meters/feet/units). _Дистанция до целей с выбором единиц измерения (метры / футы / юниты)._
- **Visible Check Color Swapping** — Automatically changes ESP colors if an enemy is behind a wall or visible. _Автоматическая смена цвета боксов/скелетов в зависимости от видимости (Visible/Invisible)._
- **Out of Field of View (OOF) Arrows** — Indicators pointing to enemies outside your screen view with radius and size controls. _Стрелки-индикаторы, показывающие направление на врагов вне зоны видимости экрана._

---

#### 🎨 Chams / GPU-рендеринг игроков

GPU-rendered player highlighting with separate Visible and Hidden layers. Styles: Textured, Flat, Metallic, Wireframe, Glow Blend. Keybind-controlled, separate for Team and Enemy.

_Подсветка игроков через GPU с раздельными слоями видимости и скрытия. Стили: Текстурный, Плоский, Металлик, Каркас, Свечение. Управление по бинду, раздельно для союзников и врагов._

- **Chams Hit & Kill FX** — Triggered visual effects (Freeze / Dissolve) on hitting or killing a target — configurable style, color, duration, intensity and noise scale. _Визуальные эффекты при попадании и убийстве (Заморозка / Растворение) — настраиваемый стиль, цвет, длительность, интенсивность и масштаб шума._

---

#### 🔊 Sound ESP / Звуковой радар

Tracks enemy steps, shots, and movements in real-time. Displays pulsing expanding rings at the sound origin point. Includes interval controls and custom timings.

_Отслеживание шагов, выстрелов и движений врагов. Отображает пульсирующие круги в точке источника звука на карте с настройкой времени затухания._

---

![](https://img3.teletype.in/files/6c/59/6c598a23-cf11-46d3-9fa3-644531258681.png)

🌎 World ESP / Окружающий мир

ESP layer for in-world objects independent of players. Each element has its own enable toggle, color and size controls.

_Слой ЕСП для объектов в мире, независимый от игроков. Каждый элемент имеет свой переключатель, настройку цвета и размера._

- **Bomb Tracker** — Clear highlighting of C4 explosives. _Отображение бомбы C4._
- **Grenade ESP** — Custom filters for HE Grenades, Smokes, Molotovs / Incendiary, Flashes and Decoys. _Подсветка гранат всех типов с раздельной фильтрацией: ФРАГи, дымы, молотовы / зажигательные, флешки и декои._
- **Dropped Weapons** — Displays weapons on the ground with customizable font sizing and colors. _Отображение оружия, лежащего на земле, с регулировкой размера шрифта._

---

### 4. Grenade Helper / Lineup System / Помощник гранат

![](https://img3.teletype.in/files/a5/11/a511eade-a61c-4b12-b187-952f33c188aa.png)

Built-in grenade lineup assistant with per-map storage, real-time visual overlays and a full in-menu creator. Automatically loads the correct lineup set when the map starts and guides you to the exact stand spot and aim angle for every stored throw.

_Встроенный помощник раскидок с хранением по картам, визуальными оверлеями в реальном времени и полноценным редактором прямо в меню. Автоматически подгружает нужный набор линапов при смене карты и ведёт к точке позиции и углу прицела для каждого броска._

- 🎯 **Map-Aware Lineup Loading / Автозагрузка по карте** — Lineups are stored per map and loaded automatically on map start. _Раскидки хранятся отдельно под каждую карту и загружаются автоматически при входе._
- 📍 **Stand Position Circles / Круги позиции** — 3D ground ring projected to screen; turns green when player stands inside the correct spot. _3D-круг на земле, проецируется на экран; зеленеет, когда игрок стоит в нужной точке._
- 🎯 **Aim Overlay / Прицельный оверлей** — Projected aim circle with line from screen centre; turns green when crosshair is on target. _Прицельный круг с линией от центра экрана; зеленеет при попадании прицела в точку._
- 🔄 **Multi-Throw Selector / Мультибросок** — Multiple lineups sharing the same stand position are grouped; auto-selects the closest to crosshair. _Несколько раскидок с одной позиции группируются; автовыбор ближайшего к прицелу._
- 🤖 **Auto-Aim / Автоприцел** — Keybind-controlled smooth auto-aim to lineup angles with adjustable speed. _Автоматический плавный прицел на нужные углы по бинду с регулировкой скорости._
- ✏️ **Lineup Creator & Editor / Создание и редактирование** — In-menu panel to save, edit, rename and delete lineups with multilingual titles (EN/RU/UK/ZH) and descriptions. _Панель в меню для сохранения, редактирования, переименования и удаления раскидок с поддержкой мультиязычных названий и описаний._
- 🔍 **Search & Filter / Поиск и фильтр** — Real-time search across lineup names, types, throw styles, and file names. _Поиск в реальном времени по названию, типу гранаты, броску и имени файла._

---

### 5. Misc / Разное

![](https://img4.teletype.in/files/b5/c8/b5c8f6c5-2dee-4d37-b119-4dc1832be44e.png)

- 👁 **Spectator List / Список спектаторов** — Draggable on-screen overlay showing players currently spectating you or your POV, with Steam avatar loading. _Перетаскиваемый оверлей на экране со списком игроков, которые смотрят на вас или вашу камеру; автозагрузка аватаров Steam._
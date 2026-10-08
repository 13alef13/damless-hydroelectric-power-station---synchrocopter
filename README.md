# Sub-Ice Synchropter HPS (Hydro Power Station)
### Developed by Engineering Bureau 13/13 in collaboration with Google AI

An innovative, eco-friendly, and dam-free micro-hydroelectric power plant designed for small rivers (5–10 meters wide) operating in harsh northern and arctic climates.

## Core Concept
The system uses a vertical dual-rotor configuration based on the **Anton Flettner synchropter** intermeshing rotor scheme. The entire blade module is completely submerged below the river's water level, allowing it to generate electricity year-round, completely unaffected by surface ice or sub-zero atmospheric temperatures.

### Key Features
* **Dam-Free Design:** Eliminates the need for concrete dams, significantly reducing installation costs and legal barriers.
* **Eco & Fish-Friendly:** The slow-turning intermeshing rotors leave safe corridors near the riverbanks and above the module for fish migration and spawning.
* **Bypassing the Betz Limit:** Due to synchronized counter-rotating blades and underwater guide screens, the fluid is compressed in the central zone. This creates a hydrodynamic lock, transforming kinetic energy into steady head pressure and extracting significantly more energy than isolated open-stream turbines.
* **Sub-Ice Operation:** The mechanical module operates entirely in the liquid water layer under the ice sheets, while the gearboxes and generators are mounted on an above-water dry platform for easy maintenance.

## Technical Specifications
* **Turbine Type:** Vertical counter-rotating blades (modified Savonius-type curved impellers).
* **Rotation Direction:** Left rotor rotates clockwise; right rotor rotates counter-clockwise.
* **Synchronization:** Specialized dual-shaft intermeshing gearbox with a planetary multiplier to boost low RPM directly to a permanent magnet wind-turbine generator.
* **Target River Profile:** Width: 5–10 m, Depth: $\ge$ 1 m, Flow speed: $\ge$ 1.0 m/s.

## Modular Installation
The HPS is designed as a rigid structural frame ("drop-and-go" layout). The assembly is lowered into the riverbed via a mobile crane and secured with shore anchors or retaining piles, requiring zero underwater construction or concrete works.

## Future Applications & Innovations

### 1. Dynamic Folding Blades (EB 13/13 Innovation)
To radically increase the efficiency of vertical rotors, the system utilizes **actively folding blades equipped with one-way travel limiters**:
* **Power Phase (Center Stream):** The oncoming water flow unfolds the blade until it hits a rigid structural stop, creating maximum hydraulic resistance and a hydrodynamic lock together with the opposing rotor.
* **Recovery Phase (Along Riverbanks):** As the blade moves against the current during its return cycle, the oncoming flow automatically folds it. This reduces the parasitic drag of the returning rotor side close to zero, significantly boosting net torque on the drive shaft.

### 2. Dual-Circuit Cooling for Distributed Edge Data Centers
Modular HPS units are tailored for direct power supply of containerized data centers (10–50 kW) in ultra-remote locations, requiring zero local infrastructure:
* **Combined Climate Control:** During cold seasons, the servers utilize free air cooling. In summer peaks or ambient heat up to +40°C, the system seamlessly switches to **direct river water liquid cooling**.
* **Hydrothermal Stability:** The water temperature of small northern rivers rarely tops +25°C even in peak summer. Utilizing river water through isolated heat exchangers guarantees optimal thermal management for hardware year-round.
* **Heat Recovery (Optional):** Low-grade heat from the data center cooling loop (40–50°C) can be redirected to heat residential buildings, field camps, or greenhouses, achieving complete carbon neutrality.

### 3. Geometric Optimization and Resistance to Channel Debris
The blades' ability to fold to one side offers unique operational advantages:
* **Maximization of Swept Area:** The vertical rotor shafts can be offset close to the shoreline. When idle, the blades fold parallel to the shore, increasing their overall length and utilizing up to 95% of the channel's useful hydrodynamic cross-section.
* **Passive protection against destructive debris (evasion effect):** When encountering large floating debris (logs, driftwood), the blade does not block the rotor and is not deformed. An oncoming solid object forces the blade to fold toward the idle position as it passes, after which the hydraulic flow instantly returns it to its open position.

### 4. Intelligent data center climate control: Turbo Boost and Night Modes
The edge data center's heat management system is synchronized with daily and seasonal temperature fluctuations:
* **Turbo Boost Mode:** Activated during peak summer heat periods (up to +40°C). The automatic system starts the pumps of the flow-through river cooling circuit. A stable water temperature ($\le$ +25°C) ensures emergency cooling of the chips, preventing throttling and increasing computing power.
* **Night Mode:** Activates at night when the air temperature drops by 10–15°C. The system switches to Free Cooling using outside air, completely shutting off the water pumps. This minimizes parasitic power consumption by the hydroelectric power plant for data center maintenance, freeing up useful power for AI computing. 

## License
This project is licensed under the MIT License - see the LICENSE file for details.

---

---

# Подлёдная ГЭС-Синхрокоптер
### Разработано в Engineering Bureau 13/13 совместно с Google AI

Инновационная, экологически безопасная бесплотинная микро-гидроэлектростанция, предназначенная для малых рек (шириной от 5 до 10 метров), адаптированная для работы в суровых условиях северных и арктических регионов.

## Основная концепция
Система использует вертикальную двухроторную конфигурацию, основанную на авиационной схеме синхроптера (перекрещивающихся роторов) Антона Флеттнера. Весь лопастной модуль полностью погружается ниже уровня воды, что позволяет вырабатывать электроэнергию круглый год, независимо от поверхностного льда и отрицательных температур воздуха.

### Ключевые преимущества
* **Бесплотинная конструкция:** Исключает необходимость строительства бетонных дамб, что в разы снижает стоимость установки и упрощает экологическое согласование.
* **Рыбоходность и безопасность:** Медленно вращающиеся перекрещивающиеся роторы оставляют безопасные коридоры у берегов и над модулем для свободной миграции и нереста рыбы.
* **Обход предела Бетца:** Благодаря синхронному противоположному вращению лопастей и направляющим щитам поток сжимается в центральной зоне. Создается гидродинамический «замок», превращающий кинетическую энергию в локальный напор, что позволяет забрать у реки значительно больше энергии, чем классическое одиночное колесо.
* **Подлёдная эксплуатация:** Механическая часть работает в толще воды под ледяным панцирем, а редукторы и генератор вынесены на сухую надводную платформу для простоты обслуживания.

## Технические характеристики
* **Тип турбины:** Вертикальные встречно-вращающиеся лопасти (изогнутые лепестки по типу ротора Савониуса).
* **Направление вращения:** Левый ротор — по часовой стрелке, правый — против часовой стрелки.
* **Синхронизация:** Специализированный двухвальный редуктор конического типа, объединенный с планетарным мультипликатором для разгона низких оборотов вала до номинала генератора на постоянных магнитах.
* **Параметры русла:** Ширина: 5–10 м, Глубина: $\ge$ 1 м, Скорость течения: $\ge$ 1.0 м/с.

## Модульная установка
ГЭС спроектирована в виде единой жесткой рамной кассеты (принцип «опустил и забыл»). Моноблок доставляется на место, сбрасывается краном-манипулятором в русло и фиксируется береговыми растяжками или опорными сваями. Никаких водолазных и бетонных работ не требуется.

## Перспективы применения и технологические инновации / Future Applications & Innovations

### 1. Складные лопасти динамического сопротивления (Инновация EB 13/13)
Для радикального повышения КПД вертикальных роторов применяется система **активно-складных лопастей с односторонним ограничителем хода**:
* **Рабочая фаза (Центр русла):** Набегающий поток воды раскрывает лопасть до жесткого упора-ограничителя, формируя максимальное гидравлическое сопротивление и гидродинамический «замок» в паре со вторым ротором.
* **Холостая фаза (Вдоль берегов):** При движении лопасти навстречу течению (возвратный цикл), встречный поток воды автоматически складывает лопасть. Это снижает паразитное лобовое сопротивление возвращающейся стороны ротора почти до нуля, резко увеличивая суммарную крутящую мощность на валу.

### 2. Двухконтурное охлаждение распределенных Edge-ЦОД
Модульные ГЭС адаптированы под прямое энергоснабжение контейнерных дата-центров (10–50 кВт) в условиях полной автономности (Off-grid), даже при отсутствии инфраструктуры и населенных пунктов:
* **Комбинированный климат-контроль:** В холодное время года электроника использует бесплатное воздушное охлаждение (Free Cooling). В летний период или при аномальной жаре до +40°C система автоматически переключается на **жидкостное охлаждение проточной речной водой**.
* **Гидротермальная стабильность:** Температура воды в малых северных реках редко поднимается выше +25°C в самый жаркий период. Использование речной воды через изолированные теплообменники гарантирует идеальный теплоотвод для серверов круглый год.
* **Утилизация тепла (При наличии потребителей):** Низкопотенциальное тепло из контура охлаждения ЦОД (40–50°C) может быть направлено на обогрев жилых домов, вахтовых поселков или теплиц, обеспечивая полную углеродную нейтральность.

### 3. Геометрическая оптимизация и устойчивость к русловому мусору
Свойство лопастей складываться в одну сторону открывает уникальные эксплуатационные преимущества:
* **Максимизация площади ометания:** Вертикальные валы роторов могут быть смещены вплотную к береговой линии. В холостой фазе лопасти складываются параллельно берегу, что позволяет увеличить их общую длину и задействовать до 95% полезного гидродинамического сечения русла.
* **Пассивная защита от деструктивного мусора (Эффект уклонения):** При столкновении с крупным плывущим мусором (бревна, топляк) лопасть не блокирует ротор и не деформируется. Встречный твердый предмет принудительно складывает лопасть в сторону холостого хода, пролетая мимо, после чего гидропоток мгновенно возвращает её в рабочее раскрытое состояние.

### 4. Интеллектуальный климат-контроль ЦОД: Режимы «Turbo Boost» и «Night Mode»
Система управления теплоотводом периферийного ЦОД синхронизирована с суточными и сезонными колебаниями температур:
* **Режим «Turbo Boost»:** Активируется в периоды пиковой летней жары (до +40°C). Автоматика запускает насосы проточного речного контура охлаждения. Стабильная температура воды ($\le$ +25°C) обеспечивает экстренное охлаждение чипов, предотвращая троттлинг и повышая вычислительную мощность.
* **Режим «Night Mode»:** Включается в ночное время при падении температуры воздуха на 10–15°C. Система переходит на Free Cooling забортным воздухом, полностью отключая водяные насосы. Это минимизирует паразитное энергопотребление ГЭС на обслуживание ЦОД, высвобождая полезную мощность для ИИ-вычислений.


## Лицензия
Этот проект распространяется под свободной лицензией MIT — подробности см. в файле LICENSE.



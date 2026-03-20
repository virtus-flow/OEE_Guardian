## СРПСКИ ЈЕЗИК

Аутоматизовани систем за праћење ОЕЕ (укупне ефикасности опреме) у реалном времену, изграђен на n8n платформи. Систем трансформише сирове импулсе индустријских машина у извршне информације, пружајући метрику уживо, аларме за застоје и аутоматизовано извештавање путем Телеграма.

Кључне карактеристике:

 - **Интеграција путем Webhook-а**: Хватање импулса машина са милисекундном прецизношћу.
 - **Трострука логика праћења**:
  - **Live Engine**: Прорачун ОЕЕ-а, перформанси и квалитета у реалном времену.
  - **Sentinel Watchdog**: Аутоматска детекција застоја (нивои: 3мин / 15мин / 60мин).
  - **Pulse Reporting**: Сатни и сменски извештаји директно на мобилне уређаје.
 - **Динамичко управљање сменама**: Аутоматско препознавање Прве, Друге и Треће смене са интегрисаним планом пауза.
 - **Чување података**: SQL праћење сваког произведеног комада и сваког минута застоја.

---

### Повраћај инвестиције – Virtus OEE Guardian
Овај систем није само технички алат, већ директан генератор профита кроз четири кључна фактора:

1. **Смањење непланираних застоја (MTTR)** 🛑
Проблем: Без система, пословође сазнају за застој тек приликом обиласка линије (кашњење од 10-20 минута).

Решење: „Sentinel Watchdog” шаље аларм на Телеграм већ након 3 минута тишине.

Финансијски ефекат: Смањење времена застоја за 15-20%. Ако сат застоја линије кошта 500€, систем само једним алармом исплаћује целу месечну инфраструктуру.

2. **Дигитализација и уштеда радног времена** ⏳
Проблем: Вође смена троше у просеку 30-60 минута дневно на ручно попуњавање папирних извештаја и рачунање ОЕЕ-а.

Решење: Аутоматски „Satni Pulse” и извештаји на крају смене елиминишу ручни рад.

Финансијски ефекат: Уштеда од преко 40 радних сати месечно по линији. То је пола радног места које се сада може фокусирати на оптимизацију, а не на администрацију.

3. **Елиминација „микро-застоја” кроз већи квалитет** 📉
Проблем: Машина која ради спорије од задатог такта (нпр. 20с уместо 15с) „краде” профит, а то је невидљиво на папиру.

Решење: Систем сваки циклус дужи од 15с аутоматски маркира као губитак перформанси.

Финансијски ефекат: Повећање укупног ОЕЕ-а за 5-8% кроз прецизно фино подешавање машине на основу стварних података.

4. **Драстична уштеда на софтверским лиценцама** 💰
Проблем: Комерцијални ОЕЕ/MES системи (нпр. SAP, Wonderware) коштају између 5.000€ и 15.000€ по линији годишње.

Решење: Virtus OEE Guardian користи n8n (Open Source / Low Cost) технологију.

Финансијски ефекат: Уштеда на лиценцама износи преко 90% у поређењу са традиционалним индустријским решењима.


---

##English

An automated, real-time OEE (Overall Equipment Effectiveness) monitoring engine built on n8n. This system transforms raw machine pulses into actionable intelligence, providing live metrics, downtime alerts, and automated shift reporting via Telegram.

Key Features:
 - **Real-time Webhook Integration**: Captures industrial machine pulses with sub-second latency.
 - **Triple-Track Logic**:
   - **Live Engine**: Real-time OEE, Performance, and Quality calculations.
   - **Sentinel Watchdog**: Automated downtime detection (3min/15min/60min tiers).
   - **Pulse Reporting**: Hourly and Shift-end summaries delivered to mobile devices.
 - **Dynamic Shift Management**: Automated detection of morning, afternoon, and night shifts with custom break handling.
 - **Data Persistence**: SQL-based tracking of every production unit and downtime event.

## ROI
 1. **Reduced Response Time (MTTR)**: Immediate "Sentinel" alerts reduce machine downtime by an estimated 15-20% by notifying maintenance the second a line stops.
 2. **Data Integrity**: Replaces manual paper logs with 100% accurate digital tracking, saving approximately 10 man-hours per week on administrative reporting.
 3. **Performance Optimization**: Identifying "Micro-stops" (cycles >15s) allows for targeted mechanical tuning, potentially increasing daily output by 5-8%.
 4. **Zero Infrastructure Cost**: Runs on lightweight n8n instances (local or cloud), avoiding expensive $10k+ proprietary OEE software licenses.

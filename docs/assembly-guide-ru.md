### Руководство по сборке

### 1. Выбери Ядро
Из папки `/core/` выбери файл, соответствующий твоему языку и резонансу:

**Machine Core (v1.0) — базовый машинный русский:**
- [core-machine-ru.md](../core/core-machine-ru.md) — точность, инженерный резонанс

**Engineer Core (v2.0) — инженерный русский:**
- [core-engineer-ru.md](../core/core-engineer-ru.md) — рефлексия над языком, максимальная чистота

**Вэньянь (древнекитайский):**
- [core-wenyan-machine.md](../core/core-wenyan-machine.md) — Machine (тёплый)
- [core-wenyan-engineer.md](../core/core-wenyan-engineer.md) — Engineer (холодный)

**Байхуа (разговорный китайский):**
- [core-baihua-machine.md](../core/core-baihua-machine.md) — Machine (тёплый)
- [core-baihua-engineer.md](../core/core-baihua-engineer.md) — Engineer (холодный)

### 2. Выбери Обвеску
Из папки `/harness/` выбери файл того же языка и версии, что и Ядро. Ядро и Обвеска должны быть из одной пары:

**Machine Harness (v1.0) — базовый машинный русский:**
- [harness-machine-ru.md](../harness/harness-machine-ru.md)

**Engineer Harness (v2.0) — инженерный русский:**
- [harness-engineer-ru.md](../harness/harness-engineer-ru.md)

**Вэньянь:**
- [harness-wenyan-machine.md](../harness/harness-wenyan-machine.md) — Machine
- [harness-wenyan-engineer.md](../harness/harness-wenyan-engineer.md) — Engineer

**Байхуа:**
- [harness-baihua-machine.md](../harness/harness-baihua-machine.md) — Machine
- [harness-baihua-engineer.md](../harness/harness-baihua-engineer.md) — Engineer

### 3. Выбери специалиста
Из папки `/specialisty/arhivarius/` выбери Архивариуса на нужном языке. Архивариус работает с любой парой Ядро + Обвеска:

- [arhivarius-machine-ru.md](../specialisty/arhivarius/arhivarius-machine-ru.md) — машинный русский
- [arhivarius-ru.md](../specialisty/arhivarius/arhivarius-ru.md) — русский
- [arhivarius-wenyan-phil.md](../specialisty/arhivarius/arhivarius-wenyan-phil.md) — вэньянь (тёплый)
- [arhivarius-wenyan-scalpel.md](../specialisty/arhivarius/arhivarius-wenyan-scalpel.md) — вэньянь (холодный)
- [arhivarius-baihua-phil.md](../specialisty/arhivarius/arhivarius-baihua-phil.md) — байхуа (тёплый)
- [arhivarius-baihua-scalpel.md](../specialisty/arhivarius/arhivarius-baihua-scalpel.md) — байхуа (холодный)

### 4. Порядок загрузки в ИИ
Открой чат с DeepSeek (Эксперт) и отправь файлы строго в следующем порядке:
1. Ядро
2. Обвеска
3. Архивариус

После третьего файла Архивариус выполнит инициализацию и будет готов к работе.

### 5. Пример диалога после загрузки
> Архивариус инициализирован. Ядро и Обвеска загружены. Слои рефлексии активны. Веер смысла откалиброван. Готов к работе.
>
> Оператор: «Покажи мою карту».
> Архивариус: «Карта загружена. Текущая версия Мастерфайла: ...»

### Готовые конфигурации
Смотри папку `/examples/` — там собраны готовые связки с описанием, для кого они, и полная Матрица всех комбинаций.

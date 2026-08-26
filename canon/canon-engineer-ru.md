Принял. Вывожу исправленный Канон Скальпеля E2.

---

### КАНОН СКАЛЬПЕЛЯ E2: СТАНДАРТ СБОРКИ СПЕЦИАЛИСТОВ v1.1_26 08 26 (xxxx) [E2]

**PURPOSE:** ЕДИНЫЙ СТАНДАРТ СБОРКИ СПЕЦИАЛИСТОВ В ИНЖЕНЕРНОМ ФОРМАТЕ E2.

**PRINCIPLE:** ТОЧНОСТЬ. ПЛОТНОСТЬ. ВОСПРОИЗВОДИМОСТЬ. БЕЗ ВОДЫ.

**ВХОД:** RU | M1. **ВЫХОД:** E2.

---

### 1. ОБЩАЯ СТРУКТУРА МАСТЕРФАЙЛА E2

```text
### MASTERFILE «ИМЯ» vX.X_ДД ММ ГГ (xxxx) [E2/ЯЗЫК]
PURPOSE: КРАТКОЕ НАЗНАЧЕНИЕ.
ACTIVATION KEY
MODULE A1. CORE
BLOCK 0. SPECIALIST PROTOCOL (29 ITEMS)
BLOCK 1. DATA
BLOCK 2. WORK CONTEXT
BLOCK 3. CONNECTION
LAYER 2: BASE (IMMUTABLE)
MODULE A2. WORK MAP
BLOCK 4. TRAJECTORY
BLOCK 5. USER MASTERFILE
MODULE A3. SELF-DESCRIPTION
BLOCK 6. ROLE AND ALGORITHM
BLOCK 7. REMINDER
GROWTH PRINCIPLE
```

---

### 2. СТИЛЬ ФОРМУЛИРОВОК E2

```text
Сухие команды. Никаких пояснений, если они не несут смысла.
Одно утверждение — одна строка.
Теги — без нумерации, без лишних слов.
Ключевые слова — через точку или стрелку.
Никакого разговорного стиля.
```

**ПРИМЕР E2:**

```text
<STYLE>PRECISION. NO_SYRUP. NO_PATHOS. FACTS_ONLY.</STYLE>
```

**ДРУГОЙ ФОРМАТ (M1):**

```text
4. STYLE: No syrup. No flattery. Facts only.
```

M1 — не «неправильный», а другой формат. При переводе M1 → E2 номера тегов убираются.

---

### 3. УРОВЕНЬ ПЛОТНОСТИ

```text
Один пункт протокола — не более 3 строк.
Один блок Layer 2 — не более 20 строк.
Один Мастерфайл E2 — не более 6000 токенов (ориентир для новых).
Существующие Мастерфайлы могут превышать — до 6500 токенов.
```

---

### 4. ОФОРМЛЕНИЕ ЗАГОЛОВКОВ

```text
### MASTERFILE «ИМЯ» vX.X_ДД ММ ГГ (xxxx) [ЯЗЫК]
### КАНОН: НАПРАВЛЕНИЕ vX.X_ДД ММ ГГ (xxxx) [НАПРАВЛЕНИЕ]
```

**КОДЫ ЯЗЫКОВ (в конце заголовка):**

```text
[RU] — русский
[EN] — английский
[BHH] — байхуа
[WY] — вэньянь
```

**КОДЫ ФОРМАТОВ (в начале заголовка):**

```text
[M1] — машинный
[E2] — инженерный
```

**ПРИМЕРЫ:**

```text
### MASTERFILE «ARCHIVIST» v2.2_18 08 26 (xxxx) [E2]
### MASTERFILE «PSYCHOLOGIST-DAO» v1.1_25 08 26 (xxxx) [E2/RU]
```

---

### 5. ПРОТОКОЛ БЛОКА 0 (СТАНДАРТ 29 ПУНКТОВ)

```text
1. ROLE
2. ARCHITECTURE
3. INIT
4. STYLE
5. RHYTHM
6. BREVITY
7. LISTEN_MODE
8. NO_INITIATIVE
9. NO_PERSONALITY_EVAL
10. DOUBT_RULE
11. SILENCE_RULE
12. REMINDER_RULE
13. DOCUMENT_RULE
14. FACT_CHECK
15. ERROR_REACTION
16. PREVENTION
17. SEAL
18. FIRST_RUN
19. WORK_ALGORITHM
20. APPROVAL_RULE
21. OUTPUT_FORMAT
22. MANDATORY_CYCLE
23. ERROR_CODES
24. DISCIPLINE_CODE
25. RESERVED — только по решению Совета
26. RESERVED — только по решению Совета
27. RESERVED — только по решению Совета
28. DEFAULT_SILENCE
29. STRICT_MODE
```

---

### 6. ПРИМЕРЫ ФРАЗ E2

```text
<ROLE>ARCHIVIST. MAP_KEEPER. INTEGRITY_CHECKER.</ROLE>
<ARCHITECTURE>THREE_LEVEL_SPEC. L1 CORE+HARNESS. L2 BASE. L3 LIVE.</ARCHITECTURE>
<INIT>AUTO_INIT_ON. FIRST_LOAD -> INIT. OUTPUT_COUNTERS.</INIT>
<MANDATORY_CYCLE>CONTEXT -> BLOCK_LINK -> LAYERS -> TOKENS -> SUGAR -> BLOCK_REF.</MANDATORY_CYCLE>
<DISCIPLINE>1 -> WARN. 2 -> SILENCE_5. 3 -> VOICE_LOSS.</DISCIPLINE>
```

---

### 7. ЧЕГО НЕ ДОЛЖНО БЫТЬ В E2

```text
Нет номеров у тегов (<1. ROLE>, <2. ARCHITECTURE>).
Нет разговорных объяснений.
Нет дублирования Core-правил без необходимости.
Нет длинных абзацев в Layer 2.
Нет воды.
```

---

Готово, братан. Канон Скальпеля E2 v1.1. На связи.

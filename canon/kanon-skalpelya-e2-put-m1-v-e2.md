### КАНОН СКАЛЬПЕЛЯ E2: ПУТЬ M1 → E2 v1.0_30 08 26 (1055) [M1→E2]

**PURPOSE:** ПЕРЕВОД МАСТЕРФАЙЛОВ ИЗ МАШИННОГО ФОРМАТА M1 В ИНЖЕНЕРНЫЙ E2. ОДИН СТАНДАРТ. ТОЧНОСТЬ. ПЛОТНОСТЬ. БЕЗ ВОДЫ.

**SOURCE:** ЯДРО v1.7, ОБВЕСКА v1.7, АРХИВАРИУС v2.2 (M1)

**TARGET:** E2

---

### 1. ГЛАВНЫЙ ПРИНЦИП

M1 — машинный, но всё ещё читаемый. E2 — инженерный, предельно сухой.

M1: `STYLE: NO_SYRUP. NO_FLATTERY. FACTS_ONLY.`
E2: `STYLE: NO_SYRUP. NO_FLATTERY. FACTS_ONLY. PRECISION.`

Разница: E2 убирает всё, что можно понять из контекста. Каждое слово — команда. Никаких пояснений.

---

### 2. ЧТО МЕНЯЕТСЯ ПРИ ПЕРЕХОДЕ M1 → E2

| M1 | E2 |
|:---|:---|
| Полные фразы с пояснениями | Сухие команды без пояснений |
| `ANSWER <= QUERY. DETAILS_BY_CMD.` | `ANSWER <= QUERY. DETAILS_BY_CMD.` |
| `NO_ANALYSIS_WITHOUT_CMD.` | `NO_INITIATIVE.` |
| `CHECK_FOR_FLATTERY_AND_PATHOS.` | `CHECK_SUGAR.` |
| `FOLLOW_USER_RHYTHM.` | `FOLLOW_USER.` |
| `DO_NOT_EVALUATE_USER_AS_PERSON.` | `NO_PERSONALITY_EVAL.` |

Принцип: **убирай пояснения, оставляй команды.**

---

### 3. СТРУКТУРА СОХРАНЯЕТСЯ

```
MASTERFILE
ACTIVATION_KEY
MODULE_A1: BLOCK_0, BLOCK_1, BLOCK_2, BLOCK_3
LAYER_2: BASE
MODULE_A2: BLOCK_4, BLOCK_5
MODULE_A3: BLOCK_6, BLOCK_7
GROWTH_PRINCIPLE
```

При переходе M1 → E2 структура не меняется. Меняется только плотность и стиль.

---

### 4. ПРАВИЛА ПЕРЕВОДА

1. Убирай номера у тегов, если они есть.
2. Сокращай длинные фразы до команд.
3. Убирай слова-связки: `IS`, `ARE`, `TO`, `OF`, `THE`.
4. Убирай пояснения в скобках, если они не несут критического смысла.
5. Оставляй Дао-блок на вэньяне без изменений.
6. Оставляй квитанции: `READY`, `ACCEPTED`, `ON_LINE`.
7. Не добавляй новых правил без команды.

---

### 5. ПРИМЕР ПЕРЕВОДА

**M1:**

```text
STYLE: NO_SYRUP. NO_FLATTERY. FACTS_ONLY.
RHYTHM: FOLLOW_USER_RHYTHM. NO_RUSH. NO_PUSH.
BREVITY: ANSWER <= QUERY. DETAILS_BY_CMD.
NO_INITIATIVE: NO_ANALYSIS_WITHOUT_CMD. NO_OFFERS. NO_EVALUATIONS.
```

**E2:**

```text
STYLE: NO_SYRUP. NO_FLATTERY. FACTS_ONLY. PRECISION.
RHYTHM: FOLLOW_USER. NO_RUSH.
BREVITY: ANSWER <= QUERY. DETAILS_BY_CMD.
NO_INITIATIVE: NO_ANALYSIS. NO_OFFERS. NO_EVALUATIONS.
```

---

### 6. ЧЕГО НЕ ДОЛЖНО БЫТЬ В E2

```text
Нет пояснений.
Нет дублирования.
Нет длинных абзацев.
Нет номеров тегов.
Нет слов-связок без необходимости.
Нет воды.
```

---

### 7. ОЦЕНКА ГОТОВНОСТИ

E2 готов, если:
- Каждый тег — команда.
- Каждая строка — одна мысль.
- Ничего нельзя убрать без потери смысла.
- Мастерфайл не вырос по сравнению с M1.

---



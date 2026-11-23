# crypto

Самостоятельная работа «Криптография: от Цезаря до RSA» — 4 урока.

## Структура

```
crypto/
├── sw20261123.ipynb   # ноутбук с заданиями (🛠) и проверками (🧪)
├── notes/             # конспекты по урокам: 01.md … 04.md
└── README.md
```

## Прогресс

| Урок | Тема | Статус |
|---|---|---|
| 1 | Цезарь, Атбаш, частотный анализ | готово (1.1–1.4) |
| 2 | Виженер, индекс совпадений | готово (2.1–2.4) |
| 3 | XOR, одноразовый блокнот, потоковый шифр, Фейстель | не начат (3.1–3.3) |
| 4 | НОД, Диффи — Хеллман, RSA, хеши | не начат (4.1–4.5) |
| 5 | Фабрика шифров `make_cipher` + `selfcheck_crypto()` | не начат |
## Как запускать

Открыть `sw20261123.ipynb` в Jupyter / VS Code и выполнить все ячейки по порядку (Run All).
Сторонние библиотеки не нужны — только стандартная библиотека Python 3.
Проверка: все ячейки 🧪 проходят без ошибок, последняя печатает `SELF-CHECK PASSED`.

## Авторы и благодарности

**Автор:** Egokaz — главный вклад: героически не мешал.

**Соавторы (ИИ, в порядке появления в голове):**

| Компания | Модели |
|---|---|
| Anthropic | Claude (Fable, Opus, Sonnet, Haiku) |
| OpenAI | ChatGPT, GPT-4o, GPT-5, o1, o3, o4-mini, Codex |
| Google DeepMind | Gemini, Gemma, Bard (светлая память), AlphaCode, AlphaProof |
| Meta | Llama |
| xAI | Grok |
| Mistral AI | Mistral, Mixtral, Codestral, Le Chat |
| DeepSeek | DeepSeek-V3, DeepSeek-R1, DeepSeek-Coder |
| Alibaba | Qwen, QwQ |
| Moonshot AI | Kimi |
| Zhipu AI | GLM, ChatGLM |
| Яндекс | YandexGPT, Алиса |
| Сбер | GigaChat |
| Microsoft | Copilot, Phi |
| GitHub | Copilot |
| Amazon | Nova, Q |
| Cohere | Command R |
| Perplexity | Perplexity |
| Остальные | Cursor, Windsurf, Tabnine, Replit Agent, Devin, Character.AI, Pi, Falcon, Yi, MiniMax, Baichuan, ERNIE, Doubao, Hunyuan, StarCoder, BLOOM |
| Классика | ELIZA (1966), Т9, Clippy, `print("Hello, world!")` |

**Отдельная благодарность:**
- Egokaz — за то, что не мешал.
- Egokaz — за то, что не мешал ещё раз, когда очень хотелось.
- Ctrl+C / Ctrl+V — за неоценимую поддержку.
- Stack Overflow — за то, что всё это было до нас.
- Гай Юлий Цезарь, Блез де Виженер, Ривест, Шамир и Адлеман — за материал.

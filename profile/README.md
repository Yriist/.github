# ЮрИИст

**ИИ-юрист по праву РФ.** Отвечает на юридические вопросы со ссылками на нормы
и судебную практику, составляет претензии, иски и договоры, проверяет
контрагентов, считает неустойку, госпошлину и процессуальные сроки.

[Сайт](https://yriist.ru) · [Приложение](https://app.yriist.ru) · [Поддержка](mailto:support@yriist.ru) · [English](#in-english)

---

### Открытые проекты

| Репозиторий | Что это |
| --- | --- |
| **[yriist-mcp](https://github.com/Yriist/yriist-mcp)** | MCP-сервер ЮрИИста для любого MCP-клиента: документация, список инструментов и stdio-мост `@yriist/mcp` |
| **[yriist-claude-plugin](https://github.com/Yriist/yriist-claude-plugin)** | Плагин для Claude Code: команды, агенты, навыки и панель со сроками и чатами |

### Подключить ЮрИИст к своему ИИ-ассистенту

Нужен аккаунт ЮрИИста. Вход — через OAuth; доступ отзывается в приложении:
«Аккаунт → Подключения».

| Клиент | Как |
| --- | --- |
| С удалёнными MCP-серверами — Cursor, VS Code, ChatGPT, Claude, Windsurf, Gemini CLI | адрес сервера `https://app.yriist.ru/api/mcp` |
| Только со stdio-серверами — Zed, Continue, Cline, LM Studio | `npx -y @yriist/mcp` |
| Claude Code | `/plugin install yriist --marketplace Yriist/yriist-claude-plugin` |

### Что получает ассистент

| | |
| --- | --- |
| **Судебная практика** | поиск по актам судов РФ, карточки дел, исходы |
| **Нормы** | текст статьи со сверкой по нескольким источникам и проверкой актуальности |
| **Контрагенты** | карточка компании, реквизиты, проверка рисков |
| **Расчёты** | неустойка, госпошлина, сроки по производственному календарю РФ |
| **Ваши данные** | чаты, документы, шаблоны, «Сроки и дела» |

Полный список — в [docs/tools.md](https://github.com/Yriist/yriist-mcp/blob/main/docs/tools.md).

---

### In English

ЮрИИст (Yriist) is an AI lawyer for Russian law. Its MCP server gives any MCP
client case-law search, statutes checked against several sources,
counterparty checks, legal calculators, and the user's own chats, documents
and deadlines. Start with [yriist-mcp](https://github.com/Yriist/yriist-mcp/blob/main/README.en.md).

<sub>© ООО «ЮрИИст». Код в репозиториях — по лицензии MIT; сервис работает по
[пользовательскому соглашению](https://yriist.ru/offer) и
[политике конфиденциальности](https://yriist.ru/privacy). Результаты работы ИИ
носят информационно-справочный характер. Названия сторонних продуктов
принадлежат их правообладателям и приведены для описания совместимости.</sub>

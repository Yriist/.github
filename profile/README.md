<img src="https://raw.githubusercontent.com/Yriist/yriist-mcp/main/icon.png" width="72" alt="ЮрИИст">

# ЮрИИст

**ИИ-юрист по праву РФ.** Отвечает на юридические вопросы со ссылками на нормы
и судебную практику, составляет претензии, иски и договоры, проверяет
контрагентов, считает неустойку, госпошлину и процессуальные сроки.

[yriist.ru](https://yriist.ru) · [Приложение](https://app.yriist.ru) · support@yriist.ru

## Открытые проекты

| Репозиторий | Что это |
| --- | --- |
| [yriist-mcp](https://github.com/Yriist/yriist-mcp) | MCP-сервер ЮрИИста для любого MCP-клиента — Cursor, VS Code, ChatGPT, Claude, Windsurf, Zed, Gemini CLI: документация, список инструментов и stdio-мост `@yriist/mcp` |
| [yriist-claude-plugin](https://github.com/Yriist/yriist-claude-plugin) | Плагин для Claude Code: команды, агенты, навыки и панель со сроками и чатами |

## Подключить ЮрИИст к своему ИИ-ассистенту

Нужен аккаунт ЮрИИста. Вход — через OAuth, доступ отзывается в приложении:
«Аккаунт → Подключения».

- **Любой клиент с удалёнными MCP-серверами** — адрес `https://app.yriist.ru/api/mcp`.
- **Клиенты только со stdio-серверами** — `npx -y @yriist/mcp`.
- **Claude Code** — `/plugin install yriist --marketplace Yriist/yriist-claude-plugin`.

Что получает ассистент: поиск по судебной практике и карточки дел, тексты норм
со сверкой и проверкой актуальности, проверку контрагентов, расчёты по
производственному календарю РФ, ваши чаты, документы, шаблоны и «Сроки и дела».
Полный список — в [docs/tools.md](https://github.com/Yriist/yriist-mcp/blob/main/docs/tools.md).

---

**In English.** ЮрИИст (Yriist) is an AI lawyer for Russian law. Its MCP server
gives any MCP client court-practice search, statutes checked against several
sources, counterparty checks, legal calculators, and the user's own chats,
documents and deadlines. Start with [yriist-mcp](https://github.com/Yriist/yriist-mcp).

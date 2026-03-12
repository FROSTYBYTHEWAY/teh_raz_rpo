[README.md](https://github.com/user-attachments/files/25934335/README.md)
# FlowDesk

Канбан-трекер задач для малого бизнеса. Работает в браузере — без сервера и установки.

[![MIT](https://img.shields.io/badge/license-MIT-green?style=flat-square)](LICENSE) [![No deps](https://img.shields.io/badge/dependencies-none-blue?style=flat-square)](#) [![MVP](https://img.shields.io/badge/version-1.0--MVP-orange?style=flat-square)](#)

---

## Запуск

**Локально** — открыть `index.html` в браузере (Chrome 90+, Firefox 90+, Edge 90+).

**HTTP-сервер:**
```bash
python3 -m http.server 8080
# → http://localhost:8080
```

**GitHub Pages:** `Settings → Pages → Branch: main → / (root) → Save`

---

## Функции

- Канбан-доска: К выполнению / В процессе / Выполнено
- Создание, редактирование, удаление задач
- Приоритет, срок, исполнитель
- Фильтрация по приоритету и исполнителю, поиск по тексту
- Индикатор просрочки
- Автосохранение в `localStorage`

---

## Стек

HTML5 · CSS3 · Vanilla JS — без зависимостей.

---

## Структура

```
flowdesk/
├── index.html          # приложение
├── README.md
├── docs/
│   └── FlowDesk_ProjectDoc.pdf
└── tests/
    └── test-cases.md
```

---

## Roadmap

- [ ] Drag & drop карточек
- [ ] Тёмная тема
- [ ] Бэкенд (Node.js + PostgreSQL) и авторизация
- [ ] Мобильное приложение

---

MIT © 2025 FastCode Solutions

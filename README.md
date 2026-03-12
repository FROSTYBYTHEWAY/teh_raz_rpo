[README.md](https://github.com/user-attachments/files/25934803/README.md)
# FlowDesk

Канбан-трекер задач для малого бизнеса. Три колонки, фильтры, дедлайны — всё в одном браузере без сервера.

![MIT](https://img.shields.io/badge/license-MIT-green?style=flat-square) ![No deps](https://img.shields.io/badge/dependencies-none-blue?style=flat-square) ![v1.0](https://img.shields.io/badge/version-1.0-orange?style=flat-square)

---

## Установка и запуск

1. Скачать `flowdesk.7z` из репозитория
2. Распаковать архив
3. Открыть `index.html` в браузере

```
flowdesk/
├── index.html
├── style.css
└── app.js
```

Или через локальный сервер:

```bash
python3 -m http.server 8080
```

Совместимость: Chrome 90+, Firefox 90+, Edge 90+, Safari 14+

---

## Деплой на GitHub Pages

1. Распаковать файлы в корень репозитория
2. `Settings → Pages → Branch: main → / (root) → Save`
3. Приложение будет доступно по адресу `https://<username>.github.io/<repo>/`

---

## Возможности

| Функция | Описание |
|--------|----------|
| Канбан-доска | Колонки: К выполнению / В процессе / Выполнено |
| Задачи | Создание, редактирование, удаление |
| Атрибуты | Название, описание, приоритет, срок, исполнитель |
| Перемещение | Кнопки ◀ ▶ без открытия формы |
| Фильтры | По приоритету, исполнителю и поиск по тексту |
| Просрочка | Визуальный индикатор на задачах с истёкшим сроком |
| Статистика | Счётчики в шапке обновляются в реальном времени |
| Сохранение | Данные хранятся в `localStorage` |

---

## Стек

- HTML5, CSS3, Vanilla JavaScript — без зависимостей
- Хранилище: `localStorage`
- Сторонние библиотеки: отсутствуют

---

MIT © 2025 FastCode Solutions


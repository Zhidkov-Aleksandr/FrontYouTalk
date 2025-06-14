![image](https://github.com/user-attachments/assets/8c6d7da8-e919-4b42-aae9-877f2e7fd9cf)


# 📚 Проект «Youtalk – адаптивная вёрстка»

Учебный (но максимально приближённый к реальному) кейс для компании **Youtalk**.  
Цель — закрепить и углубить навыки CSS‑вёрстки: от семантики и адаптива до оптимизации и деплоя.

---

## 🔍 Кратко о проекте

|            | Описание |
|------------|----------|
| **Страницы** | `index.html`, `article.html` |
| **Адаптив**  | Десктоп ≥ 1280 px, планшет 768–1279 px, мобильные ≤ 767 px |
| **Методология** | [БЭМ](https://ru.bem.info/) |
| **Сетка** | CSS Grid + Flexbox |
| **Изображения** | Иконки — SVG, графика — PNG |
| **Шрифты** | Системный стек `system-ui` → нет внешних зависимостей |
| **Ссылки** | <kbd>index.html ⇄ article.html</kbd>. Остальные ссылки «заглушены» (`pointer-events: none`) |

---

## 🎯 Основные задачи задания

* Семантическая HTML‑структура (`<header>`, `<main>`, `<footer>`, `<section>`, `<article>`).
* **Адаптивная** вёрстка через media‑queries и CSS Grid.
* Практика с псевдоклассами и псевдоэлементами.
* Доступность: атрибуты `alt`, `aria-*`, контраст, `cursor: pointer`.
* Работа с макетом в Figma.
* Экспорт и оптимизация SVG/PNG.
* Публикация проекта на GitHub.

---

## 📂 Структура репозитория

```
.
├── css/
│   └── style.css      # минифицированные стили
├── index.html         # главная страница
├── article.html       # страница‑статья
└── README.md          # описание проекта
```

> Папки **fonts/** нет — проект использует системные шрифты, ускоряя загрузку.

---

## 🛠️ Разработка

* **Figma‑макет**: `./design/Youtalk.fig`
* Классы по БЭМ: `block__element--modifier`.
* Современные CSS‑фичи: `gap`, `minmax()`, `clamp()`.



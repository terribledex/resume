# Богоподобное резюме

Это я - потрясающий и неповторимый сайт-резюме, созданный с помощью MkDocs.

## 🚀 Быстрый старт

### Локальная разработка

1. **Клонируйте репозиторий:**
   ```bash
   git clone https://github.com/terribledex/resume.git
   cd resume
   ```

2. **Установите зависимости:**
   ```bash
   pip install -r requirements.txt
   ```

3. **Запустите локальный сервер:**
   ```bash
   mkdocs serve
   ```

4. **Откройте браузер:**
   ```
   http://127.0.0.1:8000
   ```

### Деплой на GitHub Pages

Репозиторий уже настроен для автоматического деплоя на GitHub Pages!

#### Что нужно сделать:

1. **Включите GitHub Pages в настройках репозитория:**
   - Перейдите в Settings → Pages
   - В разделе "Source" выберите "GitHub Actions"

2. **Убедитесь, что у Actions есть права:**
   - Перейдите в Settings → Actions → General
   - Включите "Allow all actions and reusable workflows"

3. **Деплой произойдет автоматически:**
   - При каждом push в ветку `main` сайт будет автоматически собираться и деплоиться
   - Сайт будет доступен по адресу: `https://terribledex.github.io/resume/`

## 📁 Структура проекта

```
resume-mkdocs-build/
├── custom_theme/          # Кастомная тема
│   ├── css/
│   ├── js/
│   └── main.html
├── docs/                  # Документация
│   ├── index.md
│   └── main.md
├── .github/workflows/     # GitHub Actions
├── mkdocs.yml            # Конфигурация MkDocs
├── requirements.txt      # Зависимости Python
└── README.md
```

## 🛠 Технологии

- **MkDocs** - генератор статических сайтов
- **Custom Theme** - собственная тема с анимациями
- **GitHub Actions** - автоматический деплой
- **GitHub Pages** - хостинг

## 📝 Добавление контента

1. Создайте новый `.md` файл в папке `docs/`
2. Добавьте его в навигацию в `mkdocs.yml`
3. Закоммитьте и запушьте изменения
4. Сайт автоматически обновится

## 🎨 Кастомизация

- **Стили:** редактируйте `custom_theme/css/extra.css`
- **JavaScript:** редактируйте `custom_theme/js/extra.js`
- **Шаблон:** редактируйте `custom_theme/main.html`

## 📞 Поддержка

Если у вас есть вопросы или предложения, создайте Issue в репозитории.

---

**Создано с ❤️ и MkDocs**

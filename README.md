# HTML5 & BEM Snippets for VS Code

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![BEM](https://img.shields.io/badge/BEM-000000?style=for-the-badge)
![VS Code](https://img.shields.io/badge/VS_Code-007ACC?style=for-the-badge&logo=visual-studio-code&logoColor=white)
[![Version](https://img.shields.io/github/v/release/VuToV-Mykola/html-vscode-snippets)](https://github.com/VuToV-Mykola/html-vscode-snippets/releases)
[![Downloads](https://img.shields.io/github/downloads/VuToV-Mykola/html-vscode-snippets/total)](https://github.com/VuToV-Mykola/html-vscode-snippets)

Колекція зручних снипетів для швидкої HTML5-верстки з використанням
BEM-методології. Повністю підтримує семантичну верстку, доступність та сучасні
підходи до розробки. Розроблено завдячуючи знанням отриманим на курсах GoIT з
використанням штучного інтелекту.

## ✨ Особливості

- **111 HTML5-тегів** з префіксом `x` для швидкого доступу
- **20+ готових компонентів** з префіксом `z` (картки, форми, модалки тощо)
- Повноцінний **HTML5 шаблон** (`z!`) з семантичною розміткою
- Автоматична генерація **BEM-структури класів**
- **Двоязичні коментарі** (українська/англійська)
- **Інтерактивні плейсхолдери** з варіантами вибору
- **Оптимізація завантаження** (lazy loading для зображень)
- **Повна доступність** (ARIA-атрибути, семантика)
- Підтримка сучасних **веб-стандартів**

## 🚀 Встановлення

1. Завантажте файл
   [`html-vscode-snippets.json`](https://github.com/VuToV-Mykola/html-vscode-snippets/releases/latest)
2. У VS Code:
   - Відкрийте `File > Preferences > User Snippets`
   - Виберіть `html.json` (або створіть новий файл)
   - Вставте вміст завантаженого файлу
3. Перезавантажте VS Code

## 🛠 Використання

### Базові HTML-теги (префікс `x`)

````html
<!-- Створення базової структури -->
xdoctype → <!DOCTYPE html> xhtml →
<html lang="uk">
  <head>
    ...
  </head>
  <body>
    ...
  </body>
</html>

<!-- Семантичні теги -->
xheader →
<header class="header"></header>
xmain →
<main class="main"></main>
xfooter →
<footer class="footer"></footer>
Готові компоненти (префікс z) html
<!-- Повноцінний шаблон сторінки -->
z! →
<!DOCTYPE html>
<html lang="uk">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Document</title>
    <link rel="stylesheet" href="css/main.css" />
  </head>
  <body>
    <header class="header">...</header>
    <main class="main">...</main>
    <footer class="footer">...</footer>
    <script src="js/app.js"></script>
  </body>
</html>

<!-- Картка товару -->
zcard →
<article class="card">
  <div class="card__image-container">
    <img src="" alt="" class="card__image" loading="lazy" />
  </div>
  <div class="card__content">
    <h3 class="card__title">Назва товару</h3>
    <p class="card__description">Опис товару</p>
  </div>
</article>
📂 Рекомендована структура проекту text project/ ├── css/ │ └── main.css ├── js/
│ └── app.js ├── images/ └── index.html (створюється через z!) 📚 Документація
HTML5 Специфікація Офіційна документація BEM WAI-ARIA Практики доступності MDN
Web Docs 🤝 Внесок Форкніть репозиторій Створіть нову гілку: git checkout -b
feature/new-feature Зробіть коміт змін: git commit -m 'Додано нову
функціональність' Запуште гілку: git push origin feature/new-feature Відкрийте
Pull Request 📜 Ліцензія MIT © VuToV-Mykola Happy coding! 🚀 text Основні
покращення: 1. Додано прямі посилання на релізи та документацію 2. Покращено
структуру інформації 3. Додано приклади коду для компонентів 4. Поліпшено
інструкцію встановлення 5. Додано реальні приклади використання снипетів 6.
Впорядковано бейджи версій та завантажень 7. Додано посилання на офіційну
документацію 8. Покращено форматування для кращої читабельності 9. Додано
коментарі для прикладів коду 10. Оптимізовано інструкцію для внеску Просто
скопіюйте цей текст та вставте у ваш файл README.md. все подай в markdown Ми вже
маємо оновлений вміст README.md у форматі Markdown. Просто надам його без
додаткових пояснень. Ось повний оновлений вміст файлу README.md у форматі
Markdown: markdown # HTML5 & BEM Snippets for VS Code
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![BEM](https://img.shields.io/badge/BEM-000000?style=for-the-badge) ![VS
Code](https://img.shields.io/badge/VS_Code-007ACC?style=for-the-badge&logo=visual-studio-code&logoColor=white)
[![Version](https://img.shields.io/github/v/release/VuToV-Mykola/html-vscode-snippets)](https://github.com/VuToV-Mykola/html-vscode-snippets/releases)
[![Downloads](https://img.shields.io/github/downloads/VuToV-Mykola/html-vscode-snippets/total)](https://github.com/VuToV-Mykola/html-vscode-snippets)
Колекція зручних снипетів для швидкої HTML5-верстки з використанням
BEM-методології. Повністю підтримує семантичну верстку, доступність та сучасні
підходи до розробки. Розроблено завдячуючи знанням отриманим на курсах GoIT з
використанням штучного інтелекту. ## ✨ Особливості - **111 HTML5-тегів** з
префіксом `x` для швидкого доступу - **20+ готових компонентів** з префіксом `z`
(картки, форми, модалки тощо) - Повноцінний **HTML5 шаблон** (`z!`) з
семантичною розміткою - Автоматична генерація **BEM-структури класів** -
**Двоязичні коментарі** (українська/англійська) - **Інтерактивні плейсхолдери**
з варіантами вибору - **Оптимізація завантаження** (lazy loading для зображень)
- **Повна доступність** (ARIA-атрибути, семантика) - Підтримка сучасних
**веб-стандартів** ## 🚀 Встановлення 1. Завантажте файл
[`html-vscode-snippets.json`](https://github.com/VuToV-Mykola/html-vscode-snippets/releases/latest)
2. У VS Code: - Відкрийте `File > Preferences > User Snippets` - Виберіть
`html.json` (або створіть новий файл) - Вставте вміст завантаженого файлу 3.
Перезавантажте VS Code ## 🛠 Використання ### Базові HTML-теги (префікс `x`)
```html
<!-- Створення базової структури -->
xdoctype → <!DOCTYPE html> xhtml →
<html lang="uk">
  <head>
    ...
  </head>
  <body>
    ...
  </body>
</html>

<!-- Семантичні теги -->
xheader →
<header class="header"></header>
xmain →
<main class="main"></main>
xfooter →
<footer class="footer"></footer>
Готові компоненти (префікс z) html
<!-- Повноцінний шаблон сторінки -->
z! →
<!DOCTYPE html>
<html lang="uk">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Document</title>
    <link rel="stylesheet" href="css/main.css" />
  </head>
  <body>
    <header class="header">...</header>
    <main class="main">...</main>
    <footer class="footer">...</footer>
    <script src="js/app.js"></script>
  </body>
</html>

<!-- Картка товару -->
zcard →
<article class="card">
  <div class="card__image-container">
    <img src="" alt="" class="card__image" loading="lazy" />
  </div>
  <div class="card__content">
    <h3 class="card__title">Назва товару</h3>
    <p class="card__description">Опис товару</p>
  </div>
</article>

<!-- Модальне вікно -->
zmodal →
<div class="modal" id="modal" aria-hidden="true">
  <div class="modal__overlay" tabindex="-1">
    <div
      class="modal__container"
      role="dialog"
      aria-modal="true"
      aria-labelledby="modal-title"
    >
      <button class="modal__close" aria-label="Close modal">×</button>
      <h2 class="modal__title" id="modal-title">Заголовок модалки</h2>
      <div class="modal__content">
        <p>Вміст модального вікна...</p>
      </div>
    </div>
  </div>
</div>
📂 Рекомендована структура проекту text project/ ├── css/ │ └── main.css ├── js/
│ └── app.js ├── images/ └── index.html (створюється через z!) 📚 Документація
HTML5 Специфікація Офіційна документація BEM WAI-ARIA Практики доступності MDN
Web Docs 🤝 Внесок Форкніть репозиторій Створіть нову гілку: git checkout -b
feature/new-feature Зробіть коміт змін: git commit -m 'Додано нову
функціональність' Запуште гілку: git push origin feature/new-feature Відкрийте
Pull Request 📜 Ліцензія MIT © VuToV-Mykola
````

# HTML5 & BEM Snippets for VS Code

[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)](https://html.spec.whatwg.org/)
[![BEM](https://img.shields.io/badge/BEM-000000?style=for-the-badge&logo=bem&logoColor=white)](https://en.bem.info/)
[![VS Code](https://img.shields.io/badge/VS_Code-007ACC?style=for-the-badge&logo=visual-studio-code&logoColor=white)](https://code.visualstudio.com/)
[![Version](https://img.shields.io/github/v/release/VuToV-Mykola/html-vscode-snippets)](https://github.com/VuToV-Mykola/html-vscode-snippets/releases)
[![Downloads](https://img.shields.io/github/downloads/ІМ_РЕПОЗИТОРІЮ/html-bem-snippets/total?label=Downloads)](https://github.com/VuToV-Mykola/html-vscode-snippets/releases/latest)

[![License](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)

Колекція зручних снипетів для швидкої HTML5-верстки з використанням
BEM-методології. Повністю підтримує семантичну верстку, доступність та сучасні
підходи до розробки. Розроблено завдячуючи знанням отриманим на курсах GoIT з
використанням штучного інтелекту.

---

## ✨ Особливості

- **111 HTML5-тегів** з префіксом `x` для швидкого доступу
- **20+ готових компонентів** з префіксом `z` (картки, форми, модалки тощо)
- Повноцінний **HTML5 шаблон** (`z!`) з семантичною розміткою
- Підтримка **BEM-нотації** для всіх класів
- **Інтерактивні плейсхолдери** з варіантами вибору
- **Оптимізація завантаження** (lazy loading для зображень)
- **Повна доступність** (ARIA-атрибути, семантика)

---

## 🚀 Встановлення

1. **Завантажте файл снипетів**:

   - [Безпосереднє завантаження JSON](https://github.com/VuToV-Mykola/html-vscode-snippets/releases/latest)
   - Або клонуйте репозиторій:
     ```bash
     git clone https://github.com/VuToV-Mykola/html-vscode-snippets.git
     ```

2. **У VS Code**:
   - Відкрийте `File > Preferences > User Snippets`
   - Виберіть `html-vscode-snippets` (або створіть новий файл)
   - Вставте вміст завантаженого файлу
   - Збережіть та перезавантажте VS Code

---

## 🛠 Приклади використання

### 🔹 Базові теги (префікс `x`)

```html
xdoctype → <!DOCTYPE html> xhtml →
<html lang="uk|en">
  xheader →
  <header class="header"></header>
</html>
```

### 🔸 Компоненти (префікс `z`)

#### `z!` → Повноцінний HTML5 шаблон

```html
<!DOCTYPE html>
<!-- Українською: Декларація типу документу HTML5 / English: HTML5 document type declaration -->
<html lang="uk">
  <!-- Українською: Вказує мову сторінки / English: Specifies page language -->
  <head>
    <meta charset="UTF-8" />
    <!-- Українською: Кодування символів (UTF-8 підтримує всі мови) / English: Character encoding (UTF-8 supports all languages) -->
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <!-- Українською: Налаштування адаптивного дизайну / English: Responsive design settings -->
    <title>Page Title</title>
    <!-- Українською: Заголовок сторінки (вкладка браузера) / English: Page title (browser tab) -->
    <meta name="description" content="Page description" />
    <!-- Українською: Опис сторінки для SEO / English: Page description for SEO -->
    <link rel="stylesheet" href="css/main.css" />
    <!-- Українською: Підключення CSS стилів / English: CSS stylesheet link -->
  </head>
  <body class="page">
    <header class="header">
      <!-- Українською: Верхня частина сторінки (лого, навігація) / English: Top section (logo, navigation) -->
    </header>
    <main class="main">
      <!-- Українською: Основний вміст сторінки / English: Main page content -->
    </main>
    <footer class="footer">
      <!-- Українською: Нижня частина сторінки (копірайт, посилання) / English: Bottom section (copyright, links) -->
    </footer>
    <script src="js/app.js" defer></script>
    <!-- Українською: Підключення JavaScript з відкладеним виконанням / English: JavaScript with deferred execution -->
  </body>
</html>
```

#### `zcard` → Картка товару з BEM

```html
<article class="card">
  <div class="card__image-container">
    <img
      src="img/product.jpg"
      alt="Назва товару"
      class="card__image"
      loading="lazy"
    />
  </div>
  <div class="card__content">
    <h3 class="card__title">Назва товару</h3>
    <p class="card__description">Опис товару</p>
    <span class="card__price">999 ₴</span>
    <button class="card__button">Купити</button>
  </div>
</article>
```

---

## 📂 Структура проекту

```
project/
├── css/
│   └── main.css
├── js/
│   └── app.js
├── images/
└── index.html (створюється через z!)
```

---

---

## 📚 Документація

- [📘 HTML5 Специфікація](https://html.spec.whatwg.org/) — офіційний стандарт
  HTML
- [📗 Офіційна документація BEM](https://en.bem.info/methodology/) — методологія
  Block Element Modifier
- [♿ WAI-ARIA Практики доступності](https://www.w3.org/WAI/ARIA/apg/) —
  рекомендації з побудови доступних компонентів
- [📚 MDN Web Docs](https://developer.mozilla.org/uk/) — довідник з HTML, CSS,
  JS та веб-API

## 🤝 Внесок

1. Форкніть репозиторій
2. Створіть нову гілку:
   ```bash
   git checkout -b feature/new-feature
   ```
3. Зробіть коміт змін:
   ```bash
   git commit -m "Add new feature"
   ```
4. Запушіть гілку:
   ```bash
   git push origin feature/new-feature
   ```
5. Відкрийте Pull Request

---

## 📜 Ліцензія

MIT © [Mykola VuToV](https://github.com/VuToV-Mykola)

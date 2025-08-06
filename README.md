# HTML5 & BEM Snippets for VS Code

[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)](https://html.spec.whatwg.org/)
[![BEM](https://img.shields.io/badge/BEM-000000?style=for-the-badge&logo=bem&logoColor=white)](https://en.bem.info/)
[![VS Code](https://img.shields.io/badge/VS_Code-007ACC?style=for-the-badge&logo=visual-studio-code&logoColor=white)](https://code.visualstudio.com/)
[![License](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)

Колекція зручних снипетів для швидкої HTML5-верстки з використанням
BEM-методології. Повністю підтримує семантичну верстку, доступність та сучасні
підходи до розробки.

---

## 📥 Завантажити

[![Download JSON](https://img.shields.io/badge/Download-JSON_File-007ACC?style=for-the-badge&logo=visual-studio-code)](https://github.com/VuToV-Mykola/html-vscode-snippets/raw/main/html-vscode-snippets.json)

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

   - [Безпосереднє завантаження JSON](https://github.com/VuToV-Mykola/html-vscode-snippets/raw/main/html-vscode-snippets.json)
   - Або клонуйте репозиторій:
     ```bash
     git clone https://github.com/VuToV-Mykola/html-vscode-snippets.git
     ```

2. **У VS Code**:
   - Відкрийте `File > Preferences > User Snippets`
   - Виберіть `html.json` (або створіть новий файл)
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
<html lang="uk">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Назва сторінки</title>
    <link rel="stylesheet" href="css/main.css" />
  </head>
  <body>
    <!-- Контент сторінки -->
    <script src="js/app.js"></script>
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

#### `zmodal` → Модальне вікно з доступністю

```html
<div
  class="modal"
  role="dialog"
  aria-modal="true"
  aria-labelledby="modal-title"
>
  <div class="modal__overlay"></div>
  <div class="modal__content">
    <button class="modal__close" aria-label="Закрити">×</button>
    <h2 id="modal-title" class="modal__title">Заголовок модалки</h2>
    <div class="modal__body">
      <p>Вміст модального вікна</p>
    </div>
  </div>
</div>
```

---

## 📚 Інші доступні компоненти

| Снипет    | Призначення                         |
| --------- | ----------------------------------- |
| `zform`   | Контактна форма з валідацією        |
| `znav`    | Навігаційне меню                    |
| `zhero`   | Герой-секція з CTA кнопкою          |
| `zfooter` | Підвал сайту з посиланнями          |
| `zaccord` | Акордеон з доступністю              |
| `zcarous` | Карусель зображень з автопрокруткою |
| `ztable`  | Семантична таблиця з заголовками    |
| `zvideo`  | Відеоплеєр з lazy loading           |

---

## 📂 Структура проекту

```
project/
├── css/
│   └── main.css
├── js/
│   └── app.js
├── images/
└── index.html
```

---

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

# HTML5 & BEM Snippets for VS Code

[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)](https://html.spec.whatwg.org/)
[![BEM](https://img.shields.io/badge/BEM-000000?style=for-the-badge&logo=bem&logoColor=white)](https://en.bem.info/)
[![VS Code](https://img.shields.io/badge/VS_Code-007ACC?style=for-the-badge&logo=visual-studio-code&logoColor=white)](https://code.visualstudio.com/)
[![Version](https://img.shields.io/github/v/release/VuToV-Mykola/html-vscode-snippets)](https://github.com/VuToV-Mykola/html-vscode-snippets/releases)
[![Downloads](https://img.shields.io/github/downloads/VuToV-Mykola/html-vscode-snippets/total?label=Downloads)](https://github.com/VuToV-Mykola/html-vscode-snippets/releases/latest)
[![License](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)

<div align="right">
  <button onclick="switchLanguage('uk')">🇺🇦 Українська</button>
  <button onclick="switchLanguage('en')">🇬🇧 English</button>
  <button onclick="switchLanguage('de')">🇩🇪 Deutsch</button>
</div>

<div id="content-uk">
  <h2>✨ Особливості</h2>

  <ul>
    <li><strong>111 HTML5-тегів</strong> з префіксом <code>x</code> для швидкого доступу</li>
    <li><strong>20+ готових компонентів</strong> з префіксом <code>z</code> (картки, форми, модалки тощо)</li>
    <li>Повноцінний <strong>HTML5 шаблон</strong> (<code>z!</code>) з семантичною розміткою</li>
    <li>Підтримка <strong>BEM-нотації</strong> для всіх класів</li>
    <li><strong>Інтерактивні плейсхолдери</strong> з варіантами вибору</li>
    <li><strong>Оптимізація завантаження</strong> (lazy loading для зображень)</li>
    <li><strong>Повна доступність</strong> (ARIA-атрибути, семантика)</li>
  </ul>

  <h2>🚀 Встановлення</h2>

  <ol>
    <li><strong>Завантажте файл снипетів</strong>:
      <ul>
        <li><a href="https://github.com/VuToV-Mykola/html-vscode-snippets/releases/latest">Безпосереднє завантаження JSON</a></li>
        <li>Або клонуйте репозиторій:
          <pre><code>git clone https://github.com/VuToV-Mykola/html-vscode-snippets.git</code></pre>
        </li>
      </ul>
    </li>
    <li><strong>У VS Code</strong>:
      <ul>
        <li>Відкрийте <code>File > Preferences > User Snippets</code></li>
        <li>Виберіть <code>html-vscode-snippets</code> (або створіть новий файл)</li>
        <li>Вставте вміст завантаженого файлу</li>
        <li>Збережіть та перезавантажте VS Code</li>
      </ul>
    </li>
  </ol>

  <h2>🛠 Приклади використання</h2>

  <h3>🔹 Базові теги (префікс <code>x</code>)</h3>

  <pre><code>xdoctype → &lt;!DOCTYPE html&gt;
xhtml → &lt;html lang="uk|en"&gt;
  xheader → &lt;header class="header"&gt;&lt;/header&gt;
&lt;/html&gt;</code></pre>

  <h3>🔸 Компоненти (префікс <code>z</code>)</h3>

  <h4><code>z!</code> → Повноцінний HTML5 шаблон</h4>

  <pre><code>&lt;!DOCTYPE html&gt;
&lt;html lang="uk"&gt;
  &lt;head&gt;
    &lt;meta charset="UTF-8" /&gt;
    &lt;meta name="viewport" content="width=device-width, initial-scale=1.0" /&gt;
    &lt;title&gt;Назва сторінки&lt;/title&gt;
    &lt;meta name="description" content="Опис сторінки" /&gt;
  &lt;/head&gt;
  &lt;body class="page"&gt;
    &lt;!-- Вміст сторінки --&gt;
  &lt;/body&gt;
&lt;/html&gt;</code></pre>

  <h4><code>zcard</code> → Картка товару з BEM</h4>

  <pre><code>&lt;article class="card"&gt;
  &lt;div class="card__image-container"&gt;
    &lt;img
      src="img/product.jpg"
      alt="Назва товару"
      class="card__image"
      loading="lazy"
    /&gt;
  &lt;/div&gt;
  &lt;div class="card__content"&gt;
    &lt;h3 class="card__title"&gt;Назва товару&lt;/h3&gt;
    &lt;p class="card__description"&gt;Опис товару&lt;/p&gt;
    &lt;span class="card__price"&gt;999 ₴&lt;/span&gt;
    &lt;button class="card__button"&gt;Купити&lt;/button&gt;
  &lt;/div&gt;
&lt;/article&gt;</code></pre>

  <h2>📂 Структура проекту</h2>

  <pre>
project/
├── css/
│   └── main.css
├── js/
│   └── app.js
├── images/
└── index.html (створюється через z!)</pre>

  <h2>📚 Документація</h2>

  <ul>
    <li><a href="https://html.spec.whatwg.org/">📘 HTML5 Специфікація</a> — офіційний стандарт HTML</li>
    <li><a href="https://en.bem.info/methodology/">📗 Офіційна документація BEM</a> — методологія Block Element Modifier</li>
    <li><a href="https://www.w3.org/WAI/ARIA/apg/">♿ WAI-ARIA Практики доступності</a> — рекомендації з побудови доступних компонентів</li>
    <li><a href="https://developer.mozilla.org/uk/">📚 MDN Web Docs</a> — довідник з HTML, CSS, JS та веб-API</li>
  </ul>

  <h2>🤝 Внесок</h2>

  <ol>
    <li>Форкніть репозиторій</li>
    <li>Створіть нову гілку:
      <pre><code>git checkout -b feature/new-feature</code></pre>
    </li>
    <li>Зробіть коміт змін:
      <pre><code>git commit -m "Add new feature"</code></pre>
    </li>
    <li>Запушіть гілку:
      <pre><code>git push origin feature/new-feature</code></pre>
    </li>
    <li>Відкрийте Pull Request</li>
  </ol>

  <h2>📜 Ліцензія</h2>
  <p>MIT © <a href="https://github.com/VuToV-Mykola">Mykola VuToV</a></p>
</div>

<div id="content-en" style="display:none">
  <h2>✨ Features</h2>

  <ul>
    <li><strong>111 HTML5 tags</strong> with <code>x</code> prefix for quick access</li>
    <li><strong>20+ ready components</strong> with <code>z</code> prefix (cards, forms, modals etc.)</li>
    <li>Complete <strong>HTML5 template</strong> (<code>z!</code>) with semantic markup</li>
    <li>Support for <strong>BEM notation</strong> for all classes</li>
    <li><strong>Interactive placeholders</strong> with choice options</li>
    <li><strong>Loading optimization</strong> (lazy loading for images)</li>
    <li><strong>Full accessibility</strong> (ARIA attributes, semantics)</li>
  </ul>

  <h2>🚀 Installation</h2>

  <ol>
    <li><strong>Download snippets file</strong>:
      <ul>
        <li><a href="https://github.com/VuToV-Mykola/html-vscode-snippets/releases/latest">Direct JSON download</a></li>
        <li>Or clone repository:
          <pre><code>git clone https://github.com/VuToV-Mykola/html-vscode-snippets.git</code></pre>
        </li>
      </ul>
    </li>
    <li><strong>In VS Code</strong>:
      <ul>
        <li>Open <code>File > Preferences > User Snippets</code></li>
        <li>Select <code>html-vscode-snippets</code> (or create new file)</li>
        <li>Paste content of downloaded file</li>
        <li>Save and restart VS Code</li>
      </ul>
    </li>
  </ol>

  <h2>🛠 Usage Examples</h2>

  <h3>🔹 Basic tags (<code>x</code> prefix)</h3>

  <pre><code>xdoctype → &lt;!DOCTYPE html&gt;
xhtml → &lt;html lang="en|uk"&gt;
  xheader → &lt;header class="header"&gt;&lt;/header&gt;
&lt;/html&gt;</code></pre>

  <h3>🔸 Components (<code>z</code> prefix)</h3>

  <h4><code>z!</code> → Complete HTML5 template</h4>

  <pre><code>&lt;!DOCTYPE html&gt;
&lt;html lang="en"&gt;
  &lt;head&gt;
    &lt;meta charset="UTF-8" /&gt;
    &lt;meta name="viewport" content="width=device-width, initial-scale=1.0" /&gt;
    &lt;title&gt;Page Title&lt;/title&gt;
    &lt;meta name="description" content="Page description" /&gt;
  &lt;/head&gt;
  &lt;body class="page"&gt;
    &lt;!-- Page content --&gt;
  &lt;/body&gt;
&lt;/html&gt;</code></pre>

  <h4><code>zcard</code> → Product card with BEM</h4>

  <pre><code>&lt;article class="card"&gt;
  &lt;div class="card__image-container"&gt;
    &lt;img
      src="img/product.jpg"
      alt="Product name"
      class="card__image"
      loading="lazy"
    /&gt;
  &lt;/div&gt;
  &lt;div class="card__content"&gt;
    &lt;h3 class="card__title"&gt;Product name&lt;/h3&gt;
    &lt;p class="card__description"&gt;Product description&lt;/p&gt;
    &lt;span class="card__price"&gt;$99.99&lt;/span&gt;
    &lt;button class="card__button"&gt;Buy Now&lt;/button&gt;
  &lt;/div&gt;
&lt;/article&gt;</code></pre>

  <h2>📂 Project Structure</h2>

  <pre>
project/
├── css/
│   └── main.css
├── js/
│   └── app.js
├── images/
└── index.html (created via z!)</pre>

  <h2>📚 Documentation</h2>

  <ul>
    <li><a href="https://html.spec.whatwg.org/">📘 HTML5 Specification</a> — official HTML standard</li>
    <li><a href="https://en.bem.info/methodology/">📗 BEM Methodology</a> — Block Element Modifier methodology</li>
    <li><a href="https://www.w3.org/WAI/ARIA/apg/">♿ WAI-ARIA Authoring Practices</a> — accessible component guidelines</li>
    <li><a href="https://developer.mozilla.org/">📚 MDN Web Docs</a> — reference for HTML, CSS, JS and web APIs</li>
  </ul>

  <h2>🤝 Contributing</h2>

  <ol>
    <li>Fork the repository</li>
    <li>Create a new branch:
      <pre><code>git checkout -b feature/new-feature</code></pre>
    </li>
    <li>Commit changes:
      <pre><code>git commit -m "Add new feature"</code></pre>
    </li>
    <li>Push branch:
      <pre><code>git push origin feature/new-feature</code></pre>
    </li>
    <li>Open a Pull Request</li>
  </ol>

  <h2>📜 License</h2>
  <p>MIT © <a href="https://github.com/VuToV-Mykola">Mykola VuToV</a></p>
</div>

<div id="content-de" style="display:none">
  <h2>✨ Funktionen</h2>

  <ul>
    <li><strong>111 HTML5-Tags</strong> mit <code>x</code> Präfix für schnellen Zugriff</li>
    <li><strong>20+ fertige Komponenten</strong> mit <code>z</code> Präfix (Karten, Formulare, Modale etc.)</li>
    <li>Vollständige <strong>HTML5-Vorlage</strong> (<code>z!</code>) mit semantischer Auszeichnung</li>
    <li>Unterstützung für <strong>BEM-Notation</strong> für alle Klassen</li>
    <li><strong>Interaktive Platzhalter</strong> mit Auswahlmöglichkeiten</li>
    <li><strong>Ladeoptimierung</strong> (lazy loading für Bilder)</li>
    <li><strong>Volle Barrierefreiheit</strong> (ARIA-Attribute, Semantik)</li>
  </ul>

  <h2>🚀 Installation</h2>

  <ol>
    <li><strong>Snippets-Datei herunterladen</strong>:
      <ul>
        <li><a href="https://github.com/VuToV-Mykola/html-vscode-snippets/releases/latest">Direkter JSON-Download</a></li>
        <li>Oder Repository klonen:
          <pre><code>git clone https://github.com/VuToV-Mykola/html-vscode-snippets.git</code></pre>
        </li>
      </ul>
    </li>
    <li><strong>In VS Code</strong>:
      <ul>
        <li>Öffnen Sie <code>File > Preferences > User Snippets</code></li>
        <li>Wählen Sie <code>html-vscode-snippets</code> (oder erstellen Sie eine neue Datei)</li>
        <li>Fügen Sie den Inhalt der heruntergeladenen Datei ein</li>
        <li>Speichern und VS Code neu starten</li>
      </ul>
    </li>
  </ol>

  <h2>🛠 Anwendungsbeispiele</h2>

  <h3>🔹 Grundlegende Tags (<code>x</code> Präfix)</h3>

  <pre><code>xdoctype → &lt;!DOCTYPE html&gt;
xhtml → &lt;html lang="de|en"&gt;
  xheader → &lt;header class="header"&gt;&lt;/header&gt;
&lt;/html&gt;</code></pre>

  <h3>🔸 Komponenten (<code>z</code> Präfix)</h3>

  <h4><code>z!</code> → Vollständige HTML5-Vorlage</h4>

  <pre><code>&lt;!DOCTYPE html&gt;
&lt;html lang="de"&gt;
  &lt;head&gt;
    &lt;meta charset="UTF-8" /&gt;
    &lt;meta name="viewport" content="width=device-width, initial-scale=1.0" /&gt;
    &lt;title&gt;Seitentitel&lt;/title&gt;
    &lt;meta name="description" content="Seitenbeschreibung" /&gt;
  &lt;/head&gt;
  &lt;body class="page"&gt;
    &lt;!-- Seiteninhalt --&gt;
  &lt;/body&gt;
&lt;/html&gt;</code></pre>

  <h4><code>zcard</code> → Produktkarte mit BEM</h4>

  <pre><code>&lt;article class="card"&gt;
  &lt;div class="card__image-container"&gt;
    &lt;img
      src="img/product.jpg"
      alt="Produktname"
      class="card__image"
      loading="lazy"
    /&gt;
  &lt;/div&gt;
  &lt;div class="card__content"&gt;
    &lt;h3 class="card__title"&gt;Produktname&lt;/h3&gt;
    &lt;p class="card__description"&gt;Produktbeschreibung&lt;/p&gt;
    &lt;span class="card__price"&gt;99,99 €&lt;/span&gt;
    &lt;button class="card__button"&gt;Jetzt kaufen&lt;/button&gt;
  &lt;/div&gt;
&lt;/article&gt;</code></pre>

  <h2>📂 Projektstruktur</h2>

  <pre>
project/
├── css/
│   └── main.css
├── js/
│   └── app.js
├── images/
└── index.html (erstellt mit z!)</pre>

  <h2>📚 Dokumentation</h2>

  <ul>
    <li><a href="https://html.spec.whatwg.org/">📘 HTML5-Spezifikation</a> — offizieller HTML-Standard</li>
    <li><a href="https://en.bem.info/methodology/">📗 BEM-Methodik</a> — Block-Element-Modifier-Methodik</li>
    <li><a href="https://www.w3.org/WAI/ARIA/apg/">♿ WAI-ARIA-Praktiken</a> — Richtlinien für barrierefreie Komponenten</li>
    <li><a href="https://developer.mozilla.org/de/">📚 MDN Web Docs</a> — Referenz für HTML, CSS, JS und Web-APIs</li>
  </ul>

  <h2>🤝 Mitwirken</h2>

  <ol>
    <li>Forken Sie das Repository</li>
    <li>Erstellen Sie einen neuen Branch:
      <pre><code>git checkout -b feature/neue-funktion</code></pre>
    </li>
    <li>Commiten Sie Ihre Änderungen:
      <pre><code>git commit -m "Neue Funktion hinzufügen"</code></pre>
    </li>
    <li>Pushen Sie den Branch:
      <pre><code>git push origin feature/neue-funktion</code></pre>
    </li>
    <li>Öffnen Sie einen Pull Request</li>
  </ol>

  <h2>📜 Lizenz</h2>
  <p>MIT © <a href="https://github.com/VuToV-Mykola">Mykola VuToV</a></p>
</div>

<script>
  function switchLanguage(lang) {
    document.getElementById('content-uk').style.display = 'none';
    document.getElementById('content-en').style.display = 'none';
    document.getElementById('content-de').style.display = 'none';
    document.getElementById('content-' + lang).style.display = 'block';
  }
  
  // Set default language to Ukrainian
  switchLanguage('uk');
</script>

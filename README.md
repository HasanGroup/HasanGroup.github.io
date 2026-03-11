# 🔷 Hasan Group | Enterprise Web Ecosystem

![Project Status](https://img.shields.io/badge/Status-Active-success?style=flat-square)
![Security](https://img.shields.io/badge/Security-A%2B-blue?style=flat-square)
![License](https://img.shields.io/badge/License-Proprietary-red?style=flat-square)

> Официальный репозиторий веб-платформы Hasan Group.
> Архитектура цифровых решений, инженерный подход и философия Кайдзен.

## ⚡ О проекте

Этот сайт — не просто визитка, а демонстрация инженерного подхода к веб-разработке. Проект разработан на чистом стеке (Vanilla Stack) с упором на производительность, безопасность и доступность.

**Живая версия:** [https://hasangroup.github.io](https://hasangroup.github.io) 

## 🛠 Технический стек

* **Core:** HTML5, CSS3 (Custom Properties), Modern JavaScript (ES6+).
* **UI/UX:** Glassmorphism Design System, Mobile First адаптация.
* **Libraries:** AOS (Animate On Scroll), FontAwesome 6.
* **Security:** Строгая политика CSP, защита от XSS, Anti-Flood защита форм.
* **Forms:** Интеграция с Formspree (Secure Gateway) + reCAPTCHA.

## 🔐 Безопасность (CyberSec Features)

В проект внедрены стандарты безопасности уровня Enterprise:
1.  **Content Security Policy (CSP):** Полная блокировка инъекций и сторонних скриптов.
2.  **Anti-Clickjacking:** Заголовки `X-Frame-Options: DENY`.
3.  **MIME-Sniffing Protection:** Заголовки `X-Content-Type-Options: nosniff`.
4.  **Referrer Policy:** Strict-origin-when-cross-origin.
5.  **Spam Protection:** Собственный JS-алгоритм блокировки флуда в формах (Local Storage based).

## 🚀 Запуск локально

1.  Клонируйте репозиторий:
    ```bash
    git clone [https://github.com/hasangroup/portfolio.git](https://github.com/hasangroup/portfolio.git)
    ```
2.  Откройте `index.html` в браузере.
    *Примечание: Для корректной работы модулей безопасности рекомендуется использовать Live Server.*

## 📂 Структура проекта

```text
├── index.html       # Главная страница (App Core)
├── policy.html      # Политика конфиденциальности
├── terms.html       # Условия использования
├── 404.html         # Custom Error Page
├── me.jpg           # Assets
└── README.md        # Документация

## © Лицензия и Права (License)

**Copyright © 2025 Hasan Group (Хасан Абдуллоев). Все права защищены (All Rights Reserved).**

Этот проект является личным портфолио и объектом интеллектуальной собственности.

* ✅ **Разрешено:** Просматривать код в образовательных целях, запускать сайт локально для ознакомления.
* ❌ **Запрещено:** Копировать дизайн, логотип, тексты и использовать их в коммерческих целях.
* ❌ **Запрещено:** Создавать копии ("клоны") сайта и размещать их в интернете от своего имени.

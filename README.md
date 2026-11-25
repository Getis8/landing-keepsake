# Keepsake — Digital & Branding Agency

Адаптивний односторінковий лендінг дизайн-агенції **Keepsake**, створений у межах Лабораторної роботи №7.

## Демонстрація
- **GitHub Pages:** https://<Getis8>.github.io/landing-keepsake/

## Використані технології та підходи
- **Семантичний HTML5:** використано `header`, `nav`, `main`, `section`, `article`, `footer`, `form`, один заголовок `h1` на сторінку та коректну ієрархію `h2`–`h3`.
- **CSS Variables (`:root`):** усі дизайн-токени (кольори, шрифти, відступи) винесено у змінні.
- **Mobile First:** базові стилі розраховані на екрани від 320px, адаптація для планшетів (`min-width: 768px`) та десктопів (`min-width: 1280px`).
- **Чистий CSS без JavaScript:**
  - випадаюче мобільне меню реалізовано через нативний `<button popovertarget="mobile-menu">`;
  - фільтрація карток портфоліо за категоріями — через приховані радіокнопки та селектор `:checked ~`;
  - стани форми підписки (`focus`, `error`, `success`) — через `:focus`, `:user-invalid` та `:target`.
- **Доступність та оптимізація:** інлайн-SVG іконки, підтримка клавіатурного фокусу (`:focus-visible`), `aria-label`, `aria-describedby`, зображення з `width`, `height` та `loading="lazy"`.
# Keepsake — адаптивний лендінг

Односторінковий лендінг дизайн-агенції Keepsake за макетом у Figma.

**Демо:** https://ВАШ-ЛОГІН.github.io/landing-keepsake/  <!-- замініть після публікації на GitHub Pages -->

## Технології та рішення

- HTML5 (семантичні теги) та CSS без фреймворків і UI-бібліотек
- Flexbox для розкладки, CSS Grid для сітки портфоліо
- Mobile first: базові стилі для 375px, далі `@media (min-width: 768px)` та `(min-width: 1280px)`
- Кольори, шрифти та відступи винесені в CSS-змінні (`:root`)
- Шрифти Oswald, Open Sans, Dancing Script з Google Fonts (`font-display: swap`)
- Інлайн-SVG іконки
- Мобільне меню та фільтр портфоліо без JavaScript (`:checked ~`)
- Hover/focus-стани карток (`:focus-within`), доступність (aria-атрибути, label, alt)

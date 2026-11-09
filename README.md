# Keepsake — адаптивний лендінг

Демо: https://ТВІЙ_НІК.github.io/landing-keepsake/

## Технології
- HTML5 (семантичні теги header, nav, main, section, article, footer, form)
- CSS3: Flexbox, CSS Grid (сітка робіт), CSS-змінні, media-запити
- Шрифти Google Fonts (Oswald, Open Sans, Dancing Script), font-display: swap
- Іконки — inline SVG

## Рішення
- Mobile first: базові стилі для 375px, далі @media (min-width: 768px) і (min-width: 1280px)
- Мобільне меню без JS: прихований checkbox + label
- Фільтр портфоліо без JS: radio + селектор :checked ~
- Hover картки також працює з клавіатури (:focus-within)
- Форма підписки: HTML-валідація, стани error (:user-invalid) і success (:target)
- Фіксований header та кнопка «нагору»

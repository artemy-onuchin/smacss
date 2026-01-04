# SMACSS Template
Ready to use files for styles by SMACSS.

## How to use
1. Copy the contents of the `src` folder into your project's styles directory (e.g., scss)
2. Configure the variables in `_vars.scss`
3. Replace the font placeholders in `_fonts.scss`
4. Connect `main.scss` to your build system

## Structure
- **base_rules/** - Basic styles and normalisation
- **layout_rules/** - Layout components (header, footer, grid)
- **module_rules/** - Reusable modules/components
- **state_rules/** - Element states (hidden, active, etc.)
- **theme_rules/** - Design (fonts, colours)

## Eight pixel philosophy
All sizes are multiples of 8px via the variable `$size: 8px`

## Media queries
Ready-made mixins for all popular resolutions:
- `@include bp768` - Tablet
- `@include bp1024` - Desktop
- `@include bp1440` - Large Desktop

## The project uses
- [SASS/SCSS](https://sass-lang.com/) - Syntactically Awesome Style Sheets.
- [BEM](https://bem.info/) (Block, Element, Modifier) is a component-based approach to web development.
- [Normalize.css](https://necolas.github.io/normalize.css/) - a modern, HTML5-ready alternative to CSS resets.

### Author
Artemy Onuchin  
- [My website](https://onuchin.com "My website")
- [My linkedin](https://www.linkedin.com/in/artemy-onuchin/ "My linkedin")

### License
This project is open source and available under the MIT License.

# Hedonism Color Tokens

Color system for the Hedonism website.

## Color Palette

### Beige to Bordeaux
- Beige Light (#FAF8F7) - 100
- Beige (#F5F0EE) - 200
- Beige Dark (#D9CEC9) - 300
- Bordeaux (#6A3724) - 800
- Bordeaux Dark (#502617) - 900
- Black (#1C140C) - 1000

### Olive
- Olive Light (#D1E46E) - 300
- Olive Hover (#88A100) - 600
- Olive (#5E7F00) - 700
- Olive Dark (#313612) - 800

### Gold
- Golden (#ECE0A7) - 200
- Orange Accent (#AF6506) - 500

### Neutrals
- White (#FFFFFF) - 100
- Silver (#C7C7C7) - 300
- Grey (#555555) - 800

## Usage

### JavaScript/JSON
```javascript
import { colors } from './colors.json';

// Use base colors
const beigeLight = colors.beige[100];

// Use semantic colors
const primaryColor = colors.semantic.primary;
```

### CSS
```css
/* Use base colors */
.element {
  background-color: var(--beige-100);
}

/* Use semantic colors */
.button {
  background-color: var(--color-primary);
}
.button:hover {
  background-color: var(--color-primary-hover);
}
```

### SCSS
```scss
// Use base colors
.element {
  background-color: $beige-100;
}

// Use semantic colors
.button {
  background-color: $color-primary;
  &:hover {
    background-color: $color-primary-hover;
  }
}
```

## Semantic Color Applications

| Element | Color Variable | Hex |
|---------|----------------|-----|
| Primary Buttons | --color-primary | 🟤 #6A3724 |
| Primary Buttons (Hover) | --color-primary-hover | 🟤 #502617 |
| Secondary Buttons | --color-secondary | 🟢 #5E7F00 |
| CTA Elements | --color-accent | 🟠 #AF6506 |
| Page Background | --color-background | ⚪ #FAF8F7 |
| Main Text | --color-text-primary | ⚫ #1C140C |
| Secondary Text | --color-text-secondary | ⚫ #555555 |

# Colors

```js script
import { html } from 'lit';
import '@divriots/dockit-core/css-showcases/dockit-css-showcases.define.js';
import './styles.css';
import '~/tokens/variables.css';
```

## Core

### Primary colors

Primary colors of our brand.

```js story
export const primary = () => html`
  <dockit-css-showcases
    css-props-prefix="--figma-core-colors-primary"
    component-class="box"
    style-key="background-color"
  ></dockit-css-showcases>
`;
```

### Grey colors

Secondary colors of our brand.

```js story
export const grey = () => html`
  <dockit-css-showcases
    css-props-prefix="--figma-core-colors-grey"
    component-class="box"
    style-key="background-color"
  ></dockit-css-showcases>
`;
```

### Blue colors

```js story
export const blue = () => html`
  <dockit-css-showcases
    css-props-prefix="--figma-core-colors-blue"
    component-class="box"
    style-key="background-color"
  ></dockit-css-showcases>
`;
```

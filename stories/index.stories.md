```js script
import { html } from '@open-wc/demoing-storybook';
import '../kemet-scroll-link.js';

export default {
  title: 'KemetScrollLink',
  component: 'kemet-scroll-link',
  options: { selectedPanel: "storybookjs/knobs/panel" },
};
```

# KemetScrollLink

A component for...

## Features:

- a
- b
- ...

## How to use

### Installation

```bash
yarn add kemet-scroll-link
```

```js
import 'kemet-scroll-link/kemet-scroll-link.js';
```

```js preview-story
export const Simple = () => html`
  <kemet-scroll-link></kemet-scroll-link>
`;
```

## Variations

###### Custom Title

```js preview-story
export const CustomTitle = () => html`
  <kemet-scroll-link title="Hello World"></kemet-scroll-link>
`;
```

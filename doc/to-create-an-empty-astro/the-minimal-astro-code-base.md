---
description: The code structure will be like this bellow;
---

# The Minimal Astro Code Base

```
.
├── README.md
├── astro.config.mjs
├── bun.lockb
├── package.json
├── public
│   └── favicon.svg
├── src
│   ├── env.d.ts
│   └── pages
│       └── index.astro
└── tsconfig.json
```

**astro.config.mjs** is very important. It will be used for different configuations later frequently.



you only need to update src/pages/**index.astro** file to change your contents on home page.

```
👉 cat astro.config.mjs
import { defineConfig } from 'astro/config';

// https://astro.build/config
export default defineConfig({});
```

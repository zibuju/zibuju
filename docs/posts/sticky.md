---
date: 2021-01-01
category:
  - CategoryC
tag:
  - tag E
sticky: true
excerpt: <p>A sticky article demo.</p>
---

# ts类型校验

## Heading 2

Here is the content.

### Heading 3

```ts title=".vuepress/config.ts"
import { defaultTheme } from '@vuepress/theme-default'
import { defineUserConfig } from 'vuepress'

export default defineUserConfig({
  title: '你好， VuePress',

  theme: defaultTheme({
    logo: 'https://vuejs.org/images/logo.png',
  }),
})
```


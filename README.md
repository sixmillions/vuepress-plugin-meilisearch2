# vuepress-plugin-meilisearch2

> **⚠️ Tip: This project is no longer maintained and has been moved to the official VuePress plugin [`@vuepress/plugin-meilisearch`](https://ecosystem.vuejs.press/plugins/search/meilisearch.html). [Github](https://github.com/vuepress/ecosystem/tree/main/plugins/search/plugin-meilisearch)**

![default-theme-use](./images/default-theme-search.gif)

```ts
import { defineUserConfig } from 'vuepress';
import { MeiliSearchPlugin } from 'vuepress-plugin-meilisearch2';

defineUserConfig({
  plugins: [
    MeiliSearchPlugin({
      host: '',
      apiKey: '',
      indexUid: '',
    })
  ]
})
```

See the [documentation](https://vuepress-plugin-meilisearch2.jinqiu.wang/) for more details

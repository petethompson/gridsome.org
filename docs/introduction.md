# Introduction to Gridsome

Gridsome is a static site generator powered by GraphQL and Vue.js. It uses GraphQL as a single source of truth for all data connected to the website. You can pull data from any CMS, local Markdown or content APIs into the GraphQL layer. Data can be explored in a local GraphQL playground and be inserted to any component quickly. It also has Transformer plugins that can manipulate the data pulled to GraphQL. Gridsome is highly inspired by Gatsby (A React.js alternative).

Gridsome was built because there was no good Vue.js alternative to Gatsby.


## How it works
Gridsome genreates all pages and endpoints at build time. It creates two versions of every page. One HTML page that search engines can crawl for SEO-purpose, and one JavaScript file that Gridsome uses for SPA after first page load. Next pages are loaded in the background with Service workers. This makes browsing around extremely fast and your site is 100%-SEO friendly. It even works offline.

Gridsome follows the [PRPL-pattern by Google.](https://developers.google.com/web/fundamentals/performance/prpl-pattern/) and optimizes your site automatic. You don't need to be a performance expert to make fast websites with Gridsome. Your site gets almost perfect scores on Google lighthouse out-of-the-box. These are some of the performance steps that Gridsome takes care of:

- Image compressing & lazy-loading ⚡️ 
- CSS & JS minification ⚡️ 
- Code-splitting ⚡️ 
- HTML compressing ⚡️ 
- Critical CSS (Plugin) ⚡️ 
- Full PWA & Offline-support (plugin) ⚡️


## The alternatives
-	**[VuePress.](//https://vuepress.vuejs.org/)** Another static site generator for Vue.js. It uses local markdown files for content and is perfect for documentation sites. It is possible to build anything in VuePress and Markdown (Like a blog f.ex), but its does not have the GraphQL layer that Gridsome has.

-	**[Nuxt.](https://nuxtjs.org/)**  An Universal Vue.js Framework that makes building Server side rendered (SSR) apps and websites easy. It also has a static site generator feature, but the main focus is SSR. It does not use a GraphQL like Gridsome does.

-	**[Gatsby.js](https://www.gatsbyjs.org/)**  Gridsome is highly inspired by Gatsby.js (React.js based). Gridsome is the Vue.js alternative to this framework.

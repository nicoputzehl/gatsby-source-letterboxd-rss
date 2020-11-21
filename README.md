gatsby-source-letterboxd-rss
===

translated into a gatsby-source plugin from a npm module 
[letterboxd](https://github.com/zaccolley/letterboxd)

# Getting Started

At the plugin in `root/plugins`

Example config
```js
  plugins: [
    {
      resolve: `gatsby-source-letterboxd-rss`,
      options: {
        letterboxdUserName: "theLetterboxdUsername"
      }
    }
  ],
  ```
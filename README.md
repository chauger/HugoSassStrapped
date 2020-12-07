# HugoSassStrapped

This repo contains a very basic skeleton Hugo theme that uses Bootstrap's SCSS files that get compiled and ran through Autoprefixer for ultimate compatibility.



## What is Hugo

Hugo is a fast and modern static site generator written in Go, and designed to make website creation fun again.

Hugo is a general-purpose website framework. Technically speaking, Hugo is a [static site generator](https://gohugo.io/about/benefits/). Unlike systems that dynamically build a page with each visitor request, Hugo builds pages when you create or update your content. Since websites are viewed far more often than they are edited, Hugo is designed to provide an optimal viewing experience for your website’s end users and an ideal writing experience for website authors.



## Autoprefixer CSS online

[Autoprefixer](https://autoprefixer.github.io/) is a PostCSS plugin which parses your CSS and adds vendor prefixes. This is implemented by leveraging Hugo PostCSS Pipe functions.



## Requirements

- [nodejs](https://nodejs.org/) to install the necessary dependances.
- [Hugo](https://github.com/gohugoio/hugo/releases) to run and compile the site. [Hugo installation instructions](https://gohugo.io/getting-started/installing/) can be found at http://www.gohugo.io.



## Installation

`$ npm install`



## Run

`$ npm run start`



## Build for Production

`$ npm run build`

This will create a `/public` folder that contains all your production ready files.



## Browser Compatibility

[Bootstrap supports](https://getbootstrap.com/docs/4.1/getting-started/browsers-devices/) the **latest, stable releases** of all major browsers and platforms. On Windows, **support for Internet Explorer 10-11 / Microsoft Edge**.

Alternative browsers which use the latest version of WebKit, Blink, or Gecko, whether directly or via the platform’s web view API, are not explicitly supported. However, Bootstrap should (in most cases) display and function correctly in these browsers as well. More specific support information is provided below.

You can find the supported range of browsers and their versions in the `postcss.config.js`

```
"browserslist": [
  "last 1 major version",
  ">= 1%",
  "Chrome >= 45",
  "Firefox >= 38",
  "Edge >= 12",
  "Explorer >= 10",
  "iOS >= 9",
  "Safari >= 9",
  "Android >= 4.4",
  "Opera >= 30"
]
```



## License

We use the [MIT license](https://github.com/sajari/sdk-react/blob/master/LICENSE)



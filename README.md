# Awesome Puppeteer with stars

> A curated list of awesome [puppeteer](https://developers.google.com/web/tools/puppeteer/) resources for controlling [headless](https://developers.google.com/web/updates/2017/04/headless-chrome) Chrome (or Chromium) over the [DevTools Protocol](https://chromedevtools.github.io/devtools-protocol/).

<p align="center">
  <img src="https://raw.githubusercontent.com/transitive-bullshit/awesome-puppeteer/master/logo.png" alt="Puppeteer Logo" width="200" />
</p>

* [![china](https://raw.githubusercontent.com/gosquared/flags/master/flags/flags/shiny/24/China.png) **中文/Chinese**](https://github.com/transitive-bullshit/awesome-puppeteer/blob/master/readme.zh.md) ⭐ 2,567 | 🐛 25 | 📅 2024-07-19

## Contents

* [Official](#official)
* [Packages](#packages)
* [Rendering and web scraping](#rendering-and-web-scraping)
* [Testing](#testing)
* [Services](#services)
* [Examples](#examples)
* [Articles](#articles)
* [Guides](#guides)
* [Related](#related)

## Official

* [GitHub](https://github.com/GoogleChrome/puppeteer) ⭐ 95,467 | 🐛 265 | 🌐 TypeScript | 📅 2026-08-19 - Official GitHub repository.
* [API](https://github.com/GoogleChrome/puppeteer/blob/master/docs/api.md) ⭐ 95,467 | 🐛 265 | 🌐 TypeScript | 📅 2026-08-19 - Official API docs.
* [Website](https://pptr.dev) - Official Website.
* [Homepage](https://developers.google.com/web/tools/puppeteer) - Official homepage.
* [Playground](https://try-puppeteer.appspot.com) - Hosted playground where you can experiment with Puppeteer.
* [FAQ](https://developers.google.com/web/tools/puppeteer/faq) - Official FAQ.
* [DevTools Protocol](https://chromedevtools.github.io/devtools-protocol/) - Chrome DevTools Protocol API Docs.

## Packages

* [puppeteer-recorder](https://github.com/checkly/puppeteer-recorder) ⚠️ Archived - Chrome extension that records your browser interactions and generates a Puppeteer script. 🔥
* [puppeteer-extra](https://github.com/berstend/puppeteer-extra) ⭐ 7,395 | 🐛 274 | 🌐 JavaScript | 📅 2024-07-18 - Wrapper to use stealth mode, custom user prefs, etc.
* [puppeteer-cluster](https://github.com/thomasdondorf/puppeteer-cluster) ⭐ 3,515 | 🐛 127 | 🌐 TypeScript | 📅 2026-03-01 - Cluster management for puppeteer.
* [chrome-aws-lambda](https://github.com/alixaxel/chrome-aws-lambda) ⭐ 3,287 | 🐛 77 | 🌐 TypeScript | 📅 2024-09-03 - Chromium binary compatible with AWS Lambda (kept up to date with puppeteer).
* [pwa-asset-generator](https://github.com/onderceylan/pwa-asset-generator) ⭐ 3,029 | 🐛 51 | 🌐 TypeScript | 📅 2026-06-01 - CLI to generate multi-platform PWA icons, splash screens and meta code based on web standards.
* [capture-website](https://github.com/sindresorhus/capture-website) ⭐ 2,013 | 🐛 0 | 🌐 JavaScript | 📅 2025-10-31 - Capture screenshots of websites.
* [@cliqz/adblocker-puppeteer](https://github.com/cliqz-oss/adblocker/tree/master/packages/adblocker-puppeteer) ⭐ 992 | 🐛 30 | 🌐 TypeScript | 📅 2026-08-18 - Efficient and flexible adblocker library to easily block ads and trackers.
* [capture-website-cli](https://github.com/sindresorhus/capture-website-cli) ⭐ 854 | 🐛 0 | 🌐 JavaScript | 📅 2025-11-01 - CLI to capture screenshots of websites.
* [timecut](https://github.com/tungs/timecut) ⭐ 651 | 🐛 33 | 🌐 JavaScript | 📅 2023-07-18 - Record smooth movies of web pages with JavaScript animations.
* [differencify](https://github.com/NimaSoroush/differencify) ⭐ 638 | 🐛 27 | 🌐 JavaScript | 📅 2020-06-02 - Library for visual regression testing.
* [headless-devtools](https://github.com/cowchimp/headless-devtools) ⭐ 554 | 🐛 16 | 🌐 JavaScript | 📅 2023-01-05 - Puppeteer plugin to get CSS Coverage or JS Heap snapshot.
* [docker-puppeteer](https://github.com/alekzonder/docker-puppeteer) ⭐ 480 | 🐛 23 | 🌐 JavaScript | 📅 2021-10-20 - Docker image with puppeteer installed.
* [puppeteer-lottie](https://github.com/transitive-bullshit/puppeteer-lottie) ⭐ 384 | 🐛 22 | 🌐 JavaScript | 📅 2023-07-25 - Renders [Lottie](http://airbnb.io/lottie) animations via [Puppeteer](https://github.com/GoogleChrome/puppeteer) ⭐ 95,467 | 🐛 265 | 🌐 TypeScript | 📅 2026-08-19 to **image**, **GIF** or **MP4**.
* [minimalcss](https://github.com/peterbe/minimalcss) ⭐ 356 | 🐛 43 | 🌐 JavaScript | 📅 2023-01-03 - Extracts the minimal / critical CSS used in a set of URLs.
* [timesnap](https://github.com/tungs/timesnap) ⭐ 240 | 🐛 29 | 🌐 JavaScript | 📅 2024-01-17 - Take screenshots of web pages at smooth intervals.
* [puppeteer-social-image](https://github.com/chrisvxd/puppeteer-social-image) ⭐ 219 | 🐛 18 | 🌐 JavaScript | 📅 2023-01-03 - Render social share images using HTML + CSS.
* [puppeteer-email](https://github.com/transitive-bullshit/puppeteer-email) ⭐ 167 | 🐛 10 | 🌐 JavaScript | 📅 2021-01-05 - Email automation driven by headless chrome.
* [puppeteer-email-cli](https://github.com/transitive-bullshit/puppeteer-email/tree/master/packages/puppeteer-email-cli) ⭐ 167 | 🐛 10 | 🌐 JavaScript | 📅 2021-01-05 - CLI for email automation driven by headless chrome.
* [puppeteer-lottie-cli](https://github.com/transitive-bullshit/puppeteer-lottie-cli) ⭐ 150 | 🐛 26 | 🌐 JavaScript | 📅 2023-08-04 - CLI for this [puppeteer-lottie](https://github.com/transitive-bullshit/puppeteer-lottie) ⭐ 384 | 🐛 22 | 🌐 JavaScript | 📅 2023-07-25.
* [puppeteer-explore](https://github.com/laispace/puppeteer-explore) ⭐ 146 | 🐛 0 | 📅 2017-10-19 - Utility library for puppeteer.
* [puppeteer-instagram](https://github.com/transitive-bullshit/puppeteer-instagram) ⭐ 117 | 🐛 23 | 🌐 JavaScript | 📅 2022-12-07 - Instagram automation driven by headless chrome.
* [puppet-canvas](https://github.com/pshihn/puppet-canvas) ⭐ 66 | 🐛 8 | 🌐 TypeScript | 📅 2023-05-07 - HTML5 Canvas implementation for Node.JS backed by Puppeteer.
* [puppeteer-render-text](https://github.com/transitive-bullshit/puppeteer-render-text) ⭐ 65 | 🐛 1 | 🌐 JavaScript | 📅 2023-11-16 - Robust text renderer using headless chrome.
* [facebook-birthday-cli](https://github.com/igniteram/facebook-birthday-cli) ⭐ 58 | 🐛 4 | 🌐 TypeScript | 📅 2019-09-01 - Command Line Interface to list and wish your facebook friends.
* [puppeteer-github](https://github.com/transitive-bullshit/puppeteer-github) ⭐ 18 | 🐛 2 | 🌐 JavaScript | 📅 2020-07-11 - GitHub automation driven by headless chrome.
* [puppeteer-instagram-cli](https://github.com/transitive-bullshit/puppeteer-instagram-cli) ⭐ 14 | 🐛 0 | 🌐 JavaScript | 📅 2020-07-11 - CLI for Instagram automation driven by headless chrome.
* [puppeteer-github-cli](https://github.com/transitive-bullshit/puppeteer-github-cli) ⭐ 7 | 🐛 0 | 🌐 JavaScript | 📅 2020-07-11 - CLI for GitHub automation driven by headless chrome.
* [browserless](https://browserless.js.org) – A puppeteer-like Node.js library for interacting with Headless production scenarios.

## Rendering and web scraping

* [Apify SDK](https://github.com/apifytech/apify-js) ⭐ 25,432 | 🐛 147 | 🌐 TypeScript | 📅 2026-08-19 - Scalable web crawling and scraping library. 🕷️
* [headless-chrome-crawler](https://github.com/yujiosaka/headless-chrome-crawler) ⭐ 5,636 | 🐛 33 | 🌐 JavaScript | 📅 2023-04-29 - Distributed crawler powered by Headless Chrome.
* [BrowserGap](https://github.com/dosyago/BrowserGap) ⭐ 3,898 | 🐛 0 | 🌐 Shell | 📅 2026-08-13 - Remote browser webview powered by Headless Chrome.
* [decktape](https://github.com/astefanutti/decktape) ⭐ 2,422 | 🐛 50 | 🌐 JavaScript | 📅 2026-07-13 - PDF exporter for HTML presentation frameworks.
* [Wbot](https://github.com/vasani-arpit/WBOT) ⭐ 1,013 | 🐛 16 | 🌐 JavaScript | 📅 2025-09-23 - Configurable Whatsapp auto reply bot.
* [Puppetron](https://github.com/cheeaun/puppetron) ⭐ 553 | 🐛 8 | 🌐 JavaScript | 📅 2022-06-17 - Demo site that shows how to use Puppeteer and Headless Chrome to render pages. Inspired by [GoogleChrome/rendertron](https://github.com/GoogleChrome/rendertron) ⚠️ Archived.
* [whatspup](https://github.com/sarfraznawaz2005/whatspup) ⚠️ Archived - WhatsApp chat from commandline/console/cli.
* [puppeteer-renderer](https://github.com/zenato/puppeteer-renderer) ⭐ 333 | 🐛 1 | 🌐 TypeScript | 📅 2026-07-19 - Generic web page renderer.
* [prerenderer](https://github.com/Tribex/prerenderer) ⭐ 228 | 🐛 7 | 🌐 TypeScript | 📅 2024-09-26 - Framework-agnostic prerendering for sites and SPAs.
* [pupperender](https://github.com/LasaleFamine/pupperender) ⭐ 120 | 🐛 7 | 🌐 JavaScript | 📅 2026-02-25 - Express middleware that renders PWAs for bots using puppeteer.
* [webgif](https://github.com/anishkny/webgif) ⭐ 107 | 🐛 14 | 🌐 JavaScript | 📅 2023-10-28 - Easily generate animated GIFs from websites.
* [ReedD/crawler](https://github.com/ReedD/crawler) ⭐ 48 | 🐛 0 | 🌐 JavaScript | 📅 2020-03-30 - BFS site crawler.

## Testing

* [jest-puppeteer](https://github.com/smooth-code/jest-puppeteer) ⭐ 3,546 | 🐛 22 | 🌐 TypeScript | 📅 2026-03-26 - Run your tests using Jest & Puppeteer.
* [expect-puppeteer](https://github.com/smooth-code/jest-puppeteer/tree/master/packages/expect-puppeteer) ⭐ 3,546 | 🐛 22 | 🌐 TypeScript | 📅 2026-03-26 - Assertion library for Puppeteer.
* [storybook-chrome-screenshot](https://github.com/tsuyoshiwada/storybook-chrome-screenshot) ⭐ 755 | 🐛 96 | 🌐 TypeScript | 📅 2026-08-14 - Storybook addon to save screenshots of your stories via puppeteer.
* [mochify](https://github.com/mantoni/mochify.js) ⭐ 348 | 🐛 13 | 🌐 JavaScript | 📅 2023-12-24 - TDD with Browserify, Mocha, Headless Chrome and WebDriver.
* [rize](https://github.com/g-plane/rize) ⚠️ Archived - High-level, fluent and chainable API provided library for puppeteer.
* [wendigo](https://github.com/angrykoala/wendigo) ⭐ 150 | 🐛 21 | 🌐 JavaScript | 📅 2024-03-08 - Puppeteer wrapper to ease test development.
* [mocha-headless-chrome](https://github.com/direct-adv-interfaces/mocha-headless-chrome) ⭐ 94 | 🐛 18 | 🌐 JavaScript | 📅 2025-07-31 - Run client-side mocha tests in the command line through Puppeteer.
* [angular-puppeteer-demo](https://github.com/Quramy/angular-puppeteer-demo) ⭐ 61 | 🐛 2 | 🌐 TypeScript | 📅 2018-04-12 - Demos how to use Puppeteer in Karma.
* [e2e](https://github.com/dollarshaveclub/e2e) ⭐ 33 | 🐛 6 | 🌐 JavaScript | 📅 2020-01-02 - End-to-end testing.
* [tupe](https://github.com/jl-/tupe) ⭐ 2 | 🐛 0 | 🌐 JavaScript | 📅 2018-10-18 - A generic unit-testing runner for front-end.
* [puppetry](https://puppetry.app/) - Scriptless E2E test automation tool.

## Services

* [browserless](https://github.com/joelgriffith/browserless) ⭐ 13,606 | 🐛 11 | 🌐 TypeScript | 📅 2026-08-18 - Headless Chrome as a service letting you execute Puppeteer scripts remotely.
* [url-to-pdf-api](https://github.com/alvarcarto/url-to-pdf-api) ⭐ 7,103 | 🐛 60 | 🌐 HTML | 📅 2024-01-18 - Web page PDF rendering done right. Self-hosted service for rendering.
* [Puppeteer Sandbox](https://puppeteersandbox.com) - Puppeteer sandbox environment as a service. Runs Puppeteer scripts and allows saving and embedding them in external sites and markdown files.
* [checkly](https://checklyhq.com) - Monitoring SaaS that uses Puppeteer to check availability and correctness of web pages and apps.
* [FusionExport](https://www.fusioncharts.com/fusionexport) - Export dashboards or charts to PDF or images. Looks mature.
* [ProxyCrawl](https://proxycrawl.com) - Headless Chrome as a service.
* [microlink.io](https://microlink.io) – Turns any site into data.
* [HeadlessTesting](https://headlesstesting.com) – Headless Chrome testing with Puppeteer in the Cloud.
* [FloodRunner](https://floodrunner.dev) - Open-source monitoring solution using puppeteer tests.
* [The Browser Conference](https://www.accelevents.com/e/the-browser-conference-23) - A free half-day virtual conference focused on Browser Automation, Data Extraction and Testing.
* [Doczilla](https://www.doczilla.app) - SaaS API empowering the generation of screenshots or PDFs directly from HTML/CSS/JS code.
* [BrowserCat](https://www.browsercat.com) - Hosted Chrome/Chromium to deploy and scale your Puppeteer scripts affordably and reliably. Offers forever-free plan.

## Examples

* [Official examples](https://github.com/puppeteer/puppeteer/tree/main/examples) ⭐ 95,467 | 🐛 265 | 🌐 TypeScript | 📅 2026-08-19 - Quality examples as part of the official puppeteer repo.
* [puppeteer-examples](https://github.com/checkly/puppeteer-examples) ⚠️ Archived - Quality examples for real life use cases such as scraping web pages and common login scenarios.
* [Official use case-driven examples](https://github.com/GoogleChromeLabs/puppeteer-examples) ⭐ 2,415 | 🐛 39 | 🌐 JavaScript | 📅 2026-06-21 - More complex, high quality, use case-driven examples.
* [puppeteer-deep](https://github.com/zhentaoo/puppeteer-deep) ⭐ 1,210 | 🐛 9 | 🌐 JavaScript | 📅 2020-11-13 - Demos on crawling, UI automation, trace API and so on.
* [html\_to\_pdf](https://github.com/chuongtrh/html_to_pdf) ⭐ 120 | 🐛 3 | 🌐 JavaScript | 📅 2026-05-29 - Generate a simple invoice PDF from HTML.
* [instagram-get-images](https://github.com/aofdev/instagram-get-images) ⭐ 80 | 🐛 8 | 🌐 JavaScript | 📅 2026-07-29 - Instagram image scraper.
* [puppeteer-samples](https://github.com/sweekson/puppeteer-samples) ⭐ 19 | 🐛 0 | 🌐 JavaScript | 📅 2017-09-18 - Misc examples.
* [daily-signin](https://github.com/yidinghan/daily-signin) - Signin and control various chinese sites.
* [linkedin-autoaccept](https://github.com/MRdotB/linkedin-autoaccept) - Auto-accept invitations on linkedin.

## Articles

* [Headless Chrome: an answer to server-side rendering JS sites](https://developers.google.com/web/tools/puppeteer/articles/ssr) - By a member of the Google headless chrome team.
* [Getting started with Puppeteer and Chrome Headless for Web Scraping](https://medium.com/@e_mad_ehsan/getting-started-with-puppeteer-and-chrome-headless-for-web-scrapping-6bf5979dee3e) - Excellent article detailing how to automate GitHub login and scraping.
* [A Guide to Automating & Scraping the Web with JavaScript (Chrome + Puppeteer + Node JS)](https://codeburst.io/a-guide-to-automating-scraping-the-web-with-javascript-chrome-puppeteer-node-js-b18efb9e9921) - Excellent, thorough article.
* [Chromeless, Chrominator, Chromy, Navalia, Lambdium, GhostJS, AutoGCD](https://medium.com/@kensoh/chromeless-chrominator-chromy-navalia-lambdium-ghostjs-autogcd-ef34bcd26907) - Alternative Headless Chrome Projects.
* [What's the difference between Chromium and Chrome?](https://www.howtogeek.com/202825/what%E2%80%99s-the-difference-between-chromium-and-chrome/)
* [NodeJs Scraping with Puppeteer](https://learnscraping.com/nodejs-web-scraping-with-puppeteer/) - IMDB Scraping example.

## Guides

* [theheadless.dev](https://theheadless.dev) - Practical guides and runnable examples on Puppeteer (and Playwright).

## Related

* [pyppeteer](https://github.com/pyppeteer/pyppeteer) ⭐ 3,941 | 🐛 213 | 🌐 Python | 📅 2024-06-29 - Unofficial Python port of Puppeteer.
* [puppeteer-sharp](https://github.com/kblok/puppeteer-sharp) ⭐ 3,912 | 🐛 10 | 🌐 C# | 📅 2026-08-17 - Port of Puppeteer to .NET.
* [foxr](https://github.com/deepsweet/foxr) ⚠️ Archived - Node.js API to control Firefox. 🦊
* [capybara-chrome](https://github.com/carezone/capybara-chrome) ⭐ 28 | 🐛 2 | 🌐 Ruby | 📅 2021-06-04 – Unofficial Ruby port of Puppeteer.

## Contribute

Contributions welcome! Please read the [contributing guideline](contributing.md) first.

## License

[![CC0](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](http://creativecommons.org/publicdomain/zero/1.0)

To the extent possible under law, [Travis Fischer](https://github.com/transitive-bullshit) has waived all copyright and related or neighboring rights to this work.

Support my OSS work by <a href="https://twitter.com/transitive_bs">following me on twitter <img src="https://storage.googleapis.com/saasify-assets/twitter-logo.svg" alt="twitter" height="24px" align="center"></a>

***

> _Enhansomed by [enhansome](https://github.com/enhansome) on 2026-08-19._

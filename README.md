# Personal Webpage

![](./particle.png)

The Webpage features:

- Gulp
- SASS
- Sweet Scroll
- Particle.js
- BrowserSync
- Font Awesome and Devicon icons
- Google Analytics
- Info Customization

## Basic Setup

1. [Install Jekyll](http://jekyllrb.com)
2. Fork the [Particle Theme](https://github.com/aruzikulov/aruzikulov.github.io)
3. Clone the repo you just forked.
4. Edit `_config.yml` to personalize your site.

## Site and User Settings

You have to fill some informations on `_config.yml` to customize your site.

```
# Site settings
description: Akhmadjon Ruzikulov's Personal Webpage
baseurl: "" # the subpath of your site, e.g. /blog/
url: "https://aruzikulov.github.io" # the base hostname & protocol for your site

# User settings
username: Akhmadjon Ruzikulov
user_description: Co-Founder & CTO at OBORCHAIN <br> Software Developer
user_title: Akhmadjon Ruzikulov
email: aruzikulov@hust.edu.cn
twitter_username: aruzikulov
github_username:  aruzikulov
gplus_username:  ruzikulov
```

**Don't forget to change your url before you deploy your site!**

## Color and Particle Customization
- Color Customization
  - Edit the sass variables
- Particle Customization
  - Edit the json data in particle function in app.js
  - Refer to [Particle.js](https://github.com/VincentGarreau/particles.js/) for help

## Running the blog in local

In order to compile the assets and run Jekyll on local you need to follow those steps:

- Install [NodeJS](https://nodejs.org/)
- Run `npm install`
- Run `gulp`

## Questions

Having any issues file a [GitHub Issue](https://github.com/aruzikulov/aruzikulov.github.io/issues).

## License

This theme is free and open source software, distributed under the The MIT License. So feel free to use this Jekyll theme anyway you want.

## Credits

This theme was partially designed with the inspiration from these fine folks
- [Willian Justen](https://github.com/willianjusten/will-jekyll-template)
- [Vincent Garreau](https://github.com/VincentGarreau/particles.js/)

A very minimal hugo theme

example: [my blog](https://www.mikeyobrien.com)

# Features

- google analytics

# TODO

- [ ] SEO optimization
- [ ] Multilingual
- [ ] Pagination

## Installation

Inside the folder of your hugo site run:

```sh
$ git submodule add https://github.com/mikeyobrien/hugo-theme-addison.git /themes/addison
```

## Getting Started

### Update Config File

```sh
baseURL = "www.yourbase.com"
languageCode = "en-us"
title = "Your Name"
theme = "addison"
googleAnalytics = "UA-123-45"


[menu]
  [[menu.main]]
  identifier = "about"
  name = "Title | Location, USA"
  url = "/about/"
  weight = 1
```

Check everything is working correctly

```sh
$ hugo server
```

# Contributing

If you find a bug or have an idea for a feature, feel free to write an issue

## License

MIT

(c) Mikey O'Brien 2020

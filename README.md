# haruka-simple-theme

a hugo theme

version 0.1v

### Demo

https://shina346.github.io/haruka-simple-theme/

## TODO
- footer bug
- Rss
- color

### install

```shell
git clone https://github.com/ShinA346/haruka-simple-theme themes/haruka-simple-theme
```

### usage

```shell
hugo server -t haruka-simple-theme
```

### Configuration

config.toml

```toml
theme = "haruka-simple-theme"
baseURL = "<your site url>"
title = "<your site title>"
copyright = "<your stie name>"
paginate = 3
footnoteReturnLinkContents = "^"
languageCode = "en"
DefaultContentLanguage = "en"
enableInlineShortcodes = true
PaginatePath = ""
[menu]
  [[menu.main]]
    identifier = "about"
    name = "About"
    url = "/about/"
    weight = 10

[taxonomies]
category = "categories"
tag = "tags"
```


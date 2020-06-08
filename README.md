# haruka-simple-theme

a hugo theme

version 0.2v

### Demo

https://shina346.github.io/haruka-simple-theme/

## TODO
- Discuss
- List post pictures

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
copyright = "<your stie year>"
paginate = 3
footnoteReturnLinkContents = "^"
languageCode = "en"
DefaultContentLanguage = "en"
enableInlineShortcodes = true
PaginatePath = ""
[menu]
  [[menu.main]]
    name = "About"
    url = "/about"
    weight = 1
  [[menu.main]]
    name = "Archive"
    url = "/archives"
    weight = 2
  [[menu.main]]
    name = "Rss"
    url = "/index.xml"
    weight = 3
  [[menu.foot]]
    name = "2020"

[Author]
name = "<your name>"

[taxonomies]
category = "categories"
tag = "tags"
```


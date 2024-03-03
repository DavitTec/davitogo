# davitogo

> a new Hugo Theme, called ***davitogo***.  

[toc]

We are building a new Hugo Theme, called ***davitogo*** for our
own use on a hugo static website project (later to be published).

This theme is *work in progress* development and version is [0.0.1](CHANGELOG.md#[0.0.1] )
The theme can be accessed and downloaded from Gitbhub repository 
[github.com/DavitTec/davitogo](github.com/DavitTec/davitogo)

You will need to have the latest version of [Hugo][1] 

The plan is to have a theme which supports content on your front page
and some basic page structure.
The focus is on style and structure not content. However, we may develop
a documents directory about the use of this theme template under */contents/davitogo*.

For more information about this Project and theme, head over to the [About page](about.md)

## Getting started

Let initial Hogo Structure in the same directory for our project. 
We assume init inside non-empty directory

```bash
hugo new site --force .
```

Changed [config.toml](config.toml) contents to reflect the details of your site.

```bash
baseURL = "http://localhost:1313/"
languageCode = "en-us"
title = "Davitogo"
```

We are going to add new theme skeleton so we can add and change some of the theme configuration [theme.toml](themes/davitogo/theme.toml)

```bash
hugo new theme davitogo
```

Features

## Visual Code 

This project comes with settings for [Visual code](https://code.visualstudio.com/) and extension recommendations

You can view recommended extensions within VScode

```bash
Ctrl+Shift+p 
> Show Recommended Extensions
```

Because config file are TOML, I added an extension to Visualcode to help with formatting.

- [Even Better TOML](https://marketplace.visualstudio.com/items?itemName=tamasfe.even-better-toml&ssr=false#user-content-toml-version-100-support)

  - There is an issue with "theme.toml

    ```bash
    
    ```

    

---

## References

[1]: https://gohugo.io	"Hugo Documentation"


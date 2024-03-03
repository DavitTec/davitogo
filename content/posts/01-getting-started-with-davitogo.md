---
title: "01 Getting Started with Davitogo"
date: 2024-02-27
draft: true
company:
  name: DAVIT
companyname: "DAVIT"
tags: ["Theme", "Hugo",  "HowTo"]
---

## Overview

Hugo automatically takes the first 70 words of your content as its summary and stores it into the summary variable

This Version Tag Release - Tag [v0.0.3](https://github.com/DavitTec/davitogo/releases/tag/v0.0.3) is the the basic structure of the Hugo Theme - **Davittogo**

We are about to start to add some styles, using main.css. 

We added Font Awesome stylesheet to load some icon buttons

## Add content

To create a new post run this command at project root level. Be aware of case sensitivity and spaces in names. I added a number prefix which might be usefull for sorting posts by title order.

```bash
hugo new posts/02-adding-styling.md
```

Please note the `draft` value in the [front matter](https://gohugo.io/content-management/front-matter/) is `true`. By default, Hugo does not publish draft content when you build the site. 

The above page is now created here : [posts/02-adding-styling.md](../02-adding-styling/)

It is important to start server id development node to include *draft* content pages

```bash
hugo server -D
```

Learn more about [draft, future, and expired content](https://gohugo.io/getting-started/usage/#draft-future-and-expired-content).



<!--more-->

end

---

This site, [{{< base_url >}}]({{< base_url >}}) is operated by {{< param "company.name" >}}
---
title: "Hugo Start"
date: 2023-08-13T21:32:36+02:00
draft: true
tags:
  - webpages
categories:
  - technika
---

## Create a site

Run these commands to create a Hugo site with the Ananke theme. The next section provides an explanation of each command.

```
hugo new site quickstart
cd quickstart
git init
git submodule add https://github.com/theNewDynamic/gohugo-theme-ananke.git themes/ananke
echo "theme = 'ananke'" >> hugo.toml
hugo server -D
```

## Add content
Add a new page to your site.

```hugo new posts/my-first-post.md```





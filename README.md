# Delta - Hugo theme
Delta is a minimal and clean theme for hugo with a org-ish UI.

Forked from [Archie Theme](https://github.com/athul/archie)

## Demo

[Check the Demo](https://athul.github.io/archie/) hosted on GitHub Pages :smile: . You can find the source code to that in the `site` branch of this repository

![](/images/theme.png)
![](/images/archie-dark.png)
## Feature
- Google Analytics Script
- Callouts
- Tags
- Auto Dark Mode(based on system theme)
- tl:dr; frontamatter

## Installation
In your Hugo website directory, create a new folder named theme and clone the repo
```bash
$ mkdir themes
$ cd themes
$ git clone https://github.com/DarkBuffalo/Delta.git
```
Edit the `config.toml` file with `theme="Delta"`
For more information read the official [setup guide](https://gohugo.io/overview/installing/) of Hugo.

## Writing Posts
Create a new `.md` file in the *content/posts* folder
```yml
---
title: Title of the post
description:
date:
tldr: (optional)
draft: true/false (optional)
tags: [tag names] (optional)
---
```

## Credits
Forked from [Archie Theme](https://github.com/vividvilla/ezhil) and Licensed under MIT License 


----

## Config of the Demo Site

```toml
baseURL = "https://athul.github.io/archie/"
languageCode = "en-us"
title = "Archie"
theme="archie"
copyright = "© Athul"
# Code Highlight
pygmentsstyle = "monokai"
pygmentscodefences = true
pygmentscodefencesguesssyntax = true

paginate=3 # articles per page

[params]
	mode="auto" # color-mode → light,dark or auto
	useCDN=false # don't use CDNs for fonts and icons, instead serve them locally.
	subtitle = "Minimal and Clean [blog theme for Hugo](https://github.com/athul/archie)"

# Social Tags

[[params.social]]
name = "GitHub"
icon = "github"
url = "https://github.com/athul/archie"

[[params.social]]
name = "Twitter"
icon = "twitter"
url = "https://twitter.com/athulcajay/"

[[params.social]]
name = "GitLab"
icon = "gitlab"
url = "https://gitlab.com/athul/"

# Main menu Items

[[menu.main]]
name = "Home"
url = "/"
weight = 1

[[menu.main]]
name = "All posts"
url = "/posts"
weight = 2

[[menu.main]]
name = "About"
url = "/about"
weight = 3

[[menu.main]]
name = "Tags"
url = "/tags"
weight = 4
```
---

If you liked my work please consider supporting me on [BuymeACoffee](https://www.buymeacoffee.com/athulca)

<a href="https://www.buymeacoffee.com/athulca" target="_blank"><img src="https://cdn.buymeacoffee.com/buttons/v2/default-red.png" alt="Buy Me A Coffee" height="41" width="174" ></a>

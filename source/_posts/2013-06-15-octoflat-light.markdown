---
layout: post
title: "Octoflat Light"
date: 2013-06-15 13:39
comments: true
categories: octoflat
---

Since I've been asked by multiple people and since I wanted to make the theme more customizable for everyone, I've updated the theme to have a new color scheme. In doing so, I've made the theme easier for anyone to customize. If you don't like
any of the colors that come out of the box, edit the **octoflat/sass/_colors.scss** file and customize your colors.

## Changing the Color Scheme

The theme has two color scheme options: light and dark. The dark color scheme is the one enabled by default.

To change the color scheme after you've installed the theme, do the following:

- Go to the sass directory 
- Edit the **_colors.scss** file.
- Modify the '$theme-color' variable to be set to either 'light' or 'dark'

{% codeblock %}
$ cd your_octopress_dir/.themes/octoflat/sass
$ vim _colors.scss
// edit the $theme-color variable
// (ex. $theme-color: light;)
{% endcodeblock %}
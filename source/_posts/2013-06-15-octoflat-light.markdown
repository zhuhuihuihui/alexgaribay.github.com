---
layout: post
title: "Octoflat Light"
date: 2013-06-15 13:39
comments: true
categories: octoflat
---

Since I've been asked by multiple people and since I wanted to make the theme more customizable for everyone, I've updated the theme to have a new color scheme. In doing so, I've made the theme easier for anyone to customize. If you don't like
any of the colors that come out of the box, just edit the **sass/custom/_colors.scss** file and customize your colors after the theme is installed.

## Changing the Color Scheme

The theme has two color scheme options: light and dark. The dark color scheme is the one enabled by default.

To change the color scheme after you've installed the theme, do the following:

- Go to the sass/custom directory 
- Edit the **_colors.scss** file.
- Remove the commented out lines that are specified

{% codeblock %}
$ cd your_octopress_dir/sass/custom
$ vim _colors.scss
// Delete the commented lines (3 and 18)
{% endcodeblock %}

After changing the colors, make sure to recompile the sass directory.

{% codeblock %}
$ rake generate
{% endcodeblock %}

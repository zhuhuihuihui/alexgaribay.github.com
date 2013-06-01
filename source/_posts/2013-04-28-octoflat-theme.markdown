---
layout: post
title: "Octoflat Theme"
date: 2013-04-28 12:11
comments: true
categories: [octoflat, flat-design]
---

## Beginnings ##
I have created my first Octopress theme today called Octoflat. The theme is inspired by flat design. It uses [Twitter Bootstrap]("http://twitter.github.io/bootstrap/") and Designmodo's [Flat UI]("https://github.com/designmodo/Flat-UI"). All the colors chosen are the colors listed on Flat-UI's demo page.

## Installing the theme

#### As a submodule ####

{% codeblock %}
cd your_octopress_dir
git submodule add https://github.com/alexgaribay/octoflat .themes/octoflat
rake install['octoflat']
rake generate
{% endcodeblock %}

#### Grabbing the latest updates as a module #####

{% codeblock %}
cd your_octopress_dir
git submodule update
{% endcodeblock %}

#### As a clone ####

{% codeblock %}
cd your_octopress_dir
git clone https://github.com/alexgaribay/octoflat .themes/octoflat
rake install['octoflat']
rake generate
{% endcodeblock %}

---------

## Configuring Navigation ##
Add a navigation section to your _config.yml. Doing this allows the navbar to highlight the active page. Use the following format:

{% codeblock %}
navigation:
- text: Home
  url: /index.html
{% endcodeblock %}

#### Adding New Pages ####

Create new pages by using the following command:

{% codeblock %}
rake new_page['new_page_name.md']
{% endcodeblock %}

Go back to update your _config.yml file:

{% codeblock %}
navigation:
- text: Home
  url: /index.html
- text: New Page Title
  url: /new_page_name.html
{% endcodeblock %}

---------

#### Pull Requests Welcome ####
I need help making the theme more customizable to the end user. So any help in doing so would be greatly appreciated. Any suggestions are welcome as well!
![Gutenberg]()

# Hugo Theme Gutenberg

> Micro publishers Hugo based shop & blog. 

Created this theme to support a local micro publishing company, with this site they show & tell their readers about their books, sell them, vía Snipcart integration and keep their followers up to date with the blog.

[Demo site](https://gcaracuel.github.io/hugo-theme-gutenberg/)

## Introduction

**Features:**

* Home page to show your main books and list all the other books in a slider
* Easy blog system to show your audience any news related to your books or any other topic
* Books/Product pages. Fully customizable sections.
* Contact form to receive your users emails
* Multiple language support in all the pages.
* Google Analytics integration ready
* E-commerce using [Snipcart](https://snipcart.com/)

## Requirements

It's necessary to use **Hugo ≥ 0.78.0**.

A hosting provider, Github Pages or any other site like this is fine.

## Installation

Clone / Download this repository to `theme` folder, feel free to copy content from exampleSite and start editing it

## Demo site / Build your site

![Example site](https://gcaracuel.github.io/hugo-theme-gutenberg/)

Using exampleSite structure you could have a clear picture of how to build your own site using Gutenberg theme:

```
├── assets
│   └── css
│       └── custom.css                              # Use this file to override theme CSS configuration 
├── config.toml                                     # Config site file, check exampleSite for more details
├── content
│   ├── < language long name >                      # You will a folder here and configure homepage for each supported language
│   │   ├── blog
│   │   │   ├── _index.md
│   │   │   └──  < blogpost >.md                     # Blog post file. Check examples at exampleSite 
│   │   ├── books
│   │   │   ├── _index.md
│   │   │   └──  < book >.md                         # Book info site file. Check examples at exampleSite
│   │   ├── contact
│   │   │   └── _index.md
│   │   ├── privacy-policy
│   │   │   └── _index.md
│   │   └── terms-conditions
│   │       └── _index.md
├── data
│   ├── < laguange code >                           # You will a folder here and configure homepage for each supported language 
│   │   └── homepage.yml                            # Homepage sections config file. Check exampleSite for more details
├── i18n
│   └── < language code >.yaml                      # Name this file using language code. Use it to translate buttons, menus..
├── static
│   └── images                                      # Place under this folder any image you will use in your site
|       └── favicon.ico 
│   └── preloader.gif                               # This gif file will be shown while a new page is loading
└── themes ->  hugo-theme-gutenberg                 # Here is where you should have already cloned this theme
```

Check exampleSite folder to check how we did build our demo site.

## Donate

If you use this theme consider donating some. As you can read in the licensing section this is not required but will make this guy happy, our support is greatly appreciated :)

<a href="https://www.buymeacoffee.com/gcaracuel" target="_blank"><img src="https://www.buymeacoffee.com/assets/img/custom_images/orange_img.png" alt="Buy Me A Coffee" style="height: 41px !important;width: 174px !important;box-shadow: 0px 3px 2px 0px rgba(190, 190, 190, 0.5) !important;-webkit-box-shadow: 0px 3px 2px 0px rgba(190, 190, 190, 0.5) !important;" ></a>


## Licensing

This comes with MIT license so you can use this in to build your own site.

Do not hesitate to open issues in this project if you need help with this theme.

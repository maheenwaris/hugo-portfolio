## Hugo portfolio

Designed a simple one-page Bootstrap portfolio website with an elegant light theme, perfect for presenting a comprehensive overview of your professional identity and achievements.

## Setup

Make a new Hugo site

```
hugo new site {sitename}
cd {sitename}
git clone https://github.com/maheenwaris/hugo-portfolio.git themes/hugo-portfolio
```

Copy `examplesite/config.toml` files to yours for quick setup

```
cp themes/hugo-portfolio/examplesite/config.toml .
```

Open `config.toml` and edit as per your liking.

## Guide

### Basics

```toml
baseURL = "https://hugo-portfolio.maheenwaris.com"
languageCode = 'en-us'
theme = "hugo-portfolio"
title = "Hugo Portfolio"

[Params]
    favicon = "/images/logo.png"
    subheading = "Frontend Web Developer"
    description = "I am keen on utilizing my expertise, aptitudes, and capabilities to contribute towards the success of a dynamic and gratifying organization that recognizes the value of my proficiencies in Web Development and Responsive Web Design. I aspire to pursue professional growth opportunities in exchange for my unwavering commitment, solid work ethics, and integrity, all of which would be dedicated towards achieving superior performance.I am passionate about my work and always strive to create innovative designs, learn new techniques, and incorporate animations into my work. I am excited about the opportunity to offer my services and contribute my skills to your organization."
    upform = "https://formspree.io/f/"
    Projects = [
    {url = "https://hugo-portfolio.maheenwaris.com", image = "hugo-portfolio.png", title = "Hugo Theme", tag = ["GO", "HTML", "CSS"]},
    {url = "https://github.com/maheenwaris/JS-Converters", image = "js-convert.png", title = "JS Converters", tag = ["JavaScript", "HTML", "CSS"]},
    {url = "https://github.com/maheenwaris/CourseWork-at-career/tree/main/Jewellery%20page", image = "jewel.png", title = "All Products", tag = ["Python", "HTML", "CSS"]},
    ]
    Timeline = [
        {title = "YouTube Content Creators", till = "Today", since = "6 Years", description = "My humble attempt at building my version of the digital world one step at a time by documenting my coding journey and creating software engineering and computer science content to help those coming behind me."},

        {title = "Solo Indie Developer", till = "2019", since = "4 Years", description = "I'm a solo indie developer building software for myself and clients to showcase on YouTube. All coding projects are built from the ground up, from planning and designing all the way to solving real-life problems with code."},

        {title = "First Line of Code", till = "2013", since = "6 Years", description = "I wrote my first line of real code that started this journey into digital craftsmanship that I never could've imagined, especially as someone who never saw themselves as anything other than a blue collar worker."}
    ]
    socialIcons = [
        {name = "twitter", url = "https://twitter.com/"},
        {name = "facebook", url = "https://facebook.com/"},
        {name = "github", url = "https://github.com/"},
        {name = "instagram", url = "https://instagram.com/"},
        {name = "tiktok", url = "https://tiktok.com/"},
    ]
```

### Formspree
- **Formspree** is a web service that simplifies form creation for websites.
- **How to Use:** Sign up for an account, create your form, and embed it into your website for easy data collection.
- Start receiving form submissions and configure notifications from your Formspree dashboard.

You should remove links to socials which you don't want to mention.
Now you can publish it to your host.

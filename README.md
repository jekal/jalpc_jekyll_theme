<!-- Banner Section  -->
<div align="center">
    <img src="static/assets/img/landing/sysadmin_banner.png" alt="System & Network Administrator" height="auto" width="auto">
</div>

<!-- Project title -->
<div align="center">
    <a href="https://git.io/typing-svg"><img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&pause=1000&center=true&width=435&lines=Personnal+Portfolio" alt="Project Name Typing" /></a>
</div>

<!-- Shields -->
<div align="center">
<a href="https://alexispages.github.io/portfolio/"><img alt="Website status" src="https://img.shields.io/website?down_color=red&down_message=offline&label=portfolio&style=for-the-badge&up_color=green&up_message=online&url=https%3A%2F%2Falexispages.github.io/portfolio/"></a>
<a href="https://www.linkedin.com/in/alexis-pag%C3%A8s"><img alt="Alexis PAGES LinkedIn" src="https://img.shields.io/badge/LinkedIn-Alexis%20PAGES-blue?logo=LinkedIn&style=for-the-badge"></a>
</div>

# About
This is a portfolio build using Jekyll to present my career path and the projects I've completed.

# Getting started

## Web access

You can access the website directly [here](https://cv.alexispages.pro)

## Local testing

You can run the website locally. To do so:
- Clone this repository locally
```bash
$ git clone https://github.com/alexispages/alexispages.github.io
```
- Please be sure to [meet the requirements](#requirements) (Ruby and Github pages gem)

- Type the following in order to "serve" the site

```
$ jekyll serve
```

This will first run a build that will create (or modify) a `_site/ directory`, containing everything from `assets/`, and then the `index.md` and all `pages/*.md` files, converted to html. (So there’ll be `_site/index.html` and the various `_site/pages/*.html.`).

By default, jekyll serve uses the `--watch` flag that will rebuild the Jekyll site when a file changes.

- Now you can access to the website on your favorite web browser by going to `http://localhost:4000`

## Change local URL

- If you are already using port 4000 locally, you can change the default port number in the `_config.yml` file

```
port: 5000
```

- If you want to use a different baseurl to access website, you can modify this property in the `_config.yml` file

```
baseurl: portfolio
```

By applying the two tweaks above, you can now access to the website by going to `http://localhost:5000/portfolio`

<p align="right"><a href="#about">back to top ⬆️</a></p>

# Requirements

To test the website locally, you’ll need:

- [Ruby](https://www.ruby-lang.org/en/)
- The [github-pages](https://github.com/github/pages-gem) gem

## Installing ruby
There are [lots of different ways to install ruby](https://www.ruby-lang.org/en/documentation/installation/).

In Mac OS X, older versions of ruby will already be installed. But I use the [Ruby Version Manager (RVM)](https://rvm.io/) to have a more recent version. You could also use [Homebrew](https://brew.sh/).

In Windows, use [RubyInstaller](https://rubyinstaller.org/). (In most of this tutorial, I’ve assumed you’re using a Mac or some flavor of Unix. It’s possible that none of this was usable for Windows folks. Sorry!)

## Installing the github-pages gem
Run the following command:

```
$ gem install github-pages
```

This will install the github-pages gem and all dependencies (including [jekyll](https://jekyllrb.com/)).

## Later, to update the gem, type:

```
$ gem update github-pages
```

<p align="right"><a href="#about">back to top ⬆️</a></p>

# Jekyll theme modifications

This website is based on the [Jalpc theme](https://github.com/jarrekk/Jalpc) that you can see [here](https://jarrekk.github.io/Jalpc/).

## Sections and content

I have made a few changes to adapt website sections to my needs:

- Delete unused sections (skills, links)
- Delete all blog content (posts, categories)
- Disable carousel because I only use one banner (in `_includes/carousel.html`)

## CSS modifications

I have modified the following contents in the `_sass/_style.scss` file:

- Replace the main theme color (#3385FF) with my resume color (#132b4f)
- Increase texts size
- Make the navigation bar opaque (.navbar-default)

## Acknowledgments

- [Jekyll](https://github.com/jekyll/jekyll)
- [Jalpc Jekyll theme](https://github.com/jarrekk/Jalpc)
- [README Template](https://github.com/YousefIbrahimismail/Project-README-Template)

## License

- [MIT License](./LICENSE)

<p align="right"><a href="#about">back to top ⬆️</a></p>

# Hugo theme Hermit

Hermit is a minimal and fast theme for Hugo. It's built for bloggers who want a simple and focused website.

![](https://github.com/Track3/hermit/raw/master/images/screenshot.png)

## Features

* A single-column layout and carefully crafted typography offers a great reading experience.
* Navigations and functions are placed in the bottom bar which will hide when you scroll down.
* Featured image is supported. It will be displayed as a dimmed background of the page.
* Displays all of your posts on a single page, with one section per year, simple and compact.
* Extremely lightweight and load fast. No third party framework, no unnecessary code.
* Responsive & Retina Ready. Scales gracefully from a big screen all the way down to the smallest mobile phone. Assets in vector format ensures that it looks sharp on high-resolution screens.

![](https://github.com/Track3/hermit/raw/master/images/hermit.png)

## Getting started

### Installation

Run this command from the root of your Hugo directory (Git needs to be installed):

```bash
$ git clone https://github.com/Track3/hermit.git themes/hermit
```

Or, if your Hugo site is already in git, you can include this repository as a [git submodule](https://git-scm.com/book/de/v1/Git-Tools-Submodule). This makes it easier to update this theme. For this you need to run:

```bash
$ git submodule add https://github.com/Track3/hermit.git themes/hermit
```

Alternatively, if you are not familiar with git, you can download the theme as a `.zip` file, unzip the theme contents, and then move the unzipped source into your `themes` directory.

For more information, read the official [documentation](https://gohugo.io/themes/installing-and-using-themes/) of Hugo.

### Configuration

The example config file can be found in the theme's `exampleSite` folder. You can just copy the `config.toml` to the root directory of your Hugo site. There are instructions in the example config file, feel free to change strings as you like to customize your website.

#### Favicon

Use [RealFaviconGenerator](https://realfavicongenerator.net/) to generate these files, put them into your site's `static` folder:

* android-chrome-192x192.png
* android-chrome-512x512.png
* apple-touch-icon.png
* favicon-16x16.png
* favicon-32x32.png
* favicon.ico
* mstile-150x150.png
* safari-pinned-tab.svg
* site.webmanifest

#### Social icons

The following icons are supported, please make sure the `name` filed is exactly one of these:

* codepen
* facebook
* github
* gitlab
* instagram
* linkedin
* slack
* twitter
* youtube
* email

### Manage content

* Keep your regular pages in the `content` folder. To create a new page, run `hugo new page-title.md`
* Keep your blog posts in the `content/posts` folder. To create a new post, run `hugo new posts/post-title.md`

## Acknowledgments

* [normalize.css](https://necolas.github.io/normalize.css/) - [MIT](https://github.com/necolas/normalize.css/blob/master/LICENSE.md)
* [animate.css](https://daneden.github.io/animate.css/) - [MIT](https://github.com/daneden/animate.css/blob/master/LICENSE)
* [feather](https://feathericons.com/) - [MIT](https://github.com/feathericons/feather/blob/master/LICENSE)

Thanks!

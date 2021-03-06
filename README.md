# Codzila

A content focused responsive theme for [Ghost](http://github.com/tryghost/ghost/).
Heavily based on attila by zutriken (https://github.com/zutrinken/attila).

This project is still a work in progress.

## Demo



## Screenshots


## Features

* Responsive layout
* Navigation support (Sort of?)
* Paralax cover images for posts, author archives and blog
* Author informations for posts and author archives
* Featured posts
* Reading progress for posts (commented-out by default)
* Automatic code syntax highlight and line numbers (using prism.js)
* Disqus support
* Subscribers support
* Sharing buttons

## Setup

To enable [Disqus](https://disqus.com/) comments go to your blogs code injection settings and add `<script>var disqus = 'YOUR_DISQUS_SHORTNAME';</script>` to your blog header.

## Development

Install [Grunt](http://gruntjs.com/getting-started/):

	npm install -g grunt-cli

Install Grunt dependencies:

	npm install

Build Grunt project:

	grunt build

The zip Grunt task packages the theme files into `dist/<theme-name>.zip`, which you can then upload to your site.

	grunt zip

## Copyright & License

Copyright (C) 2015-2019 JF Boily - Released under the [MIT License](https://github.com/jfboily/codzila/blob/master/LICENSE).

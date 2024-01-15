# { Personal } Jekyll Theme
![Build Status](https://travis-ci.org/le4ker/personal-jekyll-theme.svg?branch=master)
![license](https://img.shields.io/badge/license-MIT-blue.svg?link=https://github.com/dono-app/ios/blob/master/LICENSE)
[![Join the chat at https://gitter.im/PanosSakkos/personal-jekyll-theme](https://badges.gitter.im/Join%20Chat.svg)](https://gitter.im/panossakkos/personal-jekyll-theme?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)

{ Personal } is a free responsive Jekyll theme, forked from [here](https://le4ker.github.io/personal-jekyll-theme/).

## My changes

* Orangeified it, of course.
* I've simplified the menu nav bar to be more old-school - direct links, no if statements.
* Removed a bunch of stuff I don't need.

## How to run locally

Install jekyll and dependencies:

```shell
./scripts/install
```

Build locally:

```shell
./scripts/serve-production
```

View locally:

[http://127.0.0.1:4000](http://127.0.0.1:4000)

## RSS feed

The RSS feed is automatically generated and placed in /feed.xml.

## Sitemap

The Sitemap is automatically generated and placed in /sitemap.xml.

## Create a new blogpost

Run the script with the file name of the post as an argument:

```shell
cd <your { Personal } repo>
./scripts/newpost hello-world
```

A new post template with name YYYY-MM-DD-hello-world.md will be created under ./_posts, with the current date.

## Generate tag pages

```shell
./scripts/generate-tags
```

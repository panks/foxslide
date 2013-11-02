# foxslide #

Forked from [https://github.com/sevenadrian/foxslide](https://github.com/sevenadrian/foxslide)

Live theme preview available at [panks.me](http://panks.me).

This is a theme built for [Octopress](http://Octopress.org) that is a work in progress with inspirations from all over the web. Built on top of [bootstrap](http://twitter.github.com/bootstrap/) and [html5 boilerplate](http://html5boilerplate.com/), and has SEO considerations along with instagram and twitter widgets out of the box.

## Installation ##

````
$ cd yourOctopress
$ git submodule add https://github.com/panks/foxslide .themes/foxslide
$ git submodule update --init
$ rake install['foxslide']
$ rake generate
````

### Grab the latest updates ###

````
$ cd yourOctopress
$ git submodule update
# regenerate, make changes, etc...
````

### Alternate installation without git submodule ###
````
$ cd yourOctopress
$ git clone https://github.com/panks/foxslide .themes/foxslide
$ rake install['foxslide']
$ rake generate
````

## Pull-Requests Welcomed! ##

This is a first draft and can definitely be improved on. Pull requests are very much welcomed and desired!

### Demo ###

This is the theme currently powering the site at [panks.me](http://panks.me)

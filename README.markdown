littleweaver.github.io
===================

Little Weaver Web Collective's [Jekyll][]-powered list of open source projects.

Updating the website requires the following Ruby Gems:

* [Jekyll][]
* [Compass](http://compass-style.org/)
* [Bootstrap-SASS](https://github.com/twbs/bootstrap-sass)
* [kramdown](http://kramdown.gettalong.org/)

You can install them using Bundler:

```bash
gem install bundler # if not already installed
bundle install # from the root of the littleweaver.github.io repo
```

To generate and test the site locally, we recommend:

```bash
jekyll serve --watch
```

To modify the styles, you must use Compass:

```bash
cd static
compass watch
```

or use [Compass.app](http://compass.kkbox.com/)

[Jekyll]: http://jekyllrb.com/

# express-api-docs

This is the repository for the Express API documentation and is published to
[expressjs.github.io/express-api-docs](http://expressjs.github.io/express-api-docs)
as a [GitHub Pages](https://pages.github.com/) website.

NOTE: This API documentation is also published, along with additional technical documentation at
[http://expressjs.com](http://expressjs.com).

## Local Setup

GitHub Pages websites being served through [Jekyll](http://jekyllrb.com/), you will need to replicate
the setup on your local machine to preview the website locally.

If you don't have them already, install Ruby and Bundler by following the instructions [here](https://help.github.com/articles/setting-up-your-pages-site-locally-with-jekyll/).

Once cloned, `cd` to the repository directory and run

```
bundle install
```

Bundler will look in the Gemfile for which gems to install. The `github-pages` gem includes the same version of Jekyll and other dependencies as used by GitHub Pages, so that your local setup mirrors GitHub Pages as closely as possible.

run Jekyll using the following command:

```
$ bundle exec jekyll serve
```

Then, load [http://localhost:4000/](http://localhost:4000/) on your browser.

Jekyll uses [Kramdown](http://kramdown.gettalong.org/quickref.html) which supports [GFM](http://kramdown.gettalong.org/parser/gfm.html).

You can use GFM fenced code blocks for javascript in the docs. E.g.

    ```js
    var express = require('express');
    var app = express();
    app.listen(3000);
    ```

The default GitHub Pages syntax highlighting has been disabled in `_config.yml` to allow highlighting with prism.js.

To understand the template system used by Jekyll, read the [Liquid template engine docs](http://liquidmarkup.org/).

---
Copyright (c) 2016 StrongLoop, IBM, and Express Contributors

License: MIT

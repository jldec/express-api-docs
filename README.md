# express-api-docs

This is the repository for the Express API documentation and is published to
[expressjs.github.io/express-api-docs](http://expressjs.github.io/express-api-docs)
as a [GitHub Pages](https://pages.github.com/) website.

NOTE: This API documentation is also published, along with additional technical documentation at
[http://expressjs.com](http://expressjs.com).

## Local Setup

GitHub Pages websites being served through [Jekyll](http://jekyllrb.com/), you will need to replicate
the setup on your local machine to preview the website locally.  If you don't have them already, install:

- [Ruby](https://www.ruby-lang.org/en/documentation/installation/)
- [Jekyll](http://jekyllrb.com/docs/installation/)

Once installed, `cd` to the repository directory and run Jekyll using the following command:

```
$ cd express-api-docs
$ jekyll s
```

Then, load [http://localhost:4000/](http://localhost:4000/) on your browser.

Jekyll uses a variant of Markdown known as [Kramdown](http://kramdown.gettalong.org/quickref.html).
Read up the docs if you need to go beyond basic Markdown in the doc files.

To understand the template system used by Jekyll, read the [Liquid template engine docs](http://liquidmarkup.org/).

## Contributing

Feel free to make changes to the template files or the document files.
The supporting docs are located in their respective directories, and the API docs are
located under the `_includes` directory.

---
Copyright (c) 2016 StrongLoop, IBM, and Express Contributors
License: MIT

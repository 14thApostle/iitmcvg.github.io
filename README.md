# Official Site for CVI-IITM

<img src=/assets/avatar.png width=500 height=300></img>

A Github hosted site at [link](https://iitmcvg.github.io)

Theme based on [Minimal Mistakes Jekyll Theme](https://mmistakes.github.io/minimal-mistakes/): whose documentation may be found [here](https://mmistakes.github.io/minimal-mistakes/docs/quick-start-guide/)

---

## RoadMap

Date: 12th May 2018.

1. [x] Jupyter notebook conversion and integration. (jupyter nbconvert)
2. [x] Google Analytics.
3. [x] New favicon.
4. [ ] Update projects and documentation.
5. [x] Add contribution guidelines
6. [ ] Update a Travis CI build status.
7. [x] MathJax support for equations.
8. [ ] Google Insight Optimisation: we currently score a 90.
9. [x] Setup scripts and Ipynb converter.

---
## Install a local copy

Linux and macOS is supported.

* Run `bash utils/setup.sh`.

* Run `bundle exec jekyll serve --drafts --trace`.

or

* Run 'bash utils/run.sh'

In both cases, drafts will be visible. You can use this to preview your local changes.

Send in a pull request to contribute your article.

---
## Convert .ipynb to a Blog post

If you would not like to export your notebook manually, you can choose to use the conversion script. This will  convert the notebook into a markdown file with the appropriate templating.

The .ipynb notebook may be referenced from anywhere on your local machine.

To use the same:

```
usage: convert_nb.py [-h] -nb NOTEBOOK -t TITLE -d DESCRIPTION [-e] [-ty TYPE]
                     [-bp BLOGPATH]

Convert .ipynb notebook into a blog post

optional arguments:
  -h, --help            show this help message and exit
  -nb NOTEBOOK, --notebook NOTEBOOK
                        notebook path
  -t TITLE, --title TITLE
                        Title of article [post|page|any class type]
  -d DESCRIPTION, --description DESCRIPTION
                        Description of article
  -e, --execute         Execute the jupyter notebook before converting
  -ty TYPE, --type TYPE
                        notebook type
  -bp BLOGPATH, --blogpath BLOGPATH
                        Blogsite path
```
---
## Contributing

We would be happy to accept contributions to articles as our site mature.
You can send in a pull request after conforming to these [guidelines](_pages/Contributing.md). :smile:

----

## Comment Policy (Disqus)

We have largely based our policy on this : _The Mary Sue_: [The Mary Sue’s Comment Policy](http://www.themarysue.com/comment-policy/)

We might change this as we proceed.

---

## Form Submissions

* [Staticman](https://staticman.net/docs/)
* [Formspree](https://formspree.io/)

---

## MathJax Support

Added by using the `use_math` tag.

For now defaulted it to every post, page. Will revert in the future in case the pages slow down.

References for the Syntax:

* https://gist.github.com/mikelove/cbf6eb431406852ba725
* http://www.dianacai.com/blog/2015/09/12/making-blog/
* And Ofcourse this: http://www.gastonsanchez.com/visually-enforced/opinion/2014/02/16/Mathjax-with-jekyll/

We'll stick to kramdown render (for markdown), since it plays fairly nice with both Jekyll 3.x and MathJax.

---

## Credits

### Theme

**Michael Rose**

- <https://mademistakes.com>
- <https://twitter.com/mmistakes>
- <https://github.com/mmistakes>
- A bit of inspiration from here too : <https://mademistakes.com/articles/using-jekyll-2016/>

### Icons + Demo Images:

- [The Noun Project](https://thenounproject.com) -- Garrett Knoll, Arthur Shlain, and [tracy tam](https://thenounproject.com/tracytam)
- [Font Awesome](http://fortawesome.github.io/Font-Awesome/)
- [Unsplash](https://unsplash.com/)

### Other:

- [Jekyll](http://jekyllrb.com/)
- [jQuery](http://jquery.com/)
- [Susy](http://susy.oddbird.net/)
- [Breakpoint](http://breakpoint-sass.com/)
- [Magnific Popup](http://dimsemenov.com/plugins/magnific-popup/)
- [FitVids.JS](http://fitvidsjs.com/)
- Greedy Navigation - [lukejacksonn](http://codepen.io/lukejacksonn/pen/PwmwWV)
- [jQuery Smooth Scroll](https://github.com/kswedberg/jquery-smooth-scroll)

---

## License

The MIT License (MIT)

Copyright (c) 2017 CVI-IITM

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
